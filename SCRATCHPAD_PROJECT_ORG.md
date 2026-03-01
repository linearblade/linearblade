# Scratchpad: M7 As An Emergent Frontend Framework

Working framing:
M7 JS is converging into a framework, even though it was built bottom-up from primitives.

Core idea:
Build complex browser applications without adopting a monolithic frontend framework.

## Root Positioning

M7 is a framework-light browser architecture:
- composable primitives
- runtime module loading
- explicit lifecycle control
- opt-in subsystems instead of all-in framework lock-in

## JavaScript Framework Stack (Grouped By Layer)

### 1) Foundation Runtime

Purpose:
Base singleton `lib` runtime that everything else can attach to.

Repos:
- [`m7-js-lib`](https://github.com/linearblade/m7-js-lib) (core runtime)

### 2) App Framework Layer

Purpose:
Higher-level app orchestration built on top of the core runtime and primitives.

Repos:
- [`m7-js-lib-app-active-tags`](https://github.com/linearblade/m7-js-lib-app-active-tags) (showcase app framework runtime)

### 3) Primitive Layer (Framework Building Blocks)

Purpose:
Reusable low-level browser primitives that define behavior contracts.

Repos:
- [`m7-js-lib-primitive-dom-eventdelegator`](https://github.com/linearblade/m7-js-lib-primitive-dom-eventdelegator)
- [`m7-js-lib-primitive-dom-changeobserver`](https://github.com/linearblade/m7-js-lib-primitive-dom-changeobserver)
- [`m7-js-lib-primitive-interval`](https://github.com/linearblade/m7-js-lib-primitive-interval)
- [`m7-js-lib-primitive-log`](https://github.com/linearblade/m7-js-lib-primitive-log)
- [`m7-js-workspace`](https://github.com/linearblade/m7-js-workspace)

### 4) Runtime Orchestration And Loading

Purpose:
Dynamic loading/unloading, package lifecycle control, and runtime fetch/network utilities.

Repos:
- [`m7BootStrap`](https://github.com/linearblade/m7BootStrap) (runtime package manager/loader)
- [`m7Fetch`](https://github.com/linearblade/m7Fetch) (fetch/network/spec/module loading)

### 5) Developer Tooling And Inspection

Purpose:
Inspect large runtime object graphs and support discovery in big API surfaces.

Repos:
- [`m7-js-lib-tree`](https://github.com/linearblade/m7-js-lib-tree)

### 6) Cross-Cutting Utility Modules

Purpose:
Modules used across apps for specialized concerns that are not full app frameworks.

Repos:
- [`m7-js-session-normalizer`](https://github.com/linearblade/m7-js-session-normalizer) (session abstraction/normalization)
- [`PageCement`](https://github.com/linearblade/PageCement) (viewport stabilization, zoom/scroll control)

### 7) Legacy / Superseded

Purpose:
Historical modules kept for reference or compatibility.

Repos:
- [`m7-js-lib-098`](https://github.com/linearblade/m7-js-lib-098) (superseded by `m7-js-lib`)

## Systems Track (Separate From JS Framework Stack)

Purpose:
Low-level C systems components that complement the JS ecosystem but are not browser framework modules.

Repos:
- [`siglatch`](https://github.com/linearblade/siglatch)

## Next Pass Candidates

- Collapse this into a publish-ready `PROJECTS.md` with the same layer model.
- Add a one-line "depends on" field under each repo.
- Add status tags: `active`, `supporting`, `legacy`.
