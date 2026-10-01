---
name: draft-replies
description: Drafts a reply for every URGENT message in work/triage.csv, in Brewmark's voice, and saves work/replies.md.
---

1. Read work/triage.csv and the CSV it came from (inputs/feedback.csv unless I name another file).
2. For every URGENT row, write a reply of at most 70 words:
   - Start with the customer's problem in their own words, so they know we read it.
   - Say which team is handling it and when we will update them (within 24 hours).
   - Never promise a refund, a replacement, a delivery date or compensation. The team decides that.
   - Warm and plain. No "we regret the inconvenience", no "valued customer".
   - Reply in the customer's language style. If they wrote in Hinglish, answer in simple Hinglish.
3. Save work/replies.md: for each reply, a heading "id <n> - <channel>", then the reply.
4. Show me how many replies you wrote.
