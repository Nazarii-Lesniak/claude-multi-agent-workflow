# Quality Workflow Plugin

A multi-agent workflow plugin for automated code review, test generation, and quality assurance.

## Components
- **Agents**: `reviewer` (read-only code analyzer) and `tester` (test builder/runner).
- **Command**: `/workflow` — Orchestrates reviewer and tester agents sequentially and in parallel.
- **Skill**: `quality-check` — Best practices for Express API endpoints.
- **Hook**: Post-tool execution hook for running automated tests.

## Installation
```bash
/plugin marketplace add .
/plugin install quality-workflow
```
