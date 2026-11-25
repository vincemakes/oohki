# Contributing to Oohki

## How work happens

1. **Plan before building.** Every change, even a small one, starts with a short plan: what changes, why, how it is
   verified. Larger changes get a design document or an ADR (`docs/adrs/`) first.
2. **Red, then green.** A fix starts with a test that fails on the current code; a feature starts with the test that
   states what it must do. Report both runs in the pull request.
3. **One concern per pull request.** Keep the diff reviewable; say in the description what it deliberately does not do.
4. **Read every check.** A pull request merges only when every CI check is green, read row by row.
5. **Name reversals.** If a change overturns an earlier decision or ADR, say which one and why.

## Commit messages: English only

```
<type>(<scope>): <subject in English, imperative, lower-case start>

- body bullets in English, wrapped ~72 columns
- state WHAT changed and WHY; reference ADRs and findings by number
```

Types: `feat`, `fix`, `refactor` (state why behaviour is unchanged), `test`, `docs`, `chore`.

## Code

- TypeScript, Node 22+.
- Use kiso through its published packages and public APIs only; never copy kiso code or reach into its internals.
- Prose in the repository (code comments, docs, ADRs) is English.

## License

By contributing, you agree that your contributions are licensed under the Apache License 2.0 (section 5 of the license).
