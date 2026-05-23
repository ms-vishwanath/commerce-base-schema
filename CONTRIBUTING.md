# Contributing

Thanks for your interest in contributing to Commerce Base Schema!

## How to Contribute

1. **Fork** the repository.
2. **Create a branch** for your change:
   ```
   git checkout -b my-feature
   ```
3. **Make your changes** to `dev-schema.dbml` and/or `dev-schema.dbdiagram`.
4. **Commit** with a clear message describing what you changed and why.
5. **Push** to your fork and open a **Pull Request**.

## Guidelines

- Keep changes focused on e-commerce schema concerns.
- If you add a new table or column, include an inline `[ref:]` foreign key rather than a standalone `Ref:` block.
- Use enums for status-type columns instead of raw strings.
- Maintain consistency with existing naming conventions (snake_case for fields, PascalCase for tables).
- Update `dev-schema.dbdiagram` positions if your changes affect table layout.

## Reporting Issues

Open an issue describing the problem, the expected behavior, and any relevant context.
