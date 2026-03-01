# Scratchpad: M7 Project Page Draft

Start here: [`m7-js-lib-app-active-tags`](https://github.com/linearblade/m7-js-lib-app-active-tags). It is the most user-facing flag bearer of the M7 stack: deterministic DOM workflow orchestration, a standalone min bundle (`dist/activeTags.standalone.v1.0.min.js`), simple install path, and built-in brand assets (logo) for presentation/demo use. For new users, this is the fastest way to understand what M7 feels like in practice.

M7 is an emergent frontend framework: composable primitives and runtime modules that scale from utility usage to full app architecture without forcing a single framework model. ActiveTags sits on top of a layered runtime (`m7-js-lib` core + primitives + runtime loading tools), so adoption can stay incremental while still supporting larger, orchestrated browser applications.

## Supporting Repos

- Core runtime: [`m7-js-lib`](https://github.com/linearblade/m7-js-lib)
- Runtime loader: [`m7BootStrap`](https://github.com/linearblade/m7BootStrap)
- Fetch/network tooling (used by BootStrap): [`m7Fetch`](https://github.com/linearblade/m7Fetch)
- DOM event primitive: [`m7-js-lib-primitive-dom-eventdelegator`](https://github.com/linearblade/m7-js-lib-primitive-dom-eventdelegator)
- DOM change primitive: [`m7-js-lib-primitive-dom-changeobserver`](https://github.com/linearblade/m7-js-lib-primitive-dom-changeobserver)
- Interval/scheduling primitive: [`m7-js-lib-primitive-interval`](https://github.com/linearblade/m7-js-lib-primitive-interval)
- Log primitive: [`m7-js-lib-primitive-log`](https://github.com/linearblade/m7-js-lib-primitive-log)
- Workspace primitive utility: [`m7-js-workspace`](https://github.com/linearblade/m7-js-workspace)
- Runtime inspection tooling: [`m7-js-lib-tree`](https://github.com/linearblade/m7-js-lib-tree)
- Session abstraction utility: [`m7-js-session-normalizer`](https://github.com/linearblade/m7-js-session-normalizer)
- Viewport utility: [`PageCement`](https://github.com/linearblade/PageCement)
