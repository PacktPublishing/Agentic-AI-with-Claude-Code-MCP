# AGENTS.md

## Repository purpose
This repository is a small demo web app used for showing GitHub MCP workflows with Claude Code.

## Working style
- Keep changes tightly scoped to the current GitHub issue
- Do not refactor unrelated code
- Prefer editing existing files over creating new files
- Explain the plan before making code changes
- After implementation, summarize the files changed and the behavior added

## Git workflow
- Use feature branch names in the form `feature/<issue-number>-<short-description>`
- Write concise conventional commit messages
- Draft pull request text before creating the PR

## Validation
- Run the simplest relevant validation for the project
- For UI changes, verify behavior in the browser
- Mention assumptions or limitations in the final summary

## Communication
- Be concise and practical
- Do not make unrelated improvements
- Ask before making larger structural changes