# Contributing

Thanks for helping build this! Follow this workflow so we don't step on each other.

## Workflow

1. **Pick an issue** from the Issues tab or Project board, and comment "I'll take this." Don't start work on an issue someone else has claimed.
2. **Update your local `main`:**
   ```bash
   git checkout main
   git pull
   ```
3. **Create a branch** named `type/short-description`:
   ```bash
   git checkout -b feature/booking-form
   ```
   Types: `feature/`, `fix/`, `docs/`, `chore/`
4. **Commit small and often** with clear messages (present tense, say what changed):
   - Good: `Add slot selection to booking form`
   - Bad: `stuff`, `fix`, `update`
5. **Push and open a Pull Request** into `main`. In the description, say what you changed and link the issue (`Closes #12`).
6. **Get one approval** from a maintainer, then merge. Delete your branch after merging.

## Rules

- Never push directly to `main`.
- Never commit secrets (`.env`, API keys, passwords) or real student/teacher data. Use `.env.example` for variable names only.
- Keep pull requests small: one feature or fix per PR.
- Make sure `npm run lint` and `npm run build` pass before requesting review.
- Be kind in reviews. Critique the code, not the person.

## Getting Unstuck

- Merge conflicts or Git confusion: ask in the club chat before force-pushing anything.
- Not sure how to start: look for issues labeled `good first issue`.

## Labels

`good first issue` · `bug` · `feature` · `frontend` · `backend` · `design` · `docs`
