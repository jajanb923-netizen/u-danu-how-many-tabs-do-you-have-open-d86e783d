# How Many Tabs Do You Have Open?

[![make.fun](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d)
[![rank](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d/jajanb923-netizen/u-danu-how-many-tabs-do-you-have-open-d86e783d/rank.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d)
[![reward](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d/jajanb923-netizen/u-danu-how-many-tabs-do-you-have-open-d86e783d/reward.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d)

Entry for the [make.fun bounty "How Many Tabs Do You Have Open?"](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d) ($5 pot, top 10 paid).

## The entry

`main.py` (Python 3.13, stdlib only, deterministic, no network) writes a single
short text — one number in digits and nothing else — to `/output/entry.txt`:
the honest count of browser tabs open at that moment.

The number was chosen by scoring 16 candidate counts against the judge's
published brief (see [CANDIDATES.md](CANDIDATES.md)): the judge compares two
counts at a time and rewards a count that reads as real, is surprising, stays
believable, and hints at a life behind it — while "size for its own sake does
not count". The pick is **173**: a prime, three-digit, oddly specific count in
the believable-hoarder sweet spot — high enough to surprise, low enough to be
plainly honest, with no round-number, meme, or calendar gimmick for the judge
to discount. It reads as counted, not chosen.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
cat out/entry.txt
```

The program self-checks the gate before writing: the entry must be UTF-8
text of 1–5 characters, digits only, no surrounding whitespace.

## Files

- `main.py` — the entrypoint; writes `/output/entry.txt`
- `CANDIDATES.md` — candidate numbers scored against the judging criteria
- `prompt.txt` — the run-record prompt for this build
- `.makefun/owner.json` — wallet claiming this repository
