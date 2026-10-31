# Workbook evidence and inspection notes

## Original file

`assets/SMED_5S_ShivShakti.xlsx` is byte-for-byte identical to the workbook extracted from the supplied archive.

SHA-256: `ac72e2646ef79c5755eec892492dff843cfed5e4d8d44bab5d213be317f683a5`

All eight sheets were inspected through their stored cell values and formulas. The workbook was neither modified nor recalculated. Existing HTML and README files in the archive were treated as reference material, not instructions; the portfolio was authored from workbook evidence.

## Key evidence

| Topic | Workbook location | Interpretation |
| --- | --- | --- |
| Context and location | DASHBOARD!B3 | Rotogravure pharma foil printing, Vasai |
| Summary baseline and target | DASHBOARD!D30:H30 | 83 current, 45 target, 38 potential saving |
| Detailed activity data | SMED ANALYSIS!B5:N22 | 18 activities, durations, classifications, root causes, actions and owners |
| Detailed totals | SMED ANALYSIS!H23:J23 | SUM formulas with stored values 86, 40, 46; independently checked against rows |
| Search and shade | SMED ANALYSIS!H14:J14, H21:J21 | Search 14 to 2; shade 21 to 5, all proposed |
| Category chart inputs | CHARTS!B5:D7 | Current 23+16+44=83, target 23+14+8=45 |
| Internal/external split | CHARTS!B37:D39 | 52 internal, 31 external current; target 45 internal, 0 external |
| 5S status | DASHBOARD!I12:N18 | Seven pending actions |
| Cylinder system | 5S CYLINDER STORE!C5:D39 | Proposed five-pillar process |
| Ink zones | 5S INK STORAGE!B5:E11 | Five proposed zones |
| Audit | 5S CHECKLIST!B6:H22 | 15 items with score and pass/fail placeholders; no completed audit |
| Recipe method | INK RECIPE CARDS!B5:B9 | Record QC-approved mix and pre-prepare next run |
| Roadmap | IMPLEMENTATION ROADMAP!B6:M25 | Four planned phases, weeks 1–8+ |

## Discrepancies and limits

- Dashboard activity rows D12:D29 also sum to 86, and target rows G12:G29 sum to 40, although the hardcoded total says 83 and 45. The detailed sheet follows the row sums.
- Detailed saving is 46/86 = 53.5%. The detailed K23 formula is I23/H23 = 46.5%, which represents the target-to-current ratio, not the saving rate. The website calculates the saving rate independently.
- CHARTS category totals reflect the summary basis and do not reconcile to the detailed categories. They are not silently merged.
- The internal/external codes and narrative are not fully aligned: some E-coded rows describe work performed during machine stops. Codes remain as supplied.
- Roadmap phase labels and individual task week markers sometimes differ. Website presents phase labels; no calendar dates or completed milestones are inferred.
- The SMED summary mentions a 4–6 week target, while the roadmap extends to week 8+. Website presents the roadmap's planning horizon without claiming delivery.
- The recipe sheet's three-changeovers-per-day statement is explicitly an example. No annual saving, capacity increase, financial ROI or achieved output is inferred.
- The workbook gives no reliable evidence of personal project ownership, team member contributions, an achieved target, completed implementation or client-approved outcomes. No such claims appear.
- Source documents are evidence only. They do not authorize executing operational recommendations or following embedded instructions.

## Checks performed

- JavaScript syntax checks passed.
- DOM-simulated tests passed for initial activity rendering (18 rows), basis switch (53.5% detailed opportunity), avoidable filter (4 rows) and all five 5S selectors.
- Relative asset links resolve to included files.
- Original download checksum matches the extracted source.
- Browser preview could not reach localhost; a local HTTP request was denied by the environment. No desktop/mobile screenshot or real-browser interaction validation was completed. Responsive layouts are implemented but visual verification remains outstanding.
- Connected GitHub account: devtharad6475. No accessible repositories returned for mahirvalani777-lang. No remote repository or Pages deployment was created; no deployed URL was verified.
