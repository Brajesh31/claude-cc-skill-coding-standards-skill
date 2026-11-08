# claude-cc-skill-coding-standards-skill

A Claude Code skill for applying consistent coding standards across TypeScript, JavaScript, React, and Node.js projects.

## Overview

This skill promotes readable, maintainable, and predictable code. It focuses on clarity, simplicity, reuse, consistency, and avoiding unnecessary complexity.

The standards should complement the target project's established conventions rather than override them without reason.

## Core Principles

### Readability First

- Use clear names for variables, functions, and types.
- Keep functions focused.
- Prefer code that explains itself.
- Add comments for non-obvious decisions, not obvious syntax.

### Keep It Simple

- Choose the simplest implementation that satisfies the requirement.
- Avoid premature optimization.
- Do not introduce abstractions without a clear benefit.
- Prefer explicit behavior over clever shortcuts.

### Reduce Meaningful Duplication

- Extract shared logic when it has a stable responsibility.
- Avoid generic utilities that obscure simple operations.
- Keep abstractions close to the use cases they support.

### Consistency

- Follow project formatting and lint rules.
- Use predictable file and naming conventions.
- Keep error handling and data structures consistent.
- Align tests with the project's existing patterns.

## Language and Framework Areas

The skill applies to:

- JavaScript.
- TypeScript.
- React.
- Node.js.
- Common frontend and backend project structures.

## Installation

```bash
git clone https://github.com/Brajesh31/claude-cc-skill-coding-standards-skill.git ~/.claude/skills/cc-skill-coding-standards
```

## Usage

Invoke the skill during implementation, refactoring, or code review:

```text
/cc-skill-coding-standards
```

Provide the project language, framework, existing lint and formatting rules, and the scope of the change.

## Recommended Workflow

1. Inspect project instructions and existing conventions.
2. Understand the expected behavior.
3. Choose a simple implementation.
4. Use clear types and names.
5. Keep functions and components focused.
6. Handle errors explicitly.
7. Add tests for meaningful behavior.
8. Run linting, formatting, and type checks.
9. Review the diff for unnecessary changes.
10. Document important non-obvious decisions.

## Code Review Checklist

- Names communicate intent.
- Types reflect real data contracts.
- Functions have focused responsibilities.
- State is not duplicated unnecessarily.
- Error cases are handled.
- Dependencies are justified.
- Tests cover important behavior.
- Formatting is consistent.
- No secrets or debug artifacts are committed.
- Changes follow project conventions.

## Repository Contents

- `SKILL.md`: Main coding standards instructions.
- `README.md`: Principles, workflow, and review checklist.

## Practical Principle

Consistency is valuable, but blindly applying generic rules can make a codebase worse. Follow the project's context and optimize for clarity, correctness, and maintainability.
