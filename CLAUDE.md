# Project guidance for Claude Code

## Git commits and pushes

- Always commit and push as **Ouraking** (`git config user.name "Ouraking"`,
  `git config user.email "merluxe4922@gmail.com"`).
- Do **not** add `Co-Authored-By: Claude ...` or any Claude attribution lines
  (including session links) to commit messages or pull request descriptions.
- Do not create a pull request unless explicitly asked.

## Spec-Driven Development (Spec Kit)

GitHub Spec Kit is installed. Use the `/speckit-*` skills in `.claude/skills/`
for feature work, in this order: constitution, specify, (clarify), plan,
(checklist), tasks, (analyze), implement. Shared templates, scripts, and the
constitution live in `.specify/`.
