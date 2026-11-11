# Thyroid lesions, tumor types, and Bethesda categories

**Educational reference for engineers working on thyroid FNA AI. Not a clinical diagnostic guideline.**

## Two separate classification axes

1. **Histopathologic entity:** what the lesion *is* (e.g., follicular adenoma, papillary thyroid carcinoma, medullary thyroid carcinoma), usually established by resection histology and/or ancillary testing.
2. **Bethesda cytology category:** what an FNA specimen *supports* (I–VI), with a category-level risk of malignancy (ROM). A Bethesda category is **not** a one-to-one mapping to a tumor type.

For example, **Bethesda IV (follicular neoplasm) is not equivalent to follicular carcinoma**. FNA cannot establish capsular or vascular invasion. Likewise, **NIFTP cannot be definitively diagnosed by FNA**.

## 2023 Bethesda categories and estimated adult malignancy risk

| Bethesda | Official 2023 name | Mean ROM | Expected range | Interpretation |
|---|---|---:|---:|---|
| I | Nondiagnostic | 13% | 5–20% | Insufficient material; **not** a benign diagnosis |
| II | Benign | 4% | 2–7% | Cytology favors a benign process |
| III | Atypia of undetermined significance (AUS) | 22% | 13–30% | Nuclear or architectural atypia insufficient for a more definitive category |
| IV | Follicular neoplasm | 30% | 23–34% | Follicular/oncocytic neoplasm suspected; invasion cannot be judged on FNA |
| V | Suspicious for malignancy | 74% | 67–83% | Concerning features, but insufficient for a definitive malignant call |
| VI | Malignant | 97% | 97–100% | Cytology supports malignancy, often with a specific subtype |

**Interpretation:** These are *category-level* ROM estimates from the 2023 Bethesda system (adult, primarily surgically followed nodules), **not** a tumor-specific malignant transformation risk or probability of metastasis. Local prevalences, verification bias, NIFTP counting, and population affect estimates.

