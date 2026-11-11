# 2023 Bethesda System for Reporting Thyroid Cytopathology

**Adult thyroid fine-needle aspiration (FNA).** These are **category-level** risks of malignancy (ROM), not risks for a specific histologic tumor type.

| Bethesda category | Cytology report category | Mean ROM | Expected range | Typical next-step options* |
|---|---|---:|---:|---|
| **I** | Nondiagnostic | **13%** | 5–20% | Repeat ultrasound-guided FNA |
| **II** | Benign | **4%** | 2–7% | Clinical and ultrasound follow-up |
| **III** | Atypia of undetermined significance (AUS) | **22%** | 13–30% | Repeat FNA, molecular testing, diagnostic lobectomy, or surveillance |
| **IV** | Follicular neoplasm | **30%** | 23–34% | Molecular testing or diagnostic lobectomy |
| **V** | Suspicious for malignancy | **74%** | 67–83% | Molecular testing or surgery, tailored to the case |
| **VI** | Malignant | **97%** | 97–100% | Surgery or other tumor-specific management |

*Illustrative options from Bethesda 2023, not individualized clinical recommendations. Actual management depends on ultrasound, patient history, tumor subtype, and clinical context.

**Source:** [Ali et al., The 2023 Bethesda System for Reporting Thyroid Cytopathology (2023)](https://pubmed.ncbi.nlm.nih.gov/37427847/); [original paper Table 2](https://semnro.com.ar/wp-content/uploads/thy.2023.0141.pdf); [CMS reproduction of ROM table](https://www.cms.gov/medicare-coverage-database/view/lcd.aspx?lcdid=39650).

## Interpret correctly

- **Bethesda I does not mean benign**: the specimen was insufficient for a confident diagnosis.
- **Bethesda III/IV are indeterminate**: these categories do not label a tumor as cancer.
- **Bethesda IV is not follicular carcinoma**: FNA cannot establish capsular or vascular invasion.
- **Bethesda VI is a cytology report category**: it can include very different malignant entities such as PTC, MTC, and ATC.
- **NIFTP is not a carcinoma under current classification** and requires excision histology for definitive diagnosis.
- ROM estimates are influenced by selection/verification bias because many low-risk nodules do not undergo surgery; local population risks may differ. Pediatric risks also differ.

## For AI researchers

Keep the following distinct: **FNA Bethesda label**, **surgical histology diagnosis**, **molecular subtype**, and **clinical outcome**. A model predicting Bethesda category is not automatically a model predicting histologically proven malignancy.

See [thyroid tumor types and Bethesda associations](THYROID_LESIONS_AND_BETHESDA.md) and the [visual feature dictionary](VISUAL_FEATURE_DICTIONARY.md).
