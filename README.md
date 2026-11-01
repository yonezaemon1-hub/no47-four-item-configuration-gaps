# No.47 — Four-Item Unbounded Configuration Gaps via a Paired-Auxiliary Reduction

**Ryutaro Yonezu — Independent Researcher**  
Preprint v1.0 · 1 November 2026

**Mathematics: SOURCE-CONDITIONAL PASS. Novelty: INCONCLUSIVE. Not human peer-reviewed.**

This source-dependent corollary relies on OpenAI (2026), *Additive hardness and unbounded configuration gaps in bin packing*. It is not an independent proof of OpenAI's theorem. It makes no strengthened NP-hardness claim and no claim of established priority.

## Publication

- [GitHub Release v1.0](https://github.com/yonezaemon1-hub/no47-four-item-configuration-gaps/releases/tag/v1.0)
- [Zenodo Preprint 1.0](https://zenodo.org/records/23851724)
- DOI: [10.5281/zenodo.23851724](https://doi.org/10.5281/zenodo.23851724)
- Published 2026-11-01. The public PDF and ZIP were downloaded from both GitHub and Zenodo after publication; all four SHA256 values match the canonical source files.

## Result and scope

A paired-auxiliary reduction joins two source roles into one physical item, giving rational bin-packing instances with every item size strictly greater than 1/5 and thus at most four items per unit bin. The source fractional witness is preserved with value B. Any packing of the transformed instance into B+g bins decodes into a packing of the source instance into at most B+357g bins. Conditional on the imported source theorem and its fractional templates, the unrestricted configuration LP therefore has unbounded additive integrality gaps in this class.

## Files

- `No47_Four_Item_Gaps_v1_0.pdf` — frozen four-page English manuscript.
- `No47_Four_Item_Gaps_v1_0.tex` — manuscript LaTeX source.
- `No47_Publication_Ready_v1_0_20261101.zip` — original publication-ready package, unchanged.
- `No47_four_item_gap_audit_v0_3.zip` — frozen audit bundle and exact-arithmetic verification materials.
- `PUBLICATION_STATUS.md` and `README_RELEASE.md` — original prepublication records, unchanged. Their unpublished status describes the packaging stage, not this repository's current publication state.
- `SHA256SUMS.txt` — original five-file package manifest.
- `PUBLIC_ASSET_SHA256SUMS.txt` — hashes of the formally attached PDF and publication-ready ZIP.

The canonical public PDF is the copy inside the publication-ready ZIP, with SHA256 `645fab7639f9949dd445d5531f5553d71d22da7a200b526320e20be1352e0940`. The separately saved PDF from the preparation conversation has identical extracted text and page renderings but different provenance-signature bytes; it is not the canonical asset released here.

## Verification and limits

The original publication-package manifest (5 files) and the nested audit manifest (17 files) were checked before release. Prior recorded checks cover the 17 fixed-pair groups, all 35 four-role multisets, the 357g decoding arithmetic, and parser smoke/negative tests. The optional exact-source parser requires the five authenticated OpenAI TeX files listed in `audit/SOURCE_REFERENCES.json` in the audit bundle. The source theorem and its Lean proof were not rebuilt for this publication operation. SHA256 equality verifies file identity, not mathematical correctness.

Targeted prior-art searches did not locate a directly matching theorem; novelty remains inconclusive. No human peer review or exhaustive priority clearance has been performed.

## Source acknowledgment

OpenAI (2026), *Additive hardness and unbounded configuration gaps in bin packing*, 24 September 2026. [Official research source](https://github.com/openai/math/tree/main/preprints/Additive-hardness-and-unbounded-configuration-gaps-in-bin-packing-September-24-2026).

The paired reduction imports the source's five-role inventory, original soundness theorem, and selected/unselected fractional packing templates. This work is not affiliated with or endorsed by OpenAI.

## Rights

Copyright (c) 2026 Ryutaro Yonezu. All rights reserved for the original manuscript and independent verification materials. Referenced third-party works retain their respective rights. No open-source license is granted by this release.
