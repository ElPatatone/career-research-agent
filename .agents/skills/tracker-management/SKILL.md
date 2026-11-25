---
name: tracker-management
description: Read and reconcile a local vacancy tracker, select existing records for recheck and safely persist assessed vacancies, history and follow-ups.
---

# Tracker management

Read the tracker named in the request or private brief before discovery. For a first manual discovery test without a master, use an ignored `data/test-vacancies.csv`. If absent, create it using just the header of [sample-vacancies.csv](../../../data/sample-vacancies.csv). Reopen it on subsequent tests. The sample's fictional rows are available for offline exercises on a copy. If given an unfamiliar workbook, inspect its schema, sheets, formulas and manual fields read-only. Describe the mapping and await agreement before any migration or live write.

Select a manageable recheck set from flagged roles, stale promising evidence, due actions and unresolved routes. Weigh interest, urgency, fit and evidence quality. Record selection and deferred items. Reserve time for fresh discovery. Pass identities, prior observations and precise questions to verification.

Reconcile assessed records against the starting master and each other. Prefer an employer-scoped requisition ID. Otherwise normalise company, title and location for comparison (case, whitespace and equivalent location spellings). Use the actual posting, team, duties and employment terms to resolve ambiguity. Never merge on title alone. Preserve distinct requisitions and flag uncertain matches for review before any destructive consolidation. Retain stable local IDs, original discovery dates and primary discovery sources. Pass secondary sightings to reporting.

Stage changes for every assessed vacancy including exclusions and follow-ups. Retain the discovery and official application URLs separately. Record discovery, original posting (when known) and last checked dates in ISO format, dated verification evidence, terms and constraints, fit and priority rationales, disposition, next action and historical changes. Preserve human notes, user statuses, flags, unknown columns and unrelated rows. Record the reason, evidence, owner, action, next check and eventual disposition of held matches in their tracker records so reporting can assemble the omission review. Preserve prior review decisions when resolving an omission.

For an agreed local CSV, stage a complete replacement beside the master. Re-read the original before replacing it and reconcile any intervening edits. Use a single writer, defer if another update is active, and use an atomic same-filesystem replacement. For another agreed format preserve its native structure and manual features. Reopen the saved file, verify expected IDs and changed fields, row preservation and untouched manual values. Reconcile any separate review updates too. On partial failure report exactly which writes were confirmed. On retry inspect current records before applying outstanding changes.

Return record IDs split into existing rechecks and distinct new assessments, review entries, changes and confirmation evidence. If the master is unavailable, return provisional assessments and skip claims of novelty or persistence.
