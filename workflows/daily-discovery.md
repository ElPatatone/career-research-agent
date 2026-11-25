# Daily discovery

1. **Load inputs.** Read the current brief, CV and professional experience in `context/`. Confirm the contents are readable. Use [tracker-management](../.agents/skills/tracker-management/SKILL.md) to open the designated tracker or initialise the first test tracker. Record which inputs loaded.
2. **Select rechecks.** Use tracker-management to identify existing vacancies that warrant attention. An empty test tracker gives zero rechecks.
3. **Verify existing vacancies.** Use [vacancy-verification](../.agents/skills/vacancy-verification/SKILL.md) on the selected records. Retain their IDs and note material changes.
4. **Discover new leads.** Use [job-discovery](../.agents/skills/job-discovery/SKILL.md). Keep notes on sources, companies, sightings and access failures for the report.
5. **Verify new opportunities.** Use vacancy-verification on selected leads. Keep unassessed search hits separate.
6. **Assess roles.** Use [role-assessment](../.agents/skills/role-assessment/SKILL.md) on both rechecks and new assessments. Carry forward fit, priority and unresolved questions.
7. **Update the tracker.** Use tracker-management to reconcile IDs, record assessments and confirm the saved changes. Distinguish new assessments from rechecks.
8. **Generate the report.** Use [report-generation](../.agents/skills/report-generation/SKILL.md). Create `reports/` if needed, save a dated Markdown report under an unused filename and confirm it can be read. Return its path and any outstanding work.

When a stage fails, complete unaffected steps and mark partial results explicitly. Missing personal context limits the run to generic findings. If a designated tracker is missing, unreadable or unsafe to update, report provisional findings with novelty and persistence unconfirmed. Use unknown for counts that cannot be determined. If report delivery fails, return the findings in the session.
