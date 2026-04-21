# Akın Oztorun

**Senior Product Engineer · TypeScript · React · Next.js · Vue 3 · API-first · Reliability**

I own product surfaces end to end — from instrumentation to infrastructure. Frontend is one layer, not the whole identity.

Nine years shipping production software across HR SaaS, e-commerce, legal tech, and dev tools. Currently the sole frontend on a Vue 3 / Nuxt community platform. Based in Antalya, Turkey; EU-aligned hours.

---

## What I do

- **Product engineering with frontend at the centre**
  - TypeScript · React · Next.js · Vue 3 / Nuxt · GraphQL · Feature-Sliced Design
  - Contracts-first: align the API and data shape with how clients actually use the data, before the UI exists.
  - Shared component systems, design-token pipelines, Storybook.
- **Quality in the pipeline**
  - CI/CD gates, Lighthouse CI as a build-diff signal, SonarQube, Playwright e2e.
  - Structured observability: Sentry with noise classification, Mixpanel with strict allowlist sanitisation, web vitals dashboards.
  - OpenAPI-first with MSW-backed dev, Chromatic visual regression.
- **Agentic engineering**
  - Claude Code as infrastructure, not a shortcut. `CLAUDE.md` encodes stop rules and behaviours; hooks enforce them.
  - Route by task complexity — Haiku for exploration, Sonnet for implementation, Opus for planning.
  - Self-improving loop: every correction becomes a permanent guardrail, visible in git history.

---

## Selected work

**[Base360 — multi-tenant dashboard investigation](https://github.com/akin-oz/Base360)**
Treated a public multi-tenant revenue dashboard as a real investigation. Found **14 bugs** across cross-tenant data exposure, float-precision errors in money handling, and a timezone regression hiding behind dead code. Fixed every one, wrote a postmortem for each, added **89 regression tests**, and architectural hardening that makes the whole class of failure impossible to ship silently.
`Python · FastAPI · React · Redis · PostgreSQL · multi-tenancy`

**[energy-portfolio-slice](https://github.com/akin-oz/energy-portfolio-slice)**
A vertical slice showing how I approach Staff-level product engineering from a frontend seat:
- Domain modelling — `Customer → Project → EnergyAsset`.
- **GraphQL** as the contract — pagination, filters, typed errors.
- **React** client wired to the real API, not mocks.
- Structure ready for auth, logging, events, and multi-tenant growth.

`GraphQL · React · TypeScript`

**[next-swr-quality-demo](https://github.com/akin-oz/next-swr-quality-demo)** — [live](https://next-swr-quality-demo.vercel.app/)
Focused demo on **safe, observable data fetching** in Next.js. SWR for caching and revalidation, explicit loading / fallback / failure UX, and patterns for API boundaries, typing, and testability.
`Next.js · SWR · TypeScript`

---

## Track record

- **ATS funnel, 39% → 65% completion** at Proxify (~400K applications / year). Instrumented the flow in Mixpanel, identified drop-off points, shipped targeted UX fixes, validated with A/B comparisons. *Proxify Quality Award 2024.*
- **Lighthouse 40s → 90s** on client dashboards at Skeyl — no rewrite. Audited render-blocking resources, optimised bundle splitting, eliminated layout shifts.
- **Webpack → Vite migration** with self-hosted Lighthouse CI as a build-diff signal so silent performance regressions stop at PR review, not in production.

---

## How I work

- Start from the **problem and domain**, not from components.
- Design **API and data contracts** early, with backend in the room.
- Keep the frontend **lean, typed, and predictable**, backed by tests.
- Treat internal teams as **customers** — docs, DX, and guardrails matter.
- Own the lifecycle: idea → implementation → rollout → monitoring → iteration.

---

## Writing

I publish **[Ownership in Practice](https://ownershipinpractice.substack.com/)** — a Substack on contracts, vertical slices, and the small habits that make teams calmer and faster. Real tickets, not theory.

---

## Currently focused on

Senior / Staff-track product engineer roles where:

- Engineers own a slice end to end.
- API-first, cloud-native, product-led culture is real.
- Reliability and UX both matter.

If that sounds like your environment and you'd like to talk — [LinkedIn](https://www.linkedin.com/in/oztorun/), [akinoztorun.dev](https://akinoztorun.dev), or open a discussion here.
