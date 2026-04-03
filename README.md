# XENOr

XENOr is a deterministic, simulation-first research stack. If you are landing
cold on GitHub, start with [`xenor-site`](https://github.com/XENOr-god/xenor-site)
for the public overview, then move into `xenor-core`, `xenor-sim`, and
`xenor-engine` depending on which layer you need.

## Status

The current public stack is active, but not uniformly production-ready.

- Active public surfaces: `xenor-site`, `xenor-core`, `xenor-sim`,
  `xenor-engine`
- Archived historical repo: `xenor-sale`
- Experimental and research-stage work is labeled in each repository README

## Start Here

1. [`xenor-site`](https://github.com/XENOr-god/xenor-site) /
   `https://xenor-site.vercel.app`
   The canonical public surface and the best first stop for newcomers.
2. [`xenor-core`](https://github.com/XENOr-god/xenor-core)
   The deterministic execution and protocol-systems layer.
3. [`xenor-sim`](https://github.com/XENOr-god/xenor-sim)
   The scenario and validation layer built around `xenor-core`.
4. [`xenor-engine`](https://github.com/XENOr-god/xenor-engine)
   The lower-level deterministic engine and replay/snapshot systems layer.
5. [`xenor-sale`](https://github.com/XENOr-god/xenor-sale)
   An archived Solana sale prototype kept only as historical research context.

## Why This Repo Exists

This profile repository is the GitHub entry point for the XENOr stack. Its job
is to point first-time visitors to the right repository quickly and to make the
active vs experimental vs historical boundaries obvious.

## Relationship to the XENOr Stack

- `xenor-site` is the canonical public surface
- `xenor-core` is the deterministic execution/core systems layer
- `xenor-sim` is the validation and scenario layer on top of `xenor-core`
- `xenor-engine` is the deterministic engine substrate for tick/replay/snapshot
  work
- `xenor-sale` is historical only and not part of the active path

## Quick Start

- Open `https://xenor-site.vercel.app` first if you want the public overview.
- Open [`xenor-core`](https://github.com/XENOr-god/xenor-core) next if you want
  the main protocol-systems code.
- Open [`xenor-sim`](https://github.com/XENOr-god/xenor-sim) if you want to see
  how scenarios and validation runs are modeled around `xenor-core`.
- Open [`xenor-engine`](https://github.com/XENOr-god/xenor-engine) if you want
  the reusable deterministic engine substrate and replay/snapshot work.

## Repository Boundaries

- This profile repo is a navigation surface, not a product or protocol repo.
- It should not duplicate architecture detail that already lives in
  `xenor-site`, `xenor-core`, `xenor-sim`, or `xenor-engine`.
- It should make the stack easier to enter, not act as a parallel documentation
  site.

## Related Repositories

- [`xenor-site`](https://github.com/XENOr-god/xenor-site) — canonical public
  surface and first stop
- [`xenor-core`](https://github.com/XENOr-god/xenor-core) — deterministic
  execution/core systems layer
- [`xenor-sim`](https://github.com/XENOr-god/xenor-sim) — simulation and
  validation layer
- [`xenor-engine`](https://github.com/XENOr-god/xenor-engine) — deterministic
  engine and replay/snapshot substrate
- [`xenor-sale`](https://github.com/XENOr-god/xenor-sale) — archived
  historical sale prototype

## Contributing

No standalone contributing guide is currently published in this repository.
Use issues or pull requests directly for navigation or wording fixes.

## License

No standalone license file is currently published in this repository.
