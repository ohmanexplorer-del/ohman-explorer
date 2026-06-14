# database-drivers

Curated projects in this category.

Note: young repositories can show strong potential but still carry higher stability and maintenance risk.

### 1. modernc-org/sqlite

- Link: https://github.com/modernc-org/sqlite
- Title: modernc-org/sqlite
- Description: Read-only mirror of https://gitlab.com/cznic/sqlite
- Category: database-drivers
- Type: library
- Language: Go
- Created: 2025-12-01
- Age: 6 months
- Last pushed: 2026-06-14
- Assessment context: established enough for stronger comparison, but maintenance trend still matters
- Score: 9.0/10
- Novelty: 8.0/10
- Maturity: 9.0/10
- Small repo potential: 10.0/10
- Stars: 63
- Reason: An essential, production-ready Cgo-free SQLite driver for Go that enables seamless cross-compilation without a C toolchain.
- Strengths:
  - Eliminates the need for Cgo, simplifying Go builds and cross-compilation
  - Fully-featured SQLite translation via automated C-to-Go transpilation
  - Highly trusted and widely adopted in the Go ecosystem
- Weaknesses:
  - Slightly lower performance compared to native Cgo SQLite bindings
  - Transpiled codebase is difficult to read or debug manually

