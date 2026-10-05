# Tech Rock

Tech Rock is Rock City Church's digital infrastructure, IT and systems function. It enables the wider church through systems, documentation, governance, testing, support, training and improvement.

**Media is included. Lighting sits under Media. Sound is excluded from Tech Rock's organisational scope.**

## Read this section in order

1. [Scope and responsibilities](01_SCOPE_AND_RESPONSIBILITIES.md)
2. [System architecture](02_SYSTEM_ARCHITECTURE.md)
3. [Operating model and governance](03_OPERATING_MODEL_AND_GOVERNANCE.md)
4. [Repository and technical standards](04_REPOSITORY_AND_TECHNICAL_STANDARDS.md)
5. [Project history and current direction](05_PROJECT_HISTORY_AND_CURRENT_DIRECTION.md)

For detailed Planning Center decisions, also read [Planning Center and Church Center](../01_PLANNING_CENTER.md).

## Core operating principle

Tech Rock builds and supports infrastructure for the whole church. It should not become a collection of disconnected technical experiments or duplicate systems of record.

Use the existing church platforms for the responsibilities they serve well. Build custom tools where there is a genuine workflow gap, with a defined data source, ownership, documentation, security model and support path.

## Responsibility pattern

**Coordinate → Delegate → Follow up → Test → Confirm completion**

A task is not complete merely because it was assigned, coded or uploaded. Confirm the intended outcome in the relevant environment where practical.

## System boundaries

- **Planning Center** — ministry system of record where adopted.
- **Church Center** — normal member-facing layer.
- **Operations/project workspace** — projects, actions, requests, meetings, decisions and dashboards where adopted.
- **Google Drive** — working documents and assets.
- **GitHub** — code, versioned technical documentation and portable context.
- **Custom web tools** — narrow workflows that genuinely need a purpose-built application.

Do not claim integrations, deployments or fixes are live unless they have actually been inspected or tested.

## Historical implementation note

The earlier Tech Rock OS / Live Tracker explored Google Sheets, Apps Script and Netlify and had reported sync, removal and deployment issues. Those details are preserved in the project-history page. They are not the definition of Tech Rock and should not constrain future architecture without current verification.

## Context authority

Current explicit instructions override older project history. Stable scope and governance belong in this folder; temporary implementation details and dated project state should remain clearly labelled as such.
