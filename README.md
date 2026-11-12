# SM Crew Calculator — PWA

Choose TARGET or ACTUAL. Results update when enough inputs are present.

## TARGET
- Total GC = sum of up to 16 comma-separated GC values
- Calculated Sales = AC × Total GC
- Raw Waste = entered Target Sales × 0.20%
- Complete Waste = entered Target Sales × 0.05%
- Crew Labor = Crew Total HR × Crew Rate
- Crew Labor % = Crew Labor ÷ Calculated Sales × 100
- GCPCH = Total GC ÷ Crew Total HR

## ACTUAL
- Actual Sales and Actual GC are entered
- AC = Actual Sales ÷ Actual GC
- Raw Waste = Actual Sales × 0.20%
- Complete Waste = Actual Sales × 0.05%
- Crew Labor = Crew Total HR × Crew Rate
- Crew Labor % = Crew Labor ÷ Actual Sales × 100
- GCPCH = Actual GC ÷ Crew Total HR

All result cards appear only when enough valid inputs are available. Crew Rate is entered by the user. Currency is PHP.

Upload/replace `index.html`, `manifest.webmanifest`, `sw.js`, and `README.md` in the repository root. Keep the two PNG app icons inside `icons/`. Commit changes. The service worker cache version has been updated so clients can receive the new app.
