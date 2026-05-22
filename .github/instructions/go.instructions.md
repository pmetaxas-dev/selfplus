---
applyTo: "**/*.go"
---
# Go Implementation Rules

- Follow standard Go style and keep code gofmt-compatible.
- Prefer small, testable functions with descriptive names.
- Keep business logic deterministic and easy to unit test.
- Avoid hidden side effects in helper functions.
- If behavior is unclear, ask for clarification before implementing assumptions.
- Preserve existing architecture and public contracts unless explicitly asked to change them.
