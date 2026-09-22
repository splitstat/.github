# SplitStat

**A/B and split URL testing that calls a winner only once the numbers hold.**

Most testing tools show you a lead on day two. A lead on day two is usually noise.
SplitStat holds the verdict until four things are true at once: the result has
cleared significance, it has enough visitors, it has enough conversions, and it has
run a full week. The screen names the one that is still missing.

## What it does

- **Visual and split URL tests.** Change copy, layout or a whole page in the editor, or point a test at a second address.
- **Server-side tests and feature flags.** One assignment service, so an experiment and a rollout cannot disagree about who sees what.
- **Three stats engines.** Bayesian, frequentist read once, and frequentist with a halfway reading that can end a clear test early. Every report names the engine that produced it, and each number carries the label that method actually earns.
- **Guardrails.** Metrics that are not the goal, but must not get worse.
- **Audiences and filters.** Who enters a test, and which events count toward it.
- **No visitor IP addresses, ever.** Raw events are deleted after 90 days.

## Packages

| Package | What it is | Status |
| --- | --- | --- |
| `@splitstat/nextjs` | Next.js: App Router, middleware, server-side assignment | In development |

## Links

- [splitstat.com](https://splitstat.com)

Built in India.
