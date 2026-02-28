# M7 Projects by `linearblade`

Low-level JavaScript primitives and systems tooling built from 25+ years of production work.

## Start Here

- Full repository catalog (language-first): [PROJECTS.md](./PROJECTS.md)
- Core foundation: [`m7-js-lib`](https://github.com/linearblade/m7-js-lib)
- Showcase runtime: [`m7-js-lib-app-active-tags`](https://github.com/linearblade/m7-js-lib-app-active-tags)

## Current Direction

The current focus is finishing `m7-js-lib` and `m7-js-lib-app-active-tags`.

`m7-js-lib` exports a singleton `lib` utility runtime. Other m7 modules attach to that `lib` object so projects can compose behavior without framework lock-in.

## Stack Model

```text
m7-js-lib (core lib object)
  -> primitives (DOM, observation, logging, interval, tree)
  -> app runtimes (active-tags)
  -> runtime/network support (m7BootStrap, m7Fetch)
  -> site/product modules
```

## Migration Notes

- `m7BootStrap` and `m7Fetch` keep legacy names for now.
- Older projects are being rolled into `m7-js-lib` or superseded by newer `m7-js-lib-*` modules.
- Upcoming C repositories will be grouped under the `C / Systems` section in `PROJECTS.md`.

## Connect

- GitHub: [github.com/linearblade](https://github.com/linearblade)
- X: [@thegrimscalper](https://x.com/thegrimscalper)
- Website: [m7.org](https://m7.org)

> Tools should disappear into the work, not fight for attention.
