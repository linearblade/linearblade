

### Step-by-Step: Create Your Profile README (The "Project Page")
1. Go to GitHub → Click the green **+ New** button (top-right) → **New repository**.

# M7 — Low-Level Primitives & Systems Toolkits

**25+ years of battle-tested, bloat-free tools** — now being open-sourced.

I build minimal, composable primitives so you can construct reliable systems without framework tax.  
Focus: DOM mastery, event handling, observation, logging, timing, tree traversal, session normalization, fetch wrappers, and secure inter-process comms (UDP daemon in C).

Currently releasing the **m7-js-lib-*** family — lightweight ES modules for modern browsers/Node.

## Why These Primitives?
- Zero dependencies (most are <1KB gzipped)
- Performance-first (no polyfills bloat, native APIs leveraged)
- Production-hardened (used in real businesses, not demos)
- Documented for longevity — JSDoc + examples

Pinned highlights:
- **siglatch** — Cryptographically-authenticated UDP daemon for remote control/logging
- **m7-js-lib-tree** — Interactive object tree explorer for massive APIs
- **m7-js-lib-interval** — Precise, cancelable timers & schedulers
- **m7-js-lib-primitive-dom-eventdelegator** — Efficient delegation without frameworks
<!--
## Quick Start (Example Usage)
```js
import { createEventDelegator } from 'm7-js-lib-primitive-dom-eventdelegator';

// Delegate clicks on dynamic elements
const delegator = createEventDelegator(document.body);
delegator.on('click', '.dynamic-btn', (e) => {
  console.log('Clicked dynamic button!', e.target);
});
```

## Ecosystem Overview
| Library | Purpose | Size (gzipped) | Stars | Link |
|---------|---------|----------------|-------|------|
| m7-js-lib-tree | Deep object inspection & console viz | ~2KB | - | [Repo](https://github.com/linearblade/m7-js-lib-tree) |
| m7-js-lib-interval | Advanced timing primitives | ~1.5KB | - | [Repo](https://github.com/linearblade/m7-js-lib-interval) |
| siglatch | Secure UDP daemon (C) | - | 24 | [Repo](https://github.com/linearblade/siglatch) |
| ... | ... | ... | ... | ... |

More coming — full m7 suite targeted for Q2 2026 release.

## Skills & Philosophy
- Architect-level JS (internals, perf, no-framework DOM)
- Systems programming (C networking/crypto)
- Anti-bloat: Reinvent only when better
- Documentation-first approach

  -->

Connect:  
X: [@thegrimscalper](https://x.com/thegrimscalper)  
Site: [m7.org](https://m7.org)

> "Tools should disappear into the work — not fight for attention."

