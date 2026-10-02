# Senior Full-Stack Engineer — Interactive Workday Simulator

An interactive, visual simulation of a realistic day in the life of a **Senior Full-Stack Engineer**.

The project follows one feature from product requirements to production instead of teaching frontend, backend, databases, testing, reviews, performance, and incidents as disconnected topics.

## What it covers

- Product discovery and requirement clarification
- System design and request/data flow
- React / Next.js frontend state modelling
- Node.js / TypeScript API and service design
- Authorization and idempotency
- Queues, workers, async jobs, and object storage
- PostgreSQL schema design, indexes, and query plans
- Unit, integration, and E2E testing
- Pull requests and senior-level code review
- CI, feature flags, and progressive rollout
- Performance investigation
- Production debugging and OOM incidents
- Mitigation, root-cause analysis, hotfixes, and recovery
- Senior engineering judgment and ownership

## Interactive experience

The simulator includes:
- a full workday timeline
- Simple View and Deep Dive explanations
- an interactive invoice-export state machine
- clickable Idle / Submitting / Processing / Ready / Failed states
- a working Start Export demo with progress, cancel, reset, and file download
- architecture, frontend, backend, database, testing, performance, and production visuals
- incident-response decisions and engineering quizzes

## Tech

- HTML
- CSS
- Vanilla JavaScript
- No build step
- No runtime dependencies

## Run locally

Open `index.html` directly in your browser, or run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages

This repository includes a GitHub Pages deployment workflow in:

```text
.github/workflows/pages.yml
```

Enable **Settings → Pages → Build and deployment → Source: GitHub Actions** once. Pushes to `main` will deploy automatically.

## Why this exists

Real senior engineering work is about connecting product decisions, architecture, implementation, data, review, delivery, observability, and incident response.

This project makes that complete flow visual and interactive.

## License

Educational project. Feel free to learn from it, share it, and adapt it with attribution.
