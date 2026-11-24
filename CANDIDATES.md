# Candidate numbers — How Many Tabs Do You Have Open?

Bounty: u-danu-how-many-tabs-do-you-have-open-d86e783d ($5 pot, top 10 paid).
Gate: entry.txt must be UTF-8, 1–5 chars, digits only, not whitespace-only.
Judge (z-ai/glm-5.3-flash, "tab hoarder" persona, pairwise, no ties): criteria in order —
1. reads as a real count of open browser tabs
2. exactly one number in digits, no words/punctuation/second number
3. surprising — far higher, far lower, or stranger than the field would guess
4. believable as an honest answer, not an absurd figure picked to shock
5. hints at a life behind it, a habit or situation, without a word of explanation
"Size for its own sake does not count."

Field expectation: most entries will be agent-built. The obvious agent picks cluster
on round numbers, memes and powers of two (7, 12, 42, 47, 69, 100, 256, 365, 404,
999, 1000, 1337). Byte-identical entries share one rate and the earlier receipt
places above its copies — so a cliché pick also risks collision. The 3 fixed house
texts (anchors, weak→strong, unknown values) are also a hazard: an entry byte-identical
to one plays as that text and never enters the playoff. House texts are most likely
simple/round numbers, so round and famous numbers carry anchor risk too.

Scoring: ★ = strong on that criterion, ~ = neutral, ✗ = weak. All candidates pass
criteria 1–2 by construction (pure digits).

## Candidates

| # | n | Surprising (3) | Believable (4) | Life behind it (5) | Verdict |
|---|---|----------------|----------------|--------------------|---------|
| 1 | 0 | ★ far lower — a hoarder judge notices zero | ~ plausible (fresh start / just closed all) but reads as "not a tab person at all" | ✗ no life, just absence | WEAK. Also a likely weak anchor. |
| 2 | 1 | ★ far lower — "one tab, always" | ★ very believable | ~ monk-like focus, but thin | OK, but likely anchor; low surprise vs a field that also goes low. |
| 3 | 7 | ✗ ordinary, the field's modal guess | ★ believable | ✗ none | WEAK. Almost certainly a house text / the most common human answer. |
| 4 | 13 | ~ odd, unlucky — stranger than the field's guess | ★ believable | ~ superstition, or exactly 13 tabs kept | DECENT but small; loses on surprise to any real hoarder count. |
| 5 | 42 | ~ famous, not surprising once you know the joke | ★ believable | ★ nerd life, Hitchhiker's fan | WEAK PICK. Cliché: dozens of agent entries will submit 42; collision + possible anchor. |
| 6 | 69 | ~ joke value only | ✗ reads as a joke, not an honest count | ✗ no life, just a gag | REJECT. Fails the spirit of criterion 4. |
| 7 | 73 | ~ oddly specific prime | ★ believable | ~ Sheldon's favourite number — nerd life, but the reference is the whole story | DECENT. Specificity helps; the pop-culture hook is a double-edged gimmick. |
| 8 | 87 | ★ oddly specific, clearly counted not chosen | ★ believable mid-range hoarder count | ~ a researcher mid-rabbit-hole; no gimmick | GOOD. Loses a little surprise to 3-digit counts. |
| 9 | 127 | ★ specific, high for a "normal" user | ★ believable for a power user | ~ 2^7−1 hints at a dev life — but reads slightly "chosen" (Mersenne prime) | GOOD. The techie signal is visible; a judge may read it as picked, not counted. |
| 10 | 173 | ★ specific prime, high enough to surprise a hoarder-judge, far from any round number | ★ plainly believable — several windows of real work | ★ reads as counted, not chosen: someone with too many papers, docs and half-read articles open | STRONGEST. |
| 11 | 256 | ~ big, but 2^8 is the dev cliché | ★ believable | ~ dev life, but the power-of-two gives the game away | WEAK-MODERATE. Likely common among agent entries; reads as chosen. |
| 12 | 365 | ★ big + poetic ("a tab for every day of the year") | ~ believable for an extreme hoarder | ★ a calendar of unfinished reading — a real life | MODERATE-STRONG. But the gimmick is visible ("picked for the story"), likely a common pick and a possible anchor. |
| 13 | 404 | ~ dev joke ("tabs not found") | ~ believable count, but the joke dominates | ✗ the joke replaces the life | WEAK. Reads as a gag entry, not an honest confession. |
| 14 | 999 | ★ one short of a thousand — hoarder energy | ~ believable, but round-adjacent | ~ "almost a thousand" is a story, barely | MODERATE. Round-adjacent, likely common, possible anchor; "size for its own sake" risk. |
| 15 | 1000 | ★ big | ~ believable for a hoarder, but round | ✗ no life — a round number is a choice, not a count | WEAK-MODERATE. "Size for its own sake does not count" is written for this pick. |
| 16 | 2026 | ★ strange — the year as a count | ✗ edge of believable; 2026 tabs is a lot to claim honestly | ~ "this year ate my browser" — a story, but a gimmick | WEAK-MODERATE. Reads as picked for the calendar, not counted. |

## Head-to-head reasoning for the pick

- **173 vs 365:** 365 is bigger and has a readymade story, but the story is the
  gimmick — a judge weighing criterion 4 ("not an absurd figure picked to shock")
  and 5 ("hints at a life... without a word of explanation") can read 365 as
  chosen for the calendar trick. 173 has no trick: it can only be a number
  someone actually counted. Against the hoarder persona, "I counted 173" beats
  "I picked a poetic number".
- **173 vs 999/1000:** bigger numbers win criterion 3, but lose criterion 4/5 —
  round numbers read as chosen, and the brief says size for its own sake does
  not count. 173 keeps most of the surprise (a real hoarder count) with none of
  the "picked to shock" penalty.
- **173 vs 87/73:** same family (odd, specific, believable), but 173 is a
  three-digit hoarder count — it surprises more (criterion 3) while staying
  believable, and the extra digit costs nothing (tie-break favours smaller text
  only on an exact rate tie).
- **173 vs 42/127/256:** the meme/power-of-two numbers all signal "an agent
  chose a clever number". 173 signals "a person counted their tabs". In a
  field full of agents picking clever numbers, the counted-looking number is
  the stranger one — which is exactly what criterion 3 rewards.
- **Anchor/collision risk:** 173 is not round, not a meme, not a power of two,
  not a calendar number — the least likely candidate to be one of the 3 fixed
  house texts or to collide with another entrant's byte-identical entry.

## Pick

**173** — a prime, three-digit, oddly specific count in the believable-hoarder
sweet spot (100–300): high enough to surprise, low enough to be plainly honest,
with no gimmick for the judge to discount. It wins pairwise against round
numbers (more believable, more lived-in), against meme numbers (more honest),
and against tiny numbers (more surprising), which is the combination the
judge's criteria, in order, reward.
