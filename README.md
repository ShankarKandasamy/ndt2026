# NDT2026: NDT data as a directed knowledge graph

Companion data for the paper *NDT Data as a Directed Knowledge Graph*
(S. Kandasamy, NDT.net 2026).

The study tested whether storing non-destructive testing (NDT) records as a typed
knowledge graph answers practical inspection questions better than keyword search.
It used a synthetic archive whose correct answers were fixed in advance by the
generator that wrote it.

## What is here

| Path | Contents |
|---|---|
| `archive/tested/` | The 238 records the tests ran on, as PDF, Word, Excel and e-mail files. |
| `archive/additional/` | 521 further records from the same history (routine datasheets, certificates, permits, e-mails), rendered after the study. They were not used in any test. |
| `QUESTIONS.md`, `questions_240.csv` | Test 1's 240 questions: which were tested, filled but not drawn, or dropped, with the per-question results for the 90 tested. |
| `results/test1-results.md` | Test 1 results by family, by number of identifier steps, by wording, language and entry point, with paired bootstrap intervals. |
| `results/figures/` | The figures from the paper. |

## The archive

A fictional operator runs two sites:

- **Hamilton (Ontario):** an amine treating unit, 1995 to 2026, under an owner-user API 570
  program, with two successive NDT contractors and an FFS consultant. Records in English.
- **Werk Niederrhein (Lower Rhine):** a solvent recovery unit, 2002 to 2026, under the German
  Betriebssicherheitsverordnung with an approved inspection body. Records in German.

The archive holds 759 records: survey reports and datasheets, procedures and their
revisions, inspection plans, calibration and personnel certificates, NCRs, FFS
assessments, MOC records, permits, transmittals and e-mail. The 238 records in
`archive/tested/` were drafted with Gemini 3 Flash; the 521 in `archive/additional/`
were drafted later with Gemma 4 31B, so their writing style differs. Wall thicknesses
follow a corrosion model with ultrasonic measurement noise.

All organisations, people, plants and identifiers are fictional.

## Licence

The archive, question list and results are licensed under CC BY 4.0 (`LICENSE-DATA`).

## Citation

S. Kandasamy, "NDT Data as a Directed Knowledge Graph", NDT.net, 2026.
