# Changelogs for proxy-provider-converter
> Created and Maintained by @erbanku and fellow AI agents

## 09/14/2026

- Security: upgrade `next` from 14.2.35 to 16.3.5 for GHSA-2xp9-vwfh-vxw4 / CVE-2026-75604 (no patched 14.x release)
- Refresh dependencies via `bun update`; align `@next/bundle-analyzer` to 16.3.5
- Build: use `next build --webpack` for Preact alias config on Next.js 16
- Fix Heroicons v2 import paths in `pages/index.js`
