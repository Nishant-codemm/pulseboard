# PulseBoard

> Team check-ins that turn daily updates into clear signals for managers and leadership.

## What It Does

PulseBoard reimagines how Central Operations teams share updates, surface risks, and make decisions. Instead of chasing updates across channels, teams use a single daily check-in — and the board turns their words into structured signals.

### Key Workflows

| View | Purpose |
|---|---|
| **Employee Workspace** | Personal dashboard with summaries, blockers, and suggested next actions |
| **Daily Stand-up** | Structured check-in form (what moved, what's next, what's blocking) |
| **Team Pulse** | Manager view with live updates, participation metrics, and triaged attention items |
| **Executive Brief** | Leadership summary with recommended decisions |
| **Analytics** | Adoption tracking, signal quality metrics, and trend visualization |

## Tech Stack

- **React 19** + **TypeScript**
- **Vite** (build tooling)
- **Tailwind CSS v4** (utility layer)
- **Lucide React** (icon system)
- **DM Sans + Space Grotesk** (typography)

## Running Locally

```bash
npm install
npm run dev
```

## Project Constraints & Demo Notice

This is a **Frontend UI Prototype** built to demonstrate workflow design and product judgment.

- **Frontend-only:** Authentication, backend, databases, and APIs are intentionally not implemented.
- **Mocked Data:** All dashboard values, user names, charts, notifications, and statistics are sample demo data only.
- **Static Workflows:** The application focuses on UI/UX; actions like submitting forms or viewing analytics use static state and do not persist data.
## Architecture

The entire UI lives in a single `App.tsx` with co-located components and CSS. Deliberate choice for a timed prototype — fast iteration over premature abstraction.

## Author

Built by **Nisha**.
