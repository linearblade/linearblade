# Scratchpad: M7 Project Page Draft

Draft only. Do not promote yet.

## M7: Emergent Frontend Framework

M7 is converging into a framework from the bottom up: primitives first, runtime composition second, app framework layer on top.

The goal is to build complex browser applications without full framework lock-in.

## Start Here

- Core runtime: [`m7-js-lib`](https://github.com/linearblade/m7-js-lib)
- Showcase app framework: [`m7-js-lib-app-active-tags`](https://github.com/linearblade/m7-js-lib-app-active-tags)
- Runtime package loading: [`m7BootStrap`](https://github.com/linearblade/m7BootStrap)

## Framework Model

M7 JS architecture:
- Foundation runtime (`lib`)
- Primitive modules (DOM, observation, timing, logging, workspace)
- Runtime orchestration (dynamic loading and fetch tools)
- App framework layer (ActiveTags and similar runtimes)
- Tooling and support utilities

## JavaScript Stack By Layer

### Foundation Runtime

Description:
Singleton utility runtime that other modules attach to.

Repos:
- [`m7-js-lib`](https://github.com/linearblade/m7-js-lib)

### App Framework Layer

Description:
Higher-level orchestration for interactive browser apps.

Repos:
- [`m7-js-lib-app-active-tags`](https://github.com/linearblade/m7-js-lib-app-active-tags)

### Primitive Layer

Description:
Low-level composable building blocks for browser behavior and control.

Repos:
- [`m7-js-lib-primitive-dom-eventdelegator`](https://github.com/linearblade/m7-js-lib-primitive-dom-eventdelegator)
- [`m7-js-lib-primitive-dom-changeobserver`](https://github.com/linearblade/m7-js-lib-primitive-dom-changeobserver)
- [`m7-js-lib-primitive-interval`](https://github.com/linearblade/m7-js-lib-primitive-interval)
- [`m7-js-lib-primitive-log`](https://github.com/linearblade/m7-js-lib-primitive-log)
- [`m7-js-workspace`](https://github.com/linearblade/m7-js-workspace)

### Runtime Orchestration

Description:
Dynamic loading/unloading and network fetch/spec/module tooling for runtime-managed apps.

Repos:
- [`m7BootStrap`](https://github.com/linearblade/m7BootStrap)
- [`m7Fetch`](https://github.com/linearblade/m7Fetch)

Dependency note:
- `m7BootStrap` depends on `m7Fetch`.

### Tooling And Support

Description:
Inspection and cross-cutting utilities used across projects.

Repos:
- [`m7-js-lib-tree`](https://github.com/linearblade/m7-js-lib-tree)
- [`m7-js-session-normalizer`](https://github.com/linearblade/m7-js-session-normalizer)
- [`PageCement`](https://github.com/linearblade/PageCement)

### Legacy

Description:
Superseded modules retained for reference/compatibility.

Repos:
- [`m7-js-lib-098`](https://github.com/linearblade/m7-js-lib-098)

## Current Focus

- Finish and stabilize `m7-js-lib`.
- Showcase architecture via `m7-js-lib-app-active-tags`.
- Keep runtime loading model (`m7BootStrap` + `m7Fetch`) central.
- Keep this page strictly framework-oriented (JavaScript stack only).
