# Changelogs for proxy-provider-converter
> Created and Maintained by @erbanku and fellow AI agents

## 10/02/2026

- Security: bump `next` to 16.3.8 (September 2026 security release); align `@next/bundle-analyzer` to 16.3.8

## 09/23/2026

- Security: bump `next` to 16.3.6 for GHSA-vcvr-r3jv-pc5j

## 09/14/2026

- Security: upgrade `next` from 14.2.35 to 16.3.5 for GHSA-2xp9-vwfh-vxw4 / CVE-2026-75604 (no patched 14.x release)
- Refresh dependencies via `bun update`; align `@next/bundle-analyzer` to 16.3.5
- Build: use `next build --webpack` for Preact alias config on Next.js 16
- Fix Heroicons v2 import paths in `pages/index.js`
