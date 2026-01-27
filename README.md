<!--
m7
├── js                              # Core JavaScript library root
│   ├── lib                         # Primitive / modular building blocks (your main focus)
│   │   ├── primitive
│   │   │   ├── dom
│   │   │   │   ├── eventdelegator
│   │   │   │   │   Name: m7-js-lib-primitive-dom-eventdelegator
│   │   │   │   │   Link: https://github.com/linearblade/m7-js-lib-primitive-dom-eventdelegator
│   │   │   │   │   Purpose: A selector-aware DOM event delegation primitive built on top of native event bubbling and capture that routes events through explicit selectors and policies.
│   │   │   │   └── changeobserver
│   │   │   │       Name: m7-js-lib-primitive-dom-changeobserver
│   │   │   │       Link: https://github.com/linearblade/m7-js-lib-primitive-dom-changeobserver
│   │   │   │       Purpose: (none)
│   │   │   ├── log
│   │   │   │   Name: m7-js-lib-primitive-log
│   │   │   │   Link: https://github.com/linearblade/m7-js-lib-primitive-log
│   │   │   │   Purpose: (none)
│   │   │   └── interval
│   │   │       Name: m7-js-lib-interval
│   │   │       Link: https://github.com/linearblade/m7-js-lib-interval
│   │   │       Purpose: Precise, cancelable timers & schedulers
│   │   ├── tree                    # Specialized inspector tool
│   │   │   Name: m7-js-lib-tree
│   │   │   Link: https://github.com/linearblade/m7-js-lib-tree
│   │   │   Purpose: Runtime JavaScript object tree inspector and console for exploring large APIs and object graphs.
│   │   └── 098                     # Possibly experimental / misc primitive
│   │       Name: m7-js-lib-098
│   │       Link: https://github.com/linearblade/m7-js-lib-098
│   │       Purpose: (none)
│   └── (loose / non-lib prefixed)  # Older m7 JS tools before formal lib boundary
│       ├── workspace
│       │   Name: m7-js-workspace
│       │   Link: https://github.com/linearblade/m7-js-workspace
│       │   Purpose: (none)
│       ├── session-normalizer
│       │   Name: m7-js-session-normalizer
│       │   Link: https://github.com/linearblade/m7-js-session-normalizer
│       │   Purpose: (none)
│       ├── bootstrap
│       │   Name: m7BootStrap
│       │   Link: https://github.com/linearblade/m7BootStrap
│       │   Purpose: (none)
│       └── fetch
│           Name: m7Fetch
│           Link: https://github.com/linearblade/m7Fetch
│           Purpose: (none)
├── (other-js)                      # Standalone / non-m7 prefixed JS projects
│   ├── PageCement
│   │   Name: PageCement
│   │   Link: https://github.com/linearblade/PageCement
│   │   Purpose: (none)
│   └── agility-trial
│       Name: agility-trial
│       Link: https://github.com/linearblade/agility-trial
│       Purpose: alacritysim.com agility trials information docusaur for pre game construction research
└── systems                         # Non-JS / lower-level
    └── siglatch
        Name: siglatch
        Link: https://github.com/linearblade/siglatch
        Purpose: A lightweight, cryptographically-authenticated UDP daemon for remote access, logging, and job control.

        -->

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

