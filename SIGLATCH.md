# Siglatch

`siglatch` is a security-first C daemon for cryptographically authenticated control over connectionless protocols (especially UDP). It is designed for operators who need low-overhead, scriptable remote control with minimal exposure: secure packet validation, revocable access workflows, and deterministic behavior in hostile network environments.

Start here: [`siglatch` repository](https://github.com/linearblade/siglatch).

## Core Docs

- Overview and usage: [`README.md`](https://github.com/linearblade/siglatch#readme)
- Feature specification: [`docs/FEATURE_SPEC.md`](https://github.com/linearblade/siglatch/blob/master/docs/FEATURE_SPEC.md)
- Security model: [`docs/SECURITY.md`](https://github.com/linearblade/siglatch/blob/master/docs/SECURITY.md)
- Compile and install: [`docs/OPERATIONS_COMPILE.md`](https://github.com/linearblade/siglatch/blob/master/docs/OPERATIONS_COMPILE.md), [`docs/OPERATIONS_INSTALL.md`](https://github.com/linearblade/siglatch/blob/master/docs/OPERATIONS_INSTALL.md)

## Focus

- Secure, low-footprint remote access control
- Scriptable operational signaling and automation hooks
- Minimal surface area compared with heavier VPN/web control stacks
