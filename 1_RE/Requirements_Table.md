# Requirements Engineering

## Project Title
Incident Escalation & On-Call Rotation Engine

## Requirements

The system organizes team shift rotations, routes monitoring alerts through multi-tiered phone/SMS escalation ladders, and tracks incident post-mortems.

## Functional Requirements

- FR-001: The system shall ingest incident alerts and create an incident record.
- FR-002: The system shall identify the active on-call engineer from the rotation schedule.
- FR-003: The system shall escalate an incident to the secondary engineer if the primary does not acknowledge within 5 minutes.
- FR-004: The system shall send notifications through configured channels including SMS and phone-based escalation.
- FR-005: The system shall record and track post-mortem information for resolved incidents.

## Non-Functional Requirements

- NFR-001: Alert dispatch through webhook, SMS and email shall initiate within 3 seconds of alert ingestion.
- NFR-002: The system shall allow incident and on-call information to be accessed only by authorized users and services.
