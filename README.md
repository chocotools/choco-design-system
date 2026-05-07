# choco-design-system

Shared brand register for the Choco platform.

This repo is the upstream home of three files:

- **`PRODUCT.md`** — brand register: audiences, voice, principles, anti-references, accessibility baseline.
- **`DESIGN.md`** — Stitch six-section visual spec: colors, typography, elevation, components, do's and don'ts. Eleven Named Rules including The Cream Paper Rule, The One Seal Rule, The Ledger-Green Means Signed Rule, The 65ch Rule, The Tonal-Layering Rule, The No-Glow Rule, The Asymmetric-Easing Rule, The Modal-Justification Rule.
- **`DESIGN.json`** — schemaVersion-2 sidecar tokens: OKLCH canonical names, 8-step tonal ramps, motion vocabulary, twelve self-contained component snippets renderable in a shadow DOM.

## How it is consumed

Mounted as a git submodule at `choco-design-system/` from:

- [`choco-hq/choco-hq`](https://github.com/choco-hq/choco-hq) — primary platform repo.
- [`oompa-tools/oompa`](https://github.com/oompa-tools/oompa) — peer-engine repo (see decision 0006 in choco-hq).

Register-scoped extensions live inside their consumer repos rather than here:

- `choco-hq/cho-co/web/PRODUCT.md` + `cho-co/web/DESIGN.md` — live web client product register.
- `oompa-tools/oompa/PRODUCT.md` + `oompa-tools/oompa/DESIGN.md` (when authored) — Oompa product register.

## Mutation flow

Changes land here as PRs. Submodule pointer bumps in consumer repos run normal CI (markdown + JSON validation). drift-watch #11 in `choco-hq/docs/north-star/intent.md` § *Drift-watches* fires symmetrically against both consumer repos when banned patterns appear in code.

## Decision provenance

- `choco-hq/docs/decisions/2026-04-30-adopt-design-system-upstream.md` (decision 0005) — ratified the three files as upstream sources.
- `choco-hq/docs/decisions/2026-05-07-shared-design-system-submodule.md` (decision 0007) — established this repo as the cross-repo home.

This README is the only original content authored in this repo. Everything else is `git filter-repo`-preserved history from `choco-hq/choco-hq`.
