# ourKairos

Minimal workspace bootstrap for the monorepo.

## Local setup

1. Install Node.js 18 or newer.
2. Install pnpm 10 or newer.
3. Run `pnpm install`.
4. Run `pnpm check:workspace`.

## Workspace scripts

- `pnpm check:workspace` validates root workspace files and package manifests.
- `pnpm build` runs the workspace validation baseline.
- `pnpm lint` runs the workspace validation baseline.
- `pnpm typecheck` runs the workspace validation baseline.
- `pnpm test` runs the workspace validation baseline.

The validation script is intentionally non-blocking for an empty workspace so new apps and packages can be added incrementally without breaking `main`.

