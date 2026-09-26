# Trigenys

**Designing the systems behind decisions.**

Trigenys builds focused software products, automation systems and developer tools that turn operational friction into dependable workflows.

We care about software that is useful in the real world: clear problems, measurable outcomes, pragmatic architecture and automation where it actually saves time.

## Products

- [**Release Video Engine**](https://github.com/Trigenys/release-video-engine) — turns software releases into branded short-form product videos with Remotion.
- [**Product Identity**](https://github.com/Trigenys/product-identity) — product serialization, authenticity verification and warranty registration for physical-product brands.
- [**Sims Mod Health**](https://github.com/Trigenys/sims-mod-health) — offline-first desktop tooling for auditing and maintaining The Sims 4 mods and custom content.
- [**AppFactory OpenPage Engine**](https://github.com/Trigenys/appfactory-openpage-engine) — JSON-first website generation with reusable layouts, visual editing and AI-assisted workflows.

## What we work on

**Product engineering** — full-stack applications, internal tools and workflow-heavy business software.

**Automation** — systems that eliminate repetitive operational work without hiding the engineering underneath.

**Developer tooling** — CI/CD, project automation, release workflows and software-delivery infrastructure.

**Applied media & AI** — deterministic content generation, AI-assisted workflows and productized automation.

## Engineering principles

- Start with the problem, not the stack.
- Automate repeatable work, not judgment.
- Prefer explicit quality gates over fragile magic.
- Keep systems observable, maintainable and economically sensible.
- Ship narrow, prove value, then expand.

## RAIDER engineering standard

Trigenys uses **RAIDER** as a cross-project engineering standard for shared components, automations, platform tooling and structural changes:

- **R — Reusable:** capabilities should be reusable without copy-paste or consumer-specific forks.
- **A — Agnostic:** behavior should not depend implicitly on a repository, owner, branch, stack, OS or provider when that context can be discovered or configured.
- **I — Idempotent:** repeated runs converge to the same desired state without duplicates or unnecessary writes.
- **D — Durable / Non-regressive:** new capabilities preserve supported behavior and contracts; significant failures feed a documented failure-memory loop.
- **E — Engineering-grade:** architecture, security, tests, observability and documentation must be production-minded, with a reuse-first **Adopt · Adapt · Learn · Build** approach.
- **R — Retroactive:** existing projects are first-class consumers; new capabilities must support brownfield adoption without destructive resets.

RAIDER is used as a design, review and Definition-of-Done framework—not just as documentation.

## Core stack

TypeScript · React · Python · FastAPI · Node.js · PostgreSQL · Docker · GitHub Actions · AWS · Cloudflare

---

**Trigenys Group**  
*Building systems that are useful before they are impressive.*
