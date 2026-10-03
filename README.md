# Akın Öztorun

**Senior Product Engineer · TypeScript · React · Next.js · Vue 3 · API-first · Reliability**

I own product surfaces end to end — from instrumentation to infrastructure. Frontend is one layer, not the whole identity.

Seven years shipping production software across HR SaaS, e-commerce, legal tech, and dev tools. Most recently the sole frontend on a Vue 3 / Nuxt community platform. Based in Antalya, Turkey; EU-aligned hours.

---

## Track record

- **39% → 65% funnel completion** at Proxify (~400K applications / year). Instrumented the flow in Mixpanel, identified drop-off points, shipped targeted UX fixes, validated with A/B comparisons. *Proxify Quality Award 2024.*
- **Lighthouse 40s → 90s** on client dashboards at Skeyl — no rewrite. Audited render-blocking resources, optimised bundle splitting, eliminated layout shifts.
- **Webpack → Vite migration** with self-hosted Lighthouse CI as a build-diff signal so silent performance regressions stop at PR review, not in production.

---

## Selected work

**[Sorrel — conversion engineering funnel](https://github.com/akin-oz/sorrel)** · [live](https://sorrel.akinoztorun.dev) · [insights](https://sorrel.akinoztorun.dev/insights)
A deployed 8-step cat-food subscription wizard built as a conversion engineering artifact. Typed funnel events where a wrong event name is a compile error. Live flag-gated A/B test wired from PostHog through Stripe checkout, with an `/insights` page that reads the live funnel back in-app. The same discipline moved a real ATS funnel from 39% → 65% across 400K applications a year — Sorrel makes the method inspectable, not just asserted.
`Next.js 16 · React 19 · GraphQL · PostHog · Stripe · Storybook · TypeScript · yarn-workspaces`

**[Nord Signup — design system integration](https://github.com/akin-oz/nord-signup)** · [live](https://nord-signup.akinoztorun.dev)
Signup form implemented against the Nord Design System spec with 12 Architecture Decision Records, selective component imports that cut the JS bundle 49% (497 KB → 251 KB), and a three-tier test suite (Vitest unit + integration, Playwright + axe-core e2e). Documents three AI suggestions that were rejected — an audit trail that shows judgment, not just execution.
`Nuxt 4 · Vue · TypeScript · Pinia · Playwright · Vitest`

**[Engineering decisions](https://github.com/akin-oz/engineering-decisions)**
14 Architecture Decision Records from production — a 400K-application ATS, a German legal-tech platform, agentic tooling. Each one is a real decision under real constraints: incomplete specs, solo ownership, federated teams, production pressure. Start with the reversals (ADR-010): that's where the signal is.

**[PropertyOS — debugging investigation](https://github.com/akin-oz/propertyos-debug-investigation)**
Multi-tenant rental ops platform handed over with a vague complaint: *"two clients say the numbers are wrong, and one is seeing data that isn't theirs."* Traced **14 production-class failures** — cross-tenant cache poisoning, `float()` on money totals, fail-open auth silently exposing a real client's dashboard, PII in telemetry. Fixed each with a postmortem and a regression test. Two CI gates now block the whole class from shipping. Catching one bug is luck; preventing a class is engineering.
`Python · FastAPI · React · Redis · PostgreSQL`

**[energy-portfolio-slice](https://github.com/akin-oz/energy-portfolio-slice)**
A vertical slice showing how I approach Staff-level product engineering from a frontend seat: domain modelling, GraphQL as the contract, a React client wired to the real API, and a structure ready for auth, logging, events, and multi-tenant growth.
`GraphQL · React · TypeScript`

---

## What I do

- **Product engineering** — TypeScript, React, Next.js, Vue 3 / Nuxt, GraphQL, Feature-Sliced Design. Contracts-first: align the API and data shape before the UI exists.
- **Quality in the pipeline** — CI/CD gates, Playwright e2e, Lighthouse CI as a build-diff signal, SonarQube, Sentry, Mixpanel. Structured observability, not just error logging.
- **Agentic engineering** — Claude Code as infrastructure, not a shortcut. Specs approved before implementation begins; hooks enforce what the rules request; every correction becomes a permanent guardrail visible in git history.

---

## How I work

- Start from the problem and domain, not from components.
- Design API and data contracts early, with backend in the room.
- Keep the frontend lean, typed, and predictable, backed by tests.
- Treat internal teams as customers — docs, DX, and guardrails matter.
- Own the lifecycle: idea → implementation → rollout → monitoring → iteration.

---

## Writing

I publish **[Ownership in Practice](https://ownershipinpractice.substack.com/)** — a Substack on contracts, vertical slices, and the small habits that make teams calmer and faster. Real tickets, not theory.

---

## Looking for

Senior / Staff-track product engineer roles where engineers own a slice end to end, API-first and product-led culture is real, and reliability and UX both matter.

I'm most effective in teams that already have domain depth but need someone to own the frontend layer end to end — contracts, observability, rollout, and the feedback loop. If that sounds like your environment: [LinkedIn](https://www.linkedin.com/in/oztorun/), [akinoztorun.dev](https://akinoztorun.dev), or open a discussion here.
