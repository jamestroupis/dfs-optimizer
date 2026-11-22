# NFL DFS Optimizer and Lineup Setup

Served at https://optimizer.jamestroupis.com/.

- `index.html`: the Optimizer (sandbox).
- `lineup-setup/index.html`: Lineup Setup (fills DraftKings entries).
- `critique/index.html`: Critique My Lineups (builds a request for critical feedback from an AI).
- `playbook.md`: the playbook text Lineup Setup puts into each AI document.
- Slate data: both pages read this week's salaries, projections and slate name from the owner's Google Sheet (tabs Settings, Salaries, Projections) on every visit. Edit the sheet to update the slate.
- `slate.json`: backup copy of the slate, used only when the sheet cannot be reached. Refresh it from `/#publish`.
