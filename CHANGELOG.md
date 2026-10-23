# Changelog

## 1.0.1 - 2026-10-23

- Security: the app now builds and runs on Node.js 22.23.4, the fixed release of the Node.js security update of October 21, 2026. `nixpacks.toml` pins the Nix package set to nixos-26.05 (`da6dc0e`), which carries 22.23.4; `.nvmrc` reads 22.23.4.
- No migration and no setting changes.

## 1.0.0 — 2026-08-28

Initial public release.

- Three-destination timezone conversion with DST-aware math via the browser `Intl` API
- City-aware pickers preserving shared-timezone city identity (Barcelona / Madrid)
- Live local time for 10 world cities
- Searchable directories: 956 major cities and 195 national capitals
- Bilingual interface (English / Spanish)
- Shareable conversion URLs and local persistence
- Migrated from Vite to Next.js 16 (App Router, TypeScript strict, static export)
- Data regression suite, Playwright browser suite, and CI workflow
