# Module 4 — Translating pathology into AI research

## Questions for an FNA image dataset
1. What is the target: Bethesda category, surgical histology, molecular alteration, or clinical outcome?
2. Are labels confirmed by resection, follow-up, or cytology alone? Are NIFTP and indeterminate cases included?
3. Are data split by **patient** (not image or tile) to prevent leakage?
4. Are there differences in stain, scanner/smartphone, site, magnification, and image quality?
5. Does the model focus on nuclear details or spurious backgrounds? Use expert-reviewed regions, not saliency maps alone, as evidence.
6. Is performance reported by site, class, and diagnostic subgroup, with uncertainty and calibration?
7. Are sensitivity/specificity thresholds selected without using the held-out test set?

## Suggested mini-project
Build a pathology feature dictionary for 20 educational FNA images, with pathologist review where possible. Fields: image ID, stain, specimen preparation, cell-group pattern, nuclear enlargement, grooves, pseudoinclusions, chromatin, confidence, artifacts, label source, and 'not assessable'. Avoid claiming true capsule invasion or definitive NIFTP from FNA.

## Reading prompt
Compare the 'classical papillary' versus 'papillary-like' nuclei in Ohori et al. (2026). Which features might be observable in smartphone FNA images? Which require histology or molecular testing? How could site-specific stain differences alter their visibility?
