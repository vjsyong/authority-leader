# Changelog - Leader Interface System

## 0.2.0 - 2026-10-08

- Consolidated as this repository. The pack contents are byte-identical to
  the state previously published in the design-authority repository; this
  repo is now the canonical home.
- History before this point lives in `vjsyong/design-authority`
  (docs/synthesis, docs/portability, docs/evolution for the triage lines).

## Unreleased (2026-10-09)

- Verification contract: instrument exclusions corrected after the v3.1d lens
  review-tooling additions - the rule-strip regexes now cover `#provPanel`
  (the old `prov-` form missed the element id), and the shadow/animation/
  background censuses skip the instrument subtree. Clean build re-run:
  21 PASS / 1 known finding (`focus-visible` - the search input).

