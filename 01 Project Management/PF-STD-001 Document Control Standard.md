---
document_id: PF-STD-001
title: Document Control Standard
revision: 0.1
status: Working Draft
owner: TJ
engineering_lead: Miles
last_updated: 2026-08-11
approved_baseline: none
---

# Document Control Standard

## Source of truth

The committed Markdown file is the record. An approved revision is the authority. Chat and raw notes are source material only.

## Revisions

- `0.1`, `0.2`, etc.: drafts
- `1.0`: first approved baseline
- `1.1`, `1.2`, etc.: approved minor revisions
- `2.0`: major approved change

## Workflow

1. Discuss or research.
2. Draft a candidate requirement, decision, risk, task, or document change.
3. TJ reviews.
4. Update controlled files.
5. Commit with a meaningful summary.
6. Push to GitHub.

## Commit format

`DR-##: concise description`

Example: `DR-00: Import initial controlled-document baseline`

## Naming

Controlled documents begin with a permanent ID. Do not put revision numbers in filenames; revision metadata and Git history carry that information.

