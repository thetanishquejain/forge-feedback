---
name: feedback-run
description: Runs the whole feedback desk on one CSV - triage agent, then reply drafts, then the board.
argument-hint: 'the CSV to process, e.g. inputs/week2.csv'
disable-model-invocation: true
---

CSV to process: $ARGUMENTS (if empty, inputs/feedback.csv)

1. Start the triage agent on that CSV. Wait for it to finish.
2. Follow the steps of the draft-replies skill for the same CSV.
3. Follow the steps of the feedback-board skill for the same CSV.
4. Finish with: rows, URGENT count, replies written, and "open board.html".
