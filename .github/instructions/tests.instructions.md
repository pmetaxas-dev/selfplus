---
applyTo: "**/*_test.go"
---
# Test Authoring Rules

- Before adding audit tests, check docs/audit-questions.md.
- Put audit tests in audit-tests.go when requested.
- Use clear Arrange-Act-Assert structure.
- Cover edge cases and regression paths, not only happy paths.
- Keep tests independent and deterministic.
- Prefer table-driven tests where they improve readability.
