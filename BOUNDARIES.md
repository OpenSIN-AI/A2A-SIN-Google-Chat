# A2A-SIN-Google-Chat Boundaries

## Role
`A2A-SIN-Google-Chat` owns Google Chat messaging integration, workspace communication, and Google Chat-specific contracts.

## This repo should own
- Google Chat messaging routing, coordination, and automation flows
- Google Chat evidence, recovery, auth, and session-health handling
- Google Chat contracts used by downstream automation agents
- runbooks tied to workspace communication and chat automation

## This repo must not own
- unrelated Google platform logic outside Chat integration
- organization SSOT docs or architecture canon
- downstream business logic unrelated to Google Chat ownership

## Hard rules
- Keep changes scoped to Google Chat messaging integration and automation.
- Move non-Google-Chat behavior back to the repos that own it.
- Keep reusable contracts focused on workspace chat coordination and messaging.
