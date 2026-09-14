# AGENTS.md

## Project

Proxy Provider Converter — Next.js Pages Router app that converts Clash subscriptions to Proxy Provider / Surge External Group formats.

## Stack

| Component | Version |
|:---------:|:--------|
| Runtime | Bun 1.4.2 |
| Framework | Next.js 16.3.5 (Pages Router) |
| UI | React 19, Tailwind CSS 3, Preact (production client alias) |
| Lockfile | `bun.lock` only |

## Commands

```bash
bun install
bun run dev      # next dev --webpack
bun run build    # next build --webpack
bun run start
```

## Notes

- Next.js 16 defaults to Turbopack; this project uses `--webpack` because `next.config.js` aliases React to Preact in production client builds.
- No `eslint-config-next` in this repo.
- Security baseline: `next` must stay at or above 16.3.3 (GHSA-2xp9-vwfh-vxw4, CVE-2026-75604). There is no patched release on the 14.x line.

Last updated: 2026-09-14
