# AGENTS.md

Optimize for maintainability, not diff size.

Reduce, in order:
1. State
2. Coupling
3. Complexity
4. Diff size

Prefer simple, local, stateless, verifiable changes.
Follow existing patterns only when they support these priorities.
Prefer duplication over abstraction when it lowers complexity.
Deduplicate only when it does not increase state, coupling, or complexity.

Do not add abstractions, dependencies, configuration, fallback behavior, or architectural changes unless explicitly asked or required.

Choose tests that prove the change with minimal setup.
Present options before editing when a significant design trade-off is required.
