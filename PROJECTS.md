# Project Index

Language-first catalog for `linearblade` repositories.

Organization model:
- Language
- Project role inside that language

Source snapshot:
- GitHub account: `linearblade`
- Built from GitHub API repo metadata during local catalog generation

## JavaScript

### Core

| Project | Role | Status | Notes |
|---|---|---|---|
| [`m7-js-lib`](https://github.com/linearblade/m7-js-lib) | Core runtime | Active focus | Singleton `lib` foundation for the m7 JS stack |

### Showcase Apps

| Project | Role | Status | Notes |
|---|---|---|---|
| [`m7-js-lib-app-active-tags`](https://github.com/linearblade/m7-js-lib-app-active-tags) | Showcase app runtime | Active focus | Deterministic workflow orchestration for DOM components |

### Primitives And Tooling

| Project | Role | Status | Notes |
|---|---|---|---|
| [`m7-js-lib-primitive-dom-eventdelegator`](https://github.com/linearblade/m7-js-lib-primitive-dom-eventdelegator) | Primitive | Active | Selector-aware DOM event delegation |
| [`m7-js-lib-primitive-dom-changeobserver`](https://github.com/linearblade/m7-js-lib-primitive-dom-changeobserver) | Primitive | Active | Selector-aware DOM change observation |
| [`m7-js-lib-primitive-interval`](https://github.com/linearblade/m7-js-lib-primitive-interval) | Primitive | Active | Policy-driven async scheduling |
| [`m7-js-lib-primitive-log`](https://github.com/linearblade/m7-js-lib-primitive-log) | Primitive | Active | Synchronous structured log/event capture |
| [`m7-js-lib-tree`](https://github.com/linearblade/m7-js-lib-tree) | Dev tooling | Active | Runtime JS object graph inspector |
| [`m7-js-workspace`](https://github.com/linearblade/m7-js-workspace) | Primitive utility | Active | Part of the main `m7-js-lib` architecture |

### Runtime And Infra

| Project | Role | Status | Notes |
|---|---|---|---|
| [`m7BootStrap`](https://github.com/linearblade/m7BootStrap) | Runtime package manager/loader | Active/supporting | Dynamic loading and unloading of modules/content/packages; depends on `m7Fetch` |
| [`m7Fetch`](https://github.com/linearblade/m7Fetch) | Fetch/network toolkit | Active/supporting | HTTP/spec/module fetch tools used by `m7BootStrap` |
| [`m7-js-session-normalizer`](https://github.com/linearblade/m7-js-session-normalizer) | Session abstraction/normalizer | Active | Normalizes auth/session providers into a consistent app-facing session shape |

### Other JavaScript Projects

| Project | Role | Status | Notes |
|---|---|---|---|
| [`PageCement`](https://github.com/linearblade/PageCement) | Viewport control utility | Active | Stabilizes page viewport, locks scroll, and prevents zoom-in/out gestures/shortcuts |

### Legacy

| Project | Role | Status | Notes |
|---|---|---|---|
| [`m7-js-lib-098`](https://github.com/linearblade/m7-js-lib-098) | Legacy module | Legacy | Superseded by `m7-js-lib`; no longer active |

## C / Systems

| Project | Role | Status | Notes |
|---|---|---|---|
| [`siglatch`](https://github.com/linearblade/siglatch) | Systems daemon (C) | Active | Cryptographically-authenticated UDP daemon |

## Planned Expansion

- Add new C repositories under **C / Systems** as they are published.
- Keep JS modules split by role (`Core`, `Showcase`, `Primitives`, `Runtime`) to avoid catalog drift.
