# NFL DFS Optimizer and Lineup Setup

Served at https://optimizer.jamestroupis.com/.

- `index.html`: the Optimizer (sandbox).
- `lineup-setup/index.html`: Lineup Setup (fills DraftKings entries).
- `critique/index.html`: Critique My Lineups (builds a request for critical feedback from an AI).
- `rate/index.html`: Rate My Lineup (one lineup: pick cash or tournament, optionally upload a screenshot that is read in the browser, get a file to send to an AI).
- `rate/ocr/`: Tesseract.js (Apache 2.0), the in-browser text reader used for screenshots. Loaded only when a screenshot is added.
- `playbook.md`: the playbook text Lineup Setup puts into each AI document.
- Slate data: both pages read this week's salaries, projections and slate name from the owner's Google Sheet (tabs Settings, Salaries, Projections) on every visit. Edit the sheet to update the slate.
- `slate.json`: backup copy of the slate, used only when the sheet cannot be reached. Refresh it from `/#publish`.
