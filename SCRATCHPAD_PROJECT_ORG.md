# M7 Project Page

M7 is an emergent frontend framework: composable primitives and runtime modules that scale from utility usage to full app architecture without forcing a single framework model. ActiveTags sits on top of a layered runtime (`m7-js-lib` core + primitives + runtime loading tools), so adoption can stay incremental while still supporting larger, orchestrated browser applications.

![ActiveTags Logo](https://raw.githubusercontent.com/linearblade/m7-js-lib-app-active-tags/master/logo.png)

Start here: [`m7-js-lib-app-active-tags`](https://github.com/linearblade/m7-js-lib-app-active-tags). It is the most user-facing flag bearer of the M7 stack: deterministic DOM workflow orchestration, a standalone min bundle (`dist/activeTags.standalone.v1.0.min.js`), a simple installation path, and built-in brand assets for demos and presentations. If you are new to M7, ActiveTags is the fastest way to understand how the framework feels in real use.

## Supporting Repos

### m7-js-lib Layer

- [`m7-js-lib`](https://github.com/linearblade/m7-js-lib): Core singleton runtime (`lib`) that the framework stack builds on.
- [`m7-js-lib-app-active-tags`](https://github.com/linearblade/m7-js-lib-app-active-tags): Flagship app-layer runtime built on top of `m7-js-lib`.
- [`m7-js-lib-primitive-dom-eventdelegator`](https://github.com/linearblade/m7-js-lib-primitive-dom-eventdelegator): DOM event delegation primitive for selector-routed behavior.
- [`m7-js-lib-primitive-dom-changeobserver`](https://github.com/linearblade/m7-js-lib-primitive-dom-changeobserver): DOM change observation primitive for structured mutation reporting.
- [`m7-js-lib-primitive-interval`](https://github.com/linearblade/m7-js-lib-primitive-interval): Interval/scheduling primitive for controlled async recurring work.
- [`m7-js-lib-primitive-log`](https://github.com/linearblade/m7-js-lib-primitive-log): Logging primitive for synchronous structured event capture.
- [`m7-js-workspace`](https://github.com/linearblade/m7-js-workspace): Workspace utility module in the main m7 runtime architecture.
- [`m7-js-lib-tree`](https://github.com/linearblade/m7-js-lib-tree): Runtime inspection tooling for exploring large object graphs.

### Runtime Loader / Networking

- [`m7BootStrap`](https://github.com/linearblade/m7BootStrap): Runtime package manager for loading, mounting, and unloading modules/content.
- [`m7Fetch`](https://github.com/linearblade/m7Fetch): Fetch/network/spec/module loading toolkit used by `m7BootStrap`.
- [`m7-js-session-normalizer`](https://github.com/linearblade/m7-js-session-normalizer): Session abstraction utility for normalized app-facing session state.

### UI Survival Utility

- [`PageCement`](https://github.com/linearblade/PageCement): Viewport control utility that helps lock down UI behavior (zoom/scroll/viewport stability).
