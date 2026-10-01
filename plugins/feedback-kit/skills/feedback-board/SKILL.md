---
name: feedback-board
description: Builds board.html - a one-page board of the week's feedback from work/triage.csv, for the team to open in a browser.
---

1. Read work/triage.csv and the CSV it came from (inputs/feedback.csv unless I name another file).
2. Use the frontend-design skill (frontend-design:frontend-design) for the look, if it is installed. Keep everything self-contained anyway.
3. Write board.html directly with the Write tool: one self-contained file. All data inside the file, no internet needed, no external fonts or scripts. Don't write or run any Python or other scripts to build it.
4. The board shows:
   - At the top: total messages, number URGENT, and the busiest team
   - A count per category
   - Every URGENT message: id, channel, category, team and the customer's exact words
   - The ideas and praise, in the customers' words
5. Tell me to open board.html in a browser.
