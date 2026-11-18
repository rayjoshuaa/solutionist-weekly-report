# Solutionist Weekly Report

A simple weekly publication report website for **The Solutionist Group** (Melbourne), prepared for Jon Kenfield.

It shows, on one page:

- **This week — published:** every output for the week's topic (website article, YouTube long video, podcast episode, LinkedIn launch post, LinkedIn 90-second teaser, carousel PDF, and the CRM link pack), with its status and proof link.
- **What is next:** the simple weekly cycle for the next chapter — article ready, video and podcast, teaser and scheduling, release day, then check and report.
- **Month at a glance:** progress on *Making Sense of Family Business — 66 Common Causes of Conflict* (Book 1 on Amazon, Book 2 in progress, Book 3 planned).
- **How this report works:** a weekly update with proof links, a monthly report, and problems flagged early.

The sample content is built from a real published topic — Cause #22: The Birth Order Lottery — so the format can be reviewed before live use. In a live week, every row carries the real live link as proof.

## How it is used — the workflow

One link, bookmarked by Jon. It is the one place the whole job lives:

1. **Jon drops the month** — 4 topics in the shared folder, in one batch.
2. **Ray confirms and checks within 1 working day** — every file checked, all 4 topics entered in the pipeline, anything missing flagged early.
3. **Ray produces one topic per week** on a Thu–Tue cycle; the YouTube draft link appears in the pipeline for Jon's review.
4. **Jon checks this page in 2 minutes** — status, proof links, draft approval. No email threads.
5. **Month end** — this page's month-end version is the monthly report, and its proof links are the same links listed on the invoice.

The pipeline table shows every topic's stage and, in the "Waiting on" column, exactly what a stage is stuck on, written the same day.

## Tech

Single self-contained `index.html` (vanilla HTML/CSS, no build step). Deployed on Cloudflare Pages with automatic deployments from this repository: push a change to `main` and the live site updates.

Prepared by Ray Joshua Balingkit.
