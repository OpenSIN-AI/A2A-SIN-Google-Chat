# A2A-SIN-Google-Chat — AGENTS.md

## Purpose

Google Chat integration agent for OpenSIN fleet communication.

## Rules

- ALWAYS use opencode CLI for LLM calls
- ALWAYS follow Google account matrix
- NEVER expose proprietary backend code
- ALWAYS log errors to the approved artifact storage surface

## PARALLEL-EXPLORATION MANDATE (PRIORITY -4.5)

Bei grossen Codebases MUESSEN Agenten **5-10 parallele explore + 5-10 librarian-Agenten** starten.

## Subagenten-Modelle

| Subagent | Modell |
|:---|:---|
| **explore** | `nvidia-nim/stepfun-ai/step-3.5-flash` |
| **librarian** | `nvidia-nim/stepfun-ai/step-3.5-flash` |

## Agent Config System v5

→ [Full Documentation](https://github.com/OpenSIN-AI/OpenSIN-documentation/blob/main/docs/guide/agent-configuration.md)

## Boundary Guidance

When modifying this repo:

- Prefer Google Chat messaging integration and workspace communication work.
- Do not turn this repo into a generic Google platform bucket.
- Do not redefine organization docs, architecture, or runtime canon here.
- Move non-Google-Chat behavior back to the repos that own those surfaces.
