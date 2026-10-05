# Tech Rock — System Architecture

## Operating model

The recorded and proposed church digital architecture separates tools by responsibility rather than forcing one platform to do everything.

| Layer | Intended role |
| --- | --- |
| Planning Center | Ministry system of record: people, groups, service planning, calendar, registrations and check-ins |
| Church Center | Member-facing layer for home content, groups, signups and personal interaction |
| Project / operations workspace | Projects, actions, requests, meetings, decisions and dashboards where adopted |
| Google Drive | Working documents, shared files and media assets |
| GitHub | Code, versioned technical documentation and portable context |
| Purpose-built web tools | Narrow workflows that are not adequately served by the systems above |

This is an architectural direction. Do not claim integrations exist unless they have been implemented and tested.

## Planning Center boundary

Planning Center distinctions matter:
- **People** — people, households and authorised data workflows.
- **Groups** — ministry/group membership, leaders, events, RSVP and resources.
- **Services** — actual service planning and rostering; Worship is the principal rollout use.
- **Calendar** — church-wide event and resource visibility.
- **Registrations / Forms** — signups and intake.
- **Check-Ins** — Kids Rock attendance and safeguarding workflows.
- **Publishing / Church Center** — member-facing access.

Do not bypass an established Planning Center function with a custom build merely for convenience without understanding the governance and safeguarding consequences.

## Church Center principle

Church Center is the normal member-facing layer. Most church members should not need Planning Center backend access merely to participate.

Recorded navigation:
**Home · Groups · Signups · Me**

Recorded home tiles:
**Info Hub · Sermons · Devotionals · About Us**

## Custom applications

Use a custom web application when there is a genuine workflow gap. Define the system of record before building. Avoid creating parallel databases that silently compete with Planning Center, Drive or the adopted operations workspace.

Custom applications should have:
- a clear owner and purpose;
- a defined data source;
- explicit write/read behaviour;
- responsive access;
- error states that are visible to users;
- a connection/health test where integration failure is possible;
- documentation for deployment and recovery.
