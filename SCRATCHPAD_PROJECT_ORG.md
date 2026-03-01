# Scratchpad: Project-Centric Organization (Draft)

This is a working draft to organize repositories by product/project family instead of by language.

## ActiveTags

Description:
Deterministic workflow orchestration for DOM components and medium/high-complexity interactive web apps.

Repos:
- [`m7-js-lib-app-active-tags`](https://github.com/linearblade/m7-js-lib-app-active-tags) (primary runtime)
- [`m7-js-lib`](https://github.com/linearblade/m7-js-lib) (core utility runtime)
- [`m7-js-lib-primitive-dom-eventdelegator`](https://github.com/linearblade/m7-js-lib-primitive-dom-eventdelegator)
- [`m7-js-lib-primitive-dom-changeobserver`](https://github.com/linearblade/m7-js-lib-primitive-dom-changeobserver)
- [`m7-js-lib-primitive-interval`](https://github.com/linearblade/m7-js-lib-primitive-interval)
- [`m7-js-lib-primitive-log`](https://github.com/linearblade/m7-js-lib-primitive-log)
- [`m7-js-lib-tree`](https://github.com/linearblade/m7-js-lib-tree) (debug/inspection tooling)

## m7-js-lib

Description:
Normalization-first singleton utility runtime (`lib`) that other m7 modules attach to.

Repos:
- [`m7-js-lib`](https://github.com/linearblade/m7-js-lib) (core)
- [`m7-js-workspace`](https://github.com/linearblade/m7-js-workspace) (architecture utility)
- [`m7-js-lib-tree`](https://github.com/linearblade/m7-js-lib-tree) (runtime introspection tool)

Legacy:
- [`m7-js-lib-098`](https://github.com/linearblade/m7-js-lib-098) (superseded)

## m7BootStrap

Description:
Runtime dynamic loading/unloading of modules, assets, and package-defined content, with dependency resolution and lifecycle controls.

Repos:
- [`m7BootStrap`](https://github.com/linearblade/m7BootStrap) (runtime package manager/loader)
- [`m7Fetch`](https://github.com/linearblade/m7Fetch) (fetch/network/spec/module loading tools used by BootStrap)

## Session Layer

Description:
Session abstraction and normalization so apps use one consistent session/user shape across providers.

Repos:
- [`m7-js-session-normalizer`](https://github.com/linearblade/m7-js-session-normalizer)

## Siglatch

Description:
Systems-side secure daemon in C for remote control, logging, and job control.

Repos:
- [`siglatch`](https://github.com/linearblade/siglatch)

## PageCement

Description:
Viewport control utility to stabilize viewport height, lock scroll when needed, and prevent unwanted zoom gestures/shortcuts.

Repos:
- [`PageCement`](https://github.com/linearblade/PageCement)

## Optional Additional Bucket (If You Want It)

Description:
General or one-off projects that do not belong inside the main M7 product families.

Repos:
- `cs_books` (reference/content)

## Notes For Next Pass

- Decide whether `Session Layer` should remain standalone or be merged under `ActiveTags` / `m7-js-lib`.
- Decide whether `PageCement` is branded as an M7 family project or as independent utility tooling.
- If desired, add one level deeper in each project: `core`, `dependencies`, `support`, `legacy`.
