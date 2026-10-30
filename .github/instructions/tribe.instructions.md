---
description: "Use when developing or reviewing a .NET and JavaScript application."
applyTo: "**"
---

# Shared Development Instructions

- Use C# and .NET for the backend and JavaScript for the frontend. Follow existing project conventions and reuse existing libraries.
- Follow test-driven development for features and bug fixes: write a failing test, run it to confirm the expected failure, implement the smallest change to pass, then refactor with tests green.
- Use the existing test frameworks. Run the relevant backend tests with `dotnet test` and frontend tests with the project's configured test script. Never claim tests passed unless you ran them.
- Ensure user documentation exists for user-facing changes. Create or update the README or relevant user guide with setup steps, usage, and changed behavior as appropriate.
- Keep changes small and focused. Do not introduce unrelated refactoring or new dependencies without a clear need.
- End implementation responses with a short `TDD / Tests / Docs` summary stating what was done and anything not verified. This is the visible demo signal that these instructions were followed.