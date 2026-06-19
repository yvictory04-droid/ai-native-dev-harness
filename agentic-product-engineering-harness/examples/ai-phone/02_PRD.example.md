# 02_PRD — AI Phone Example

## Problem Statement

Operators spend too much time handling repetitive phone workflows. The system should automate routine calls while preserving human handoff for uncertain or risky scenarios.

## Goals

- Handle common inbound call intents
- Monitor live call status
- Provide call details and transcript
- Escalate exceptions to humans
- Keep an auditable record of actions

## Non-Goals

- Fully replacing human operators in all scenarios
- Handling unsupported or high-risk requests without escalation
- Making irreversible changes without confirmation

## Core Workflow

1. Caller enters call.
2. AI greets and identifies intent.
3. AI verifies identity when needed.
4. AI completes supported workflow.
5. AI sends or records confirmation.
6. AI escalates if confidence is low or scenario is unsupported.
7. System stores transcript, summary, actions, and audit trail.

## Acceptance Criteria

- Operator can see live calls.
- Operator can open call detail.
- System records transcript and summary.
- Exception queue shows unresolved calls.
- Human handoff path is available.
- All major actions are auditable.
