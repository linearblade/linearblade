# Project Index

Language-first catalog for `linearblade` repositories.

Organization model:
- Language
- Project role inside that language

Source snapshot:
- GitHub account: `linearblade`
- Repo count in last sync: `17`
- Built from GitHub API repo metadata during local catalog generation

## JavaScript

### Core

| Project | Role | Status | Notes |
|---|---|---|---|
| [`m7-js-lib`](https://github.com/linearblade/m7-js-lib) | Core runtime | Active focus | Singleton `lib` foundation for the m7 JS stack |
| [`m7-js-lib-098`](https://github.com/linearblade/m7-js-lib-098) | Core/experimental | Active | Early/experimental module in the `m7-js-lib` line |

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

### Runtime And Infra

| Project | Role | Status | Notes |
|---|---|---|---|
| [`m7BootStrap`](https://github.com/linearblade/m7BootStrap) | Runtime loader | Active/supporting | Older name, still foundational in stack |
| [`m7Fetch`](https://github.com/linearblade/m7Fetch) | Network toolkit | Active/supporting | HTTP/spec/module loading utilities |
| [`m7-js-workspace`](https://github.com/linearblade/m7-js-workspace) | Workspace utility | Active | Supporting runtime utility |
| [`m7-js-session-normalizer`](https://github.com/linearblade/m7-js-session-normalizer) | Session utility | Active | Session normalization utility |

### Other JavaScript Projects

| Project | Role | Status | Notes |
|---|---|---|---|
| [`PageCement`](https://github.com/linearblade/PageCement) | Standalone JS project | Active | Separate from current core focus |
| [`agility-trial`](https://github.com/linearblade/agility-trial) | Domain app/project | Active | AlacritySim agility-trial project |

## C / Systems

| Project | Role | Status | Notes |
|---|---|---|---|
| [`siglatch`](https://github.com/linearblade/siglatch) | Systems daemon (C) | Active | Cryptographically-authenticated UDP daemon |

## Other / Meta

| Project | Role | Status | Notes |
|---|---|---|---|
| [`linearblade`](https://github.com/linearblade/linearblade) | Catalog hub/profile repo | Active | Central index and showcase entry point |
| [`cs_books`](https://github.com/linearblade/cs_books) | Reference/content | Active | Book/reference repository |

## Planned Expansion

- Add new C repositories under **C / Systems** as they are published.
- Keep JS modules split by role (`Core`, `Showcase`, `Primitives`, `Runtime`) to avoid catalog drift.
