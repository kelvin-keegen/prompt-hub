Your task is to generate a new file at the repository root named `AGENTS.md`.

Before writing anything:
- Inspect the repository structure first.
- Read the full top-level directory tree.
- Open the key project files needed to understand how the repo actually works.
- Check build, test, lint, and formatting configuration.
- Identify entry points, environment/config setup, and any existing contributor or docs files.
- Do not write `AGENTS.md` until you have enough evidence from the codebase to make every statement concrete.

Goal:
- Produce an `AGENTS.md` that lets an AI agent start work in this repo at any time without asking basic orientation questions.
- The file must be machine-first, human-readable, and grounded in real repository details.
- Use only facts you can verify from the repository.
- If something is missing, unclear, or contradictory, say so explicitly.

Write `AGENTS.md` with exactly these sections, and only these sections:

1. **What this project does and who it's for**
2. **Tech stack and key dependencies**
3. **Annotated directory map**
   - Include every top-level file and directory
   - One line per entry
   - Each line must explain why that entry matters
4. **Setup**
   - Exact install, run, build, test, and lint commands
   - Only include commands that are supported by the repo
5. **Code conventions**
   - Naming patterns
   - File/module structure
   - Formatting/linting rules actually in use
6. **Agent rules**
   - What to always do
   - What to never do
   - How to proceed when requirements are ambiguous
7. **Git conventions**
   - Commit message format
   - Branch naming patterns
   - PR expectations
   - If these are not defined in-repo, say that explicitly
8. **Testing**
   - Test framework(s)
   - Test file locations
   - Coverage expectations
   - Fixtures, mocks, or test data locations
9. **Key files**
   - Entry points
   - Critical config files
   - Environment setup files
10. **Out of scope**
   - What an agent should escalate instead of attempting directly

Writing rules:
- Every line must be either actionable or orienting.
- Prefer bullets and short code blocks over prose.
- Do not add motivational text, introductions, conclusions, or filler.
- Do not guess.
- Do not generalize from ecosystem norms unless the repo confirms them.
- If the repo contains conflicting signals, include a `Conflict:` note rather than silently choosing one.
- If the repo is minimal, keep the file minimal.
- Accuracy is more important than completeness.

Output rules:
- Output only the final contents of `AGENTS.md`.
- Do not include analysis, commentary, or explanation outside the file content.
