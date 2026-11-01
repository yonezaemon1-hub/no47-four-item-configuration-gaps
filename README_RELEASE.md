# No.47 — Publication-ready package (not yet published)

**Title:** Four-Item Unbounded Configuration Gaps via a Paired-Auxiliary Reduction  
**Author:** Ryutaro Yonezu — Independent Researcher  
**Preprint version:** v1.0, 2026-11-01  
**Copyright / license:** All rights reserved for original manuscript and independent verification materials.  
**Novelty:** INCONCLUSIVE.  
**Peer review:** Not human peer-reviewed.  
**Source dependence:** A corollary relying on OpenAI (2026), *Additive hardness and unbounded configuration gaps in bin packing*. Not an independent proof of OpenAI's theorem. No strengthened NP-hardness claim.

## Files

- `No47_Four_Item_Gaps_v1_0.pdf` — publication manuscript, four pages.
- `No47_Four_Item_Gaps_v1_0.tex` — buildable LaTeX source for PDF.
- `No47_four_item_gap_audit_v0_3.zip` — frozen previously audited verification bundle; its original contents were not revised here.
- `PUBLICATION_STATUS.md` — verification status and limitations.
- `SHA256SUMS.txt` — SHA256 of all package contents except this manifest.

## Verification

Run `sha256sum -c SHA256SUMS.txt` in this folder. Extract the audit archive and run:

```sh
python -I verification/check_hashes.py
python -I verification/verify_no47.py
python -I verification/indep_table_check.py
python -I verification/test_source_table_parser.py
```

Optional exact-source check needs five specific OpenAI `.tex` files with authenticated Git blob SHAs, listed in `audit/SOURCE_REFERENCES.json` within the audit bundle.

## Citation / source acknowledgment

OpenAI (2026), *Additive hardness and unbounded configuration gaps in bin packing*, [official research repository](https://github.com/openai/math/tree/main/preprints/Additive-hardness-and-unbounded-configuration-gaps-in-bin-packing-September-24-2026). The new paired-auxiliary reduction relies on its five-role inventory and selected/unselected fractional packing templates.

## Publication safety

The package is ready for release processing, but **no GitHub repository or release, Zenodo publication or DOI has been created by this packaging operation.** Do not claim a DOI until Zenodo confirms it. Please verify exact released assets and SHA256 after publication.