Sources:
- [2023 Bethesda System original article](https://pubmed.ncbi.nlm.nih.gov/37427847/)
- [2023 Bethesda Table 2 (full-text PDF)](https://semnro.com.ar/wp-content/uploads/thy.2023.0141.pdf)
- [CMS table reproducing Bethesda 2023 mean/range](https://www.cms.gov/medicare-coverage-database/view/lcd.aspx?lcdid=39650)

## Common thyroid lesions and tumor types: typical FNA associations

**Important:** The Bethesda column gives *possible or typical cytology reporting categories*, not a deterministic mapping or a numerical risk specific to the lesion. 'Malignant' is a final diagnostic behavior category; 'low-risk' does not mean a Bethesda category.

| Lesion / entity | Behavior / classification | Characteristic pathology concept | Typical / possible Bethesda FNA category | Notes |
|---|---|---|---|---|
| Colloid / hyperplastic follicular nodule (nodular follicular disease) | Benign, non-neoplastic or hyperplastic | Abundant colloid; flat sheets of bland follicular cells | II; occasionally I if cyst fluid only | Common benign FNA |
| Hashimoto (lymphocytic) thyroiditis | Benign inflammatory | Lymphocytes, oncocytic/Hürthle change | II; occasionally III if atypical | Not a carcinoma |
| Subacute granulomatous thyroiditis | Benign inflammatory | Giant cells, granulomatous inflammation | II; sometimes I/III | Not a neoplasm |
| Follicular adenoma (FA) | Benign neoplasm | Encapsulated follicular-patterned lesion without invasion | III–IV, sometimes II | Definitive FA vs FC distinction requires histology |
| Oncocytic (Hürthle-cell) adenoma | Benign neoplasm | Oncocytic cells; no invasion | III–IV | Oncocytic features can also occur in thyroiditis |
| NIFTP (noninvasive follicular thyroid neoplasm with papillary-like nuclear features) | Low-risk, nonmalignant-designated neoplasm | Encapsulated/well-demarcated follicular pattern, papillary-like nuclei, no invasion, strict exclusion criteria | III–V, often III–IV | Cannot be definitively called on FNA; not counted as carcinoma in current classification |
| Follicular thyroid carcinoma (FTC) | Malignant differentiated follicular-cell-derived | Follicular pattern with capsular and/or vascular invasion | III–IV, sometimes V | Cytology cannot prove invasion |
| Oncocytic carcinoma | Malignant differentiated oncocytic-cell-derived | Oncocytic neoplasm with invasion | III–IV, sometimes V | Requires histologic assessment of invasion |
| Papillary thyroid carcinoma (PTC), classic | Malignant differentiated follicular-cell-derived | Classical PTC nuclei; often papillary architecture | V–VI; occasionally III | Nuclear grooves, pseudoinclusions, chromatin clearing; may be heterogeneous |
| Follicular-patterned PTC / infiltrative follicular variant | Malignant differentiated follicular-cell-derived | Follicular architecture with PTC-type nuclear features and infiltrative growth | III–VI | FNA may be indeterminate |
| Poorly differentiated thyroid carcinoma | Malignant, intermediate differentiation | Solid/trabecular/insular growth and high-grade features, depending on criteria | V–VI, sometimes III–IV | Distinct from 'intermediate malignancy risk' Bethesda categories |
| Medullary thyroid carcinoma (MTC) | Malignant C-cell-derived neuroendocrine carcinoma | Plasmacytoid/spindle cells, salt-and-pepper chromatin; amyloid may occur | V–VI; occasionally III–IV | Calcitonin and ancillary testing can support diagnosis; unlike PTC/FTC, derives from parafollicular C cells |
| Anaplastic thyroid carcinoma (ATC) | Malignant, highly aggressive undifferentiated carcinoma | Marked pleomorphism, spindle/giant cells, necrosis | V–VI, usually VI if adequately sampled | Aggressive clinical behavior; a different problem from differentiated PTC/FTC |
| Primary thyroid lymphoma | Malignant hematolymphoid neoplasm, **not thyroid carcinoma** | Atypical lymphoid cells | V–VI or I/III | May require flow cytometry / immunophenotyping |
| Metastatic carcinoma to thyroid | Malignant, **not primary thyroid carcinoma** | Depends on primary tumor | V–VI | Confirm origin with clinical history and ancillary tests |

### A practical distinction: 'intermediate' can mean three different things
- **Indeterminate FNA**: Bethesda III/IV (and sometimes V discussed as suspicious); a *diagnostic uncertainty category*, not a histologic tumor type.
- **Low-risk or borderline biological behavior**: e.g., NIFTP; a *tumor entity*, not an FNA category.
- **Poorly differentiated carcinoma**: a *malignant tumor type*, not a Bethesda risk interval.

## Major carcinoma families

| Family | Cell of origin | Examples | Helpful concept |
|---|---|---|---|
| Differentiated follicular-cell-derived | Thyroid follicular epithelial cells | PTC, FTC, oncocytic carcinoma | May retain thyroid differentiation |
| Poorly differentiated / high-grade follicular-cell-derived | Follicular epithelial lineage | Poorly differentiated thyroid carcinoma | More aggressive morphology than conventional differentiated tumors |
| Undifferentiated | Thyroid follicular epithelial lineage in most cases | Anaplastic thyroid carcinoma | Highly aggressive; marked cellular atypia |
| Neuroendocrine | Parafollicular C cells | Medullary thyroid carcinoma | Calcitonin-related, often RET-associated |

## For image AI research

Record **(a) cytology Bethesda label, (b) final surgical histology, (c) molecular data, and (d) clinical outcome** as distinct targets when available. Avoid treating Bethesda IV as malignant, or treating every NIFTP case as cancer. Check whether your training cohorts use historical FVPTC/NIFTP conventions.

Read with [NUS Pathweb Thyroid FNA Atlas](https://medicine.nus.edu.sg/pathweb/cytopath/picture-atlas/fna-thyroid/) (particularly cases 7–9: PTC, MTC, ATC), [Papanicolaou Society Thyroid Atlas](https://www.papsociety.org/image-atlas/), and [Ohori et al. 2026](https://doi.org/10.1002/cncy.70100).
