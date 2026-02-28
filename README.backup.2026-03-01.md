# M7 Projects by `linearblade`

Low-level JavaScript primitives and systems tooling built from 25+ years of production work.

The current release focus is `m7-js-lib` and the showcase app runtime built on top of it.

## Current Focus

- **Showcase runtime:** [`m7-js-lib-app-active-tags`](https://github.com/linearblade/m7-js-lib-app-active-tags)
- **Core foundation:** [`m7-js-lib`](https://github.com/linearblade/m7-js-lib)
- **Important dependencies:** `m7BootStrap`, `m7Fetch`, and core primitive modules

`m7-js-lib` exports a singleton `lib` utility runtime.
Other m7 modules attach to that object, so projects can compose behavior without framework lock-in.

## How The Stack Fits Together

```text
m7-js-lib (core lib object)
  -> primitive modules (dom, log, interval, tree, etc.)
  -> app runtime modules (active-tags)
  -> legacy-support loaders/network tooling (m7BootStrap, m7Fetch)
  -> site/product-specific modules
```

## Project Showcase

| Project | Role | Notes |
|---|---|---|
| [`m7-js-lib-app-active-tags`](https://github.com/linearblade/m7-js-lib-app-active-tags) | Showcase | Deterministic workflow orchestration for DOM components |
| [`m7-js-lib`](https://github.com/linearblade/m7-js-lib) | Core | Normalization-first singleton utility runtime |
| [`m7-js-lib-primitive-dom-eventdelegator`](https://github.com/linearblade/m7-js-lib-primitive-dom-eventdelegator) | Primitive | Selector-aware event delegation |
| [`m7-js-lib-primitive-dom-changeobserver`](https://github.com/linearblade/m7-js-lib-primitive-dom-changeobserver) | Primitive | Selector-aware DOM change observation |
| [`m7-js-lib-primitive-log`](https://github.com/linearblade/m7-js-lib-primitive-log) | Primitive | Synchronous structured log/event capture |
| [`m7-js-lib-primitive-interval`](https://github.com/linearblade/m7-js-lib-primitive-interval) | Primitive | Policy-driven async interval scheduling |
| [`m7-js-lib-tree`](https://github.com/linearblade/m7-js-lib-tree) | Tooling | Runtime JS object graph inspector |
| [`m7BootStrap`](https://github.com/linearblade/m7BootStrap) | Loader | Runtime package loading and mounting toolkit |
| [`m7Fetch`](https://github.com/linearblade/m7Fetch) | Network | Dynamic network/spec/module toolkit |

## Naming And Migration Notes

- `m7BootStrap` and `m7Fetch` are older names and likely to be cleaned up over time.
- Several historical projects have already been rolled into `m7-js-lib` or superseded by newer `m7-js-lib-*` modules.
- This profile will keep highlighting the currently relevant modules as consolidation continues.

## What Is Coming Next

- More `m7-js-lib` modules and app-level packages.
- Additional systems-level repositories, including substantial C code.
- A clearer cross-language layout showing how JS and C components fit together.

## Philosophy

- Composable primitives over monolithic frameworks.
- Explicit behavior over hidden magic.
- Production-first engineering over demo-only abstractions.

## Connect

- GitHub: [github.com/linearblade](https://github.com/linearblade)
- X: [@thegrimscalper](https://x.com/thegrimscalper)
- Website: [m7.org](https://m7.org)

> Tools should disappear into the work, not fight for attention.
