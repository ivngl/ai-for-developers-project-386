# Changelog

## [0.1.0] — 2026-06-14

### Features
- scaffold project with React + Vite client and Express + Prisma server
- add event types, booking slots, admin auth, calendar UI, and TypeSpec spec
- replace raw CSS with Mantine v7 UI library
- add empty state UI when no event types exist

### Bug Fixes
- tests

### Tests
- add e2e tests covering 29 scenarios and empty state handling
- add e2e API tests for public booking, admin auth, and edge cases
- add e2e UI flow tests for booking and admin dashboard
- add concurrency race test for /api/bookings

### Documentation
- create TEST_PLAN.md with 29 mapped user scenarios (A1–A8, B1–B11, C1–C10)
- reference TEST_PLAN.md from AGENTS.md

### Chores
- add *.db to gitignore

[0.1.0]: https://github.com/anomalyco/ai-for-developers-project-386/releases/tag/v0.1.0
