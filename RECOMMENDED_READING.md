# Recommended reading and visual resources

This is a staged reading list for engineers studying thyroid histopathology, FNA cytopathology, and AI. Books may require library access or purchase. Links are publisher/organization pages; verify access and editions.

## Start here: thyroid FNA interpretation

1. **Ali SZ and VanderLaan PA (editors). _The Bethesda System for Reporting Thyroid Cytopathology_, 3rd edition (2023).** Springer. https://link.springer.com/book/10.1007/978-3-031-28046-7
   - **Priority: highest.** Read introductory material and diagnostic categories first, then chapters on follicular-patterned lesions and papillary thyroid carcinoma.
   - Learn what each Bethesda category communicates, and why an FNA sample cannot show capsular or vascular invasion.
2. **_Thyroid FNA Cytology_, 3rd edition.** Springer. https://link.springer.com/book/10.1007/978-981-99-6782-7
   - Use as a second image-rich practical reference for cytomorphology and differential diagnosis.

## Tissue architecture, tumor entities, and molecular pathology

3. **WHO Classification of Tumours Editorial Board. _Endocrine and Neuroendocrine Tumours_, WHO Classification of Tumours, 5th edition (2025).** IARC/WHO. https://publications.iarc.who.int/Book-And-Report-Series/Who-Classification-Of-Tumours/Endocrine-And-Neuroendocrine-Tumours-2025
   - Authoritative reference for terminology and tumor classification. Consult thyroid sections for follicular adenoma, follicular carcinoma, PTC, and NIFTP. Not the easiest first read.
4. **Ohori NP et al. (2026). _The fascinating history of papillary thyroid carcinoma nuclei: revelation of two nuclear morphologies—“Classical papillary” and “papillary-like”, with different pathobiologic characteristics._** _Cancer Cytopathology_. https://doi.org/10.1002/cncy.70100
   - Read pages 2–5 for the historical transition from architectural to nuclear diagnosis; compare Figures 1–3 and Table 2 for morphology and cytology.

## Free educational resources

5. **Papanicolaou Society of Cytopathology image atlas.** https://www.papsociety.org/image-atlas/
   - Practice describing visible features before reading the diagnosis. Check image licensing before redistributing or using images for model training.
6. **American Thyroid Association: NIFTP patient education.** https://www.thyroid.org/niftp/
   - Accessible explanation of NIFTP and why terminology matters.
7. **2023 Bethesda System overview (PubMed).** https://pubmed.ncbi.nlm.nih.gov/37427847/
   - Supplemental overview of the updated reporting system.


8. **National University of Singapore (NUS) CytoWeb — Thyroid Picture Atlas.** https://blog.nus.edu.sg/cytoweb/picture-atlas/thyroid/
   - Additional thyroid cytopathology image resource for visual study. Compare cell groups and nuclear morphology with the descriptions in Modules 1–3. The page could not be independently inspected during this update; check its image captions and usage permissions before reusing figures or training models.

## Suggested reading by week

| Week | Read | Output |
|---|---|---|
| 1 | WHO thyroid normal structure sections or an introductory thyroid histology atlas | Labeled diagram of normal follicles and colloid |
| 2 | Ohori pp. 2–3; WHO follicular and papillary entities | Architecture comparison chart |
| 3 | Ohori Figures 1–3 and Table 2; Bethesda PTC sections | Nuclear morphology glossary with annotated examples |
| 4 | Bethesda 3rd ed., categories and follicular-neoplasm sections | Bethesda decision/uncertainty table |
| 5 | WHO FA/FC/PTC/NIFTP entries; Ohori pp. 4–9 | Tumor comparison matrix |
| 6 | Revisit Bethesda and Ohori with your AI dataset documentation | Label provenance and dataset-shift audit |

## Practical reading rules

- Always distinguish **histology** (tissue sections) from **cytology** (FNA cell preparations).
- Record **observed morphology**, **diagnostic interpretation**, and **ground-truth source** in separate fields.
- Do not infer invasion, definitive NIFTP, or benign-versus-malignant status from isolated FNA cells alone.
- The source paper reviews evolving interpretations; historical diagnostic rules should not be treated as current standalone criteria.
