# Turborepo `pre-commit` bug

Using Turborepo 2.0 with `pre-commit` causes an internal error in Turborepo.

## Reproduction

Install `pre-commit`: `pip install pre-commit`

Install deps: `pnpm i`

Run `pre-commit`: `pre-commit run --all-files`
