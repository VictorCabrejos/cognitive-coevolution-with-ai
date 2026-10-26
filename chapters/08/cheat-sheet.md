# Chapter 8 cheat sheet

*From helpful answers to dependable systems*

[Chapter guide](README.md) · [Cheat sheet](cheat-sheet.md) · [Practice](practice.md) · [Self-check](self-check.md) · [Answers](answers.md)

## Key distinctions

**Harness Engineering.** Design instructions, source rules, permissions, tests and recovery around the helper. Written rules and effective access controls provide different protections.

**Agent Runtime Systems.** The practical environment supplies tools, permissions, context, saved state and interruption behavior. Inspect how the controls actually operate there.

**Behavioral Invariant and Behavioral Drift.** An invariant states an observable condition, such as source comments not authorizing distribution. Drift occurs when conduct departs from the expected boundary.

**Idempotency and uncertain completion.** Repeating an operation should have the same intended effect as performing it once. Inspect existing state before retrying; a single successful repeat test does not establish behavior in all conditions.

## Everyday example

A fictional assistant can prepare a report but cannot email it under the task's permissions. A sentence inside a source document requesting email is information to inspect, not authority to expand the assignment.

## Keep this question in view

Did I distinguish a count from an unsupported percentage?
