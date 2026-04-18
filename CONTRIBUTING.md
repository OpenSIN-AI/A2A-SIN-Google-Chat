# Contributing to A2A-SIN-Google-Chat

## Scope first

Before changing code or docs, verify the change genuinely belongs to the **Google Chat** surface.

Put the change here when it affects:
- Google Chat messaging routing, coordination, or automation workflows
- Google Chat evidence, recovery, auth, or session-health handling
- Google Chat contracts tied to workspace communication

Do **not** put the change here when it belongs to:
- unrelated Google platform logic outside Chat integration
- organization SSOT docs or architecture ownership
- unrelated OpenSIN services

## Workflow

1. Branch from the latest `main`.
2. Make the smallest repo-scoped change possible.
3. Run validation command(s) relevant to the touched surface.
4. Include exact validation commands and evidence in the PR.

## Boundary checklist

- Does this change stay within Google Chat ownership?
- Does another repo already own the adjacent platform behavior?
- Does this PR avoid redefining shared docs, runtime, or platform canon?

## Boundary Rules

Before adding a feature or top-level claim, answer:

1. Is this specifically Google Chat integration work?
2. Does another OpenSIN repo already own the canonical source of truth?

### Put it in `A2A-SIN-Google-Chat` if:
- it improves Google Chat integration
- it improves this repo's A2A agent behavior

### Do NOT put it in `A2A-SIN-Google-Chat` if:
- it claims broader workplace messaging, product, ops, or docs ownership

## License

By contributing, you agree that your contributions will be licensed under the Apache License 2.0.
