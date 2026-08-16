# Client Engagements

CueHIRE™ engagements run on a written proposal or agreement that states
scope, capacity and terms. This page is the operating manual for everyone
working inside one.

## Communication channels

| Channel | Purpose |
| --- | --- |
| **WhatsApp (client group)** | Discussion with client representatives — onboarding, fast coordination and informal updates. Never credentials, never formal approvals — those belong on email. |
| **Slack (internal)** | A dedicated channel per engagement for the Cuesoft team: implementation planning, sprint coordination, technical discussion. |
| **Linear** | The system of record for the engagement's bugs, requests and sprint work. |
| **Jira Service Management** | Today's structured intake for client bug reports and support requests, triaged into Linear. Roadmap: a WhatsApp bot that files Linear issues directly — clients prefer WhatsApp to forms, and it automates intake end to end. |
| **Email group** | High-stakes communication. A dedicated group per engagement (the `cuehire-<client>@cuesoft.io` pattern) carries formal correspondence, approvals, access requests and sensitive matters — assigned personnel are added to it for continuity and stakeholder visibility. |
| **Meetings** | Monthly coordination reviews, sprint planning where the client's input is needed, incident reviews and escalations. |

## Support levels

| Category | What it means | Handling |
| --- | --- | --- |
| **Critical production outage** | Platform unavailable or a core flow broken for most users. | Initial response within 2 hours during covered periods; remediation efforts start within 4 where access and dependencies allow. |
| **High-priority defect** | A major workflow impaired but a workaround exists. | Triage within 1 business day; planned into the active or next sprint by severity. |
| **Routine bug / request** | Non-critical defect or support item. | Business hours, prioritised on the board. |
| **Feature request** | New or changed functionality. | Reviewed and planned into two-week sprints, best-effort. |
| **Maintenance window** | Planned deploys and infrastructure changes. | Low-traffic windows where practical, with notice for user-affecting changes. |

Response targets are handling commitments, not guaranteed completion —
completion depends on complexity, access, third-party dependencies and
sprint capacity, and the engagement document is the authority.

## The engineer's duties on a client project

- Ship inside the client's sprint cadence; flag risk the day you see it,
  not at review.
- Keep the client's data confidential and inside approved systems — the
  [confidentiality](../../policies/confidentiality/) and
  [data-protection](../../policies/data-protection/) policies apply with
  full force.
- Never make unauthorised production changes, credential rotations or DNS
  changes; anything touching production goes through the engagement lead.
- A **monthly work report** goes to the client: completed work, open
  issues, incidents, risks and next priorities. Your board hygiene is what
  makes that report writable.

## Escalation

Escalation ends at the founders' table: engagement lead → the division MD
(CueHIRE™) → the CEO. Clients are told this path at onboarding, and it is
honoured — no client should ever feel their problem has nowhere to go.
