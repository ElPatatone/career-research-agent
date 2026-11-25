# Design decisions

- **Start with the working process.** The managed weekday task established the research requirements. Its instructions provide the reference for manual trials here.
- **Use Codex CLI as the harness.** It already provides model execution and tools. Keeping the research procedures in ordinary Markdown leaves room to try another harness later.
- **Separate sequence from procedure.** One workflow orders the daily run. Five repository-scoped skills hold the practical instructions, so a change to source selection or verification has a clear home.
- **Keep personal inputs and results private.** Candidate context, working tracker data and generated reports live apart from versioned instructions. A sanitised CSV provides a starting format for experiments.
- **Start with a manual run.** The agent can use ad hoc code for calculations and spreadsheet work. Repeated work or observed failures will inform any decision to add permanent scripts or infrastructure.
