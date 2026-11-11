# What is diagnostic thyroid lobectomy?

**Diagnostic lobectomy** (also called *diagnostic thyroid hemithyroidectomy*) is surgery to remove **one lobe of the thyroid gland**, usually with the connecting isthmus, so the nodule can be examined as an intact tissue specimen by a pathologist.

## Why would a patient need it after FNA?

Fine-needle aspiration (FNA) collects individual cells and small cell groups. For some nodules, particularly those reported as **Bethesda III (atypia of undetermined significance)** or **Bethesda IV (follicular neoplasm)**, cytology cannot reliably establish whether the nodule is benign or malignant.

**Example: follicular adenoma versus follicular carcinoma**
- Both may show similar follicular cells and microfollicular groups in FNA.
- **Follicular adenoma** is a benign neoplasm without qualifying capsular or vascular invasion.
- **Follicular carcinoma** is malignant and may be diagnosed when histology shows qualifying **capsular and/or vascular invasion**.
- An FNA sample generally does not include the entire tumor–capsule interface needed to assess invasion.
- After diagnostic lobectomy, the pathologist can sample the tumor, its capsule, and adjacent vessels to look for invasion.

This is also why **NIFTP** cannot be definitively diagnosed by FNA: strict criteria require evaluation of the excised lesion and exclusion of invasion and other disqualifying features.

## What is removed?

The thyroid has right and left lobes joined by an isthmus. In a lobectomy, the surgeon removes the affected lobe, commonly including the isthmus, while leaving the other lobe in place.

| Procedure | Extent | Typical purpose |
|---|---|---|
| **FNA biopsy** | Cells aspirated through a needle | Cytologic risk assessment |
| **Diagnostic lobectomy** | One thyroid lobe (often with isthmus) | Definitive tissue diagnosis when FNA remains indeterminate |
| **Total thyroidectomy** | Both thyroid lobes | Selected cancers or other clinical indications; not routine for every indeterminate nodule |

## What happens afterward?

1. The excised tissue is processed into thin histologic sections.
2. The pathologist examines **architecture, tumor capsule, blood vessels, nuclear features, and other criteria**.
3. The final diagnosis may be benign (e.g., follicular adenoma), low-risk (e.g., NIFTP), or malignant (e.g., follicular carcinoma or papillary thyroid carcinoma).
4. Further treatment depends on the final diagnosis and clinical risk factors. **A second surgery is not always needed**; some patients need no additional surgery.

## Does every Bethesda III or IV nodule require lobectomy?

**No.** Depending on the case, clinicians may consider repeat FNA, molecular testing, ultrasound surveillance, or surgery. The decision depends on nodule size, sonographic risk features, molecular findings, symptoms, patient history, and preferences.

Diagnostic lobectomy has risks, including bleeding, infection, voice changes from recurrent laryngeal nerve injury, and hypothyroidism requiring thyroid hormone replacement. These risks and the likelihood of additional surgery are part of shared decision-making.

## Why it matters for thyroid cytology AI

- **Bethesda label** = interpretation of cells sampled by FNA.
- **Surgical histology label** = diagnosis after examining tissue architecture and, where needed, invasion.
- **Clinical outcome** = subsequent behavior, recurrence, or other patient outcome.

These are different labels. A model trained to predict benign versus malignant *surgical histology* from FNA images must acknowledge that some decisive information (such as capsular invasion) is **not visible in the input image**. The model may identify correlates of risk, but it cannot directly observe invasion in a typical FNA field.

## Further reading
- [The 2023 Bethesda System for Reporting Thyroid Cytopathology](https://pubmed.ncbi.nlm.nih.gov/37427847/)
- [American Thyroid Association: NIFTP](https://www.thyroid.org/niftp/)
- [American Thyroid Association: Thyroid Surgery](https://www.thyroid.org/thyroid-surgery/)
- [Thyroid lesions and Bethesda associations](THYROID_LESIONS_AND_BETHESDA.md)
