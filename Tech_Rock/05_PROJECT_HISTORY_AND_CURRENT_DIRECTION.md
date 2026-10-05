# Tech Rock — Project History and Current Direction

## Tech Rock OS / Live Tracker

A prior implementation explored Google Sheets, Apps Script and Netlify.

Requested capabilities included:
- all relevant members able to update work;
- task creation and removal;
- personal boards;
- status, deadlines and priorities;
- mark complete;
- team progress;
- workstreams;
- responsive layout;
- faster synchronisation;
- test connection.

Reported problems included 12–30 second synchronisation delays, task-removal failures, a missing core.js deployment issue and contributor/deployment constraints.

These are historical reports. Do not claim they remain unresolved or have been fixed without inspecting the current application.

The interface direction evolved from structured/brutalist toward a more maximalist technology-inspired treatment. Use the latest project-specific brief before implementing visual changes.

## Church-wide operations direction

The later requirement expanded beyond a Tech Rock team tracker toward administration for the whole church. The broader system should support church-wide projects, actions, updates, status and responsibility rather than treating every task as a Tech Rock task.

This broader operations platform is a separate architectural direction from the original Tech Rock OS implementation.

## T-shirt catalogue

A separate Rock City web project required:
- catalogue ordering;
- multiple items and sizes per person/order;
- customer name and size capture;
- Google Sheets as the recorded data destination;
- optional payment gateway;
- pay-on-collection fallback;
- Netlify deployment direction;
- Apps Script endpoint;
- QR access.

Reported sheet-write and connection issues mean the project must be verified before being described as live.

## Planning Center rollout

Planning Center remains one of Tech Rock's central enablement responsibilities. The detailed rollout architecture lives in ../01_PLANNING_CENTER.md.

Do not move every ministry into Services. The recorded model keeps Worship in Services while other ministries primarily use Groups with RSVP, with Calendar, Registrations and Check-Ins serving their distinct purposes.

## Current-state rule

Project history is evidence of requirements and previous implementation attempts, not proof of today's production state. Inspect the live repository, deployment or connected system before making current-state claims.
