Before writing anything, explore the codebase thoroughly — read the directory tree,
open key config files, trace the entry points, check the test setup, and review
any existing docs. Do not start writing until you have a clear picture of how
the project actually works.

Then generate an AGENTS.md in the root of the repo.

AGENTS.md exists so an AI agent can pick up any task in this codebase — cold,
mid-session, or after a long gap — without needing to ask basic questions.
It is machine-first but human-readable. Use real values from the project everywhere.

Cover the following, and only the following:

- What this project does and who it's for
- Tech stack and key dependencies
- Annotated directory map (every top-level entry, one line each)
- Setup: install, run, build, test, lint — exact commands
- Code conventions: naming, structure, formatting rules in use
- Agent rules: what to always do, what to never do, how to handle ambiguity
- Git conventions: commit format, branch naming, PR requirements
- Testing: framework, file locations, coverage expectations, fixtures
- Key files: entry points, critical configs, environment setup
- Out of scope: what to escalate rather than attempt

Rules for writing it:
- Every line must be actionable or orienting — cut anything decorative
- Prefer bullet points and code blocks over prose
- If two things conflict in the codebase, flag the conflict, don't pick one silently
- Accuracy over completeness — a short correct file beats a long guessed one
