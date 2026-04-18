# A2A-SIN-Google-Chat — AGENTS.md

## Purpose

Google Chat integration agent for OpenSIN fleet communication.

## Rules

- ALWAYS use opencode CLI for LLM calls
- ALWAYS follow Google account matrix
- NEVER expose proprietary backend code
- ALWAYS log errors to GitLab LogCenter

## PARALLEL-EXPLORATION MANDATE (PRIORITY -4.5)

Bei grossen Codebases MUESSEN Agenten **5-10 parallele explore + 5-10 librarian-Agenten** starten.

## Subagenten-Modelle

| Subagent | Modell |
|:---|:---|
| **explore** | `nvidia-nim/stepfun-ai/step-3.5-flash` |
| **librarian** | `nvidia-nim/stepfun-ai/step-3.5-flash` |

## Agent Config System v5

→ [Full Documentation](https://github.com/OpenSIN-AI/OpenSIN-documentation/blob/main/docs/guide/agent-configuration.md)

## Boundary Guidance for Agents

When modifying this repo:

- Prefer Google Chat integration work.
- Keep claims scoped to this integration surface.
- Do not redefine broader workplace messaging, product, ops, or docs canon from here.
