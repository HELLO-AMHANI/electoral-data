# electoral-data

# Nigeria Presidential Elections & Global Incumbent Re-election Dataset

## Overview

This project combines two research threads into a single Google Sheets workbook for analysis:

1. **Global incumbent re-election outcomes** — presidents who contested re-election worldwide, and whether they won or lost.
2. **Nigeria 2015 & 2023 presidential elections** — candidate-level results, voter turnout, and registered voter data.

The goal is to place Nigeria's two most consequential recent elections (2015: first incumbent defeat in Nigerian history; 2023: most fragmented result in the Fourth Republic) in the context of global and regional incumbency patterns.

## Structure (3 sheets)

### Sheet 1 — Incumbent Presidents (Worldwide)
Every row is one incumbent's re-election attempt.

| Column | Description |
|---|---|
| Country | Country name |
| Region | Nigeria / West Africa / East Africa / Southern Africa / North Africa / Central Africa / North America / Europe-Asia / South America etc. |
| President | Incumbent's name |
| Election Year | Year of the re-election contest |
| Incumbent Contesting? | Yes / No / context notes (e.g. succession cases) |
| Outcome (Won/Lost) | Result for the incumbent |
| Term # if Won | Which term this represents |
| Margin / Vote Share | Vote share or margin, where confirmed |
| Notes | Context (disputes, annulments, coups, term-limit changes, etc.) |
| Source | Source(s) used for verification |

**Coverage:** Nigeria (complete, 1979–2023), West Africa (partial — Côte d'Ivoire, Ghana), broader Africa (6 countries: Kenya, Uganda, Zimbabwe, Egypt, Cameroon, Rwanda), Worldwide (flagship cases only: United States full history 1800–2024, Russia, Venezuela). **~40 African and ~150 worldwide countries are not yet researched.**

### Sheet 2 — 2015 Nigeria Presidential Election
Merged from three original tabs: candidate results, voter turnout, registered voters.

- **Candidate results:** all 14 candidates, votes, % of valid votes, win/loss. Verified — the 14 figures sum exactly to the certified total valid votes (28,587,564).
- **Turnout data:** accredited voters, total votes cast, valid votes, rejected votes (two slightly different figure sets exist in public sources — both included, INEC/Channels TV figures marked as primary).
- **Registered voters:** 68,833,476 (primary) — a second widely-cited figure (67,422,005) also included since sources disagree slightly.

### Sheet 3 — 2023 Nigeria Presidential Election
Same structure as Sheet 2.

- **Candidate results:** top 4 candidates (Tinubu, Atiku, Obi, Kwankwaso) have official INEC-certified vote counts. The remaining 14 minor candidates are listed by name/party with a verified **combined** total (648,474 votes) — individual national vote counts for these 14 were not found consolidated in any single source, and are marked `n/a — not verified` rather than estimated.
- **Turnout data:** accredited voters, total votes cast, valid votes, rejected votes — all INEC-certified.
- **Registered voters:** 93,469,008, plus PVC (Permanent Voter Card) collection statistics.

## Verification Standard

Every populated cell is checked against at least one primary/official source (INEC) or cross-checked across two independent secondary sources (BBC, Reuters, AP, Al Jazeera, France24, IFES ElectionGuide, International IDEA, Wikipedia). Cells that could not be verified to this standard are explicitly marked `n/a — not verified` rather than estimated or guessed.

## Known Gaps

- **Incumbent sheet:** ~African countries and worldwide countries not yet researched.
- **2023 candidates:** individual national vote totals for 14 of 18 candidates not available — would require manual aggregation of INEC's 37 state-level results (36 states + FCT).
- Some 2015 figures (accredited voters, total votes cast) have two slightly different published versions; both are retained rather than silently picking one.

## Sources

INEC (Independent National Electoral Commission, Nigeria), IFES ElectionGuide, International IDEA, BBC, Reuters, AP, Al Jazeera, France24, VOA, CNN, Wikipedia, African Studies Centre Leiden, Nigeria Civil Society Situation Room.

## Next Steps / How to Extend

- Continue incumbent research for remaining African and worldwide countries using the same two-source verification standard.
- Aggregate INEC's state-by-state 2023 results to fill in individual minor-candidate vote totals.
