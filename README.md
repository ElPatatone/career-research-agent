# Career Research Agent

This project explores whether Codex CLI can reproduce a weekday startup job search that already runs as a managed ChatGPT Work scheduled task. The search looks for early-career roles in the UK and Europe where the candidate can own meaningful work. Titles vary, and listings can remain visible after applications close. The workflow checks both the responsibilities and the current application route. [Original task](docs/chatgpt-work-v1.md)

The managed task uses one long prompt. Here, [the daily workflow](workflows/daily-discovery.md) sets the order of work and [five skills](.agents/skills) describe discovery, verification, assessment, tracker updates and reporting. This makes it possible to inspect a decision and revise the relevant procedure after a manual run. [Design decisions](docs/design-decisions.md)

## First manual test

Place the current CV, professional experience and job-search brief in `context/` (create the directory on a fresh checkout). From the repository root, with Codex CLI and web search available, run:

```sh
codex --search 'Run workflows/daily-discovery.md with the files in context/ and use data/test-vacancies.csv as the working tracker.'
```

On first use, the workflow creates that private test tracker from the [sample CSV header](data/sample-vacancies.csv). Subsequent runs reuse it. Reports go in `reports/`. The sample's four fictional rows can be explored separately.

The repository version is an early manual implementation. Its behaviour with real candidate files, live sources and the eventual master tracker still needs testing and refinement.
