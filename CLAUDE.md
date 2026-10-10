# CLAUDE.md

Project: web-based graphical UI designer for CircuitPython displayio.
See `design requirements.md` for goals and `README.md` for the overview.

## Rules

- No Claude attribution in commit messages or other places
  (no `Co-Authored-By: Claude`, no "Generated with Claude Code" lines in commits, PRs, code or docs).
  The only exception is the single note in `README.md` that the project is built with the help of Claude.
- Git commits: plain `git commit` only, never bypass flags (`--no-verify`, GPG bypasses).
  If the GPG passphrase times out, wait for the user.

## Where Claude notes live

All todos and Claude memos are kept in this repo, not in external memory:

- `TODO.md` - open tasks
- `NOTES.md` - decisions, memos, context worth keeping
