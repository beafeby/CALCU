# SM/SL Calculator PWA

First screen asks user to choose TARGET or ACTUAL.

TARGET: enter Projected AC, Projected GC (up to 16 comma-separated values), Average Crew Rate, and Crew Total Hours. Sales = AC × total GC.

ACTUAL: enter Actual Sales, Actual GC (up to 16 comma-separated values), Average Crew Rate, and Crew Total Hours. AC = Actual Sales ÷ total GC.

Both modes: Crew Labor ₱ = Crew Total Hours × Average Crew Rate. Crew Labor % = Crew Labor ÷ Sales × 100. GCPCH = total GC ÷ Crew Total Hours. Raw Waste = Sales × 0.20%. Complete Waste = Sales × 0.50%.

Results appear progressively as enough valid values are entered. Currency is PHP.

To update GitHub Pages, replace index.html, manifest.webmanifest, sw.js and README.md in the repository root. Keep the existing two PNG icons in icons/. Commit changes. Pages should deploy from main / (root).
