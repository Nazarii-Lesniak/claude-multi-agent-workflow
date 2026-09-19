Run a complete quality assurance workflow using multi-agent orchestration.

1. **Parallel Step**: Run the `reviewer` agent to analyze `course-api/` for bugs, while simultaneously scanning test files.
2. **Dependent Step**: Pass the findings from the `reviewer` agent to the `tester` agent to update or add missing test cases in `course-api/` and ensure `npm test` passes.
