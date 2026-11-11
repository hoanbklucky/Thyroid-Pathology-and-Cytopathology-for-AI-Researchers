# Visual feature dictionary for thyroid FNA AI

A morphology-first reference for **what is actually visible in cytology**. The entries describe typical patterns, not necessary/sufficient diagnostic criteria. No atlas images are copied here; use linked source pages to inspect examples. For education and research design, not independent diagnosis.

## How to read the dictionary

- **Architecture in FNA** means *cell-group arrangement* (sheets, microfollicles, papillary fragments), **not** intact histologic architecture or capsule invasion.
- **Nuclear features** should be described individually (size, shape, chromatin, contour, grooves, pseudoinclusions).
- **Background clues** (colloid, lymphocytes, amyloid-like material, necrosis) may be informative but vary by sampling and preparation.
- **Bethesda associations** are illustrative, **not** a deterministic mapping between tumor entity and cytology category.
- A negative finding in a limited field of view is **not** proof of absence from the nodule.

## Visual feature dictionary

| Entity or pattern | FNA cell arrangement | Nuclear/cellular clues | Background / other clues | Possible Bethesda | Important limitation |
|---|---|---|---|---|---|
| Colloid / hyperplastic follicular nodule | Flat honeycomb sheets; variable macrofollicular groups | Relatively uniform round nuclei, bland chromatin | Often abundant thin colloid | II, sometimes I | Sparse or cystic aspirates can be nondiagnostic |
| Hashimoto / lymphocytic thyroiditis | Follicular cells mixed with lymphocytes; oncocytic groups | Oncocytic (Hürthle) cells may show abundant granular cytoplasm | Many lymphocytes; variable colloid | II, sometimes III | Reactive atypia may resemble neoplasm |
| Follicular adenoma | Microfollicles, crowded 3D groups, or mixed patterns | Generally monotonous follicular nuclei | Often relatively scant colloid | III–IV, sometimes II | FNA cannot distinguish adenoma from carcinoma by invasion |
| Follicular thyroid carcinoma | Similar to follicular adenoma | Often bland, relatively uniform follicular nuclei | Often scant colloid | III–IV, sometimes V | **Capsular/vascular invasion requires histology** |
| Oncocytic (Hürthle-cell) neoplasm | Cellular groups of oncocytes | Abundant granular eosinophilic cytoplasm, prominent nucleoli | Often scant colloid | III–IV | Oncocytic change also occurs in thyroiditis; adenoma/carcinoma distinction requires histology |
| NIFTP | Follicular/microfollicular groups | Mild or focal papillary-like nuclear changes; usually less conspicuous than classic PTC | Variable colloid | III–V | **Cannot be definitively diagnosed by FNA**; requires strict histologic criteria |
| Classical papillary thyroid carcinoma (PTC) | Papillary tissue fragments or syncytial sheets; sometimes crowded groups | Enlarged/elongated overlapping nuclei, pale chromatin, grooves, intranuclear cytoplasmic pseudoinclusions | May show psammoma bodies, dense/ropy colloid | V–VI; occasionally III | Not all features occur in every sample |
| Follicular-patterned PTC | Follicular groups rather than conspicuous papillae | Papillary-type nuclear changes, sometimes subtle | Variable colloid | III–VI | Invasion and encapsulation cannot be assessed reliably by FNA |
| Medullary thyroid carcinoma (MTC) | Dispersed cells, loose groups; plasmacytoid or spindle cells | Eccentric nuclei; neuroendocrine 'salt-and-pepper' chromatin; sometimes binucleation | Amyloid-like material may occur | V–VI; occasionally III–IV | Confirm using calcitonin/other ancillary testing as appropriate |
| Poorly differentiated thyroid carcinoma | Often dispersed or cohesive crowded groups | Higher nuclear-to-cytoplasmic ratios, atypia; variable mitotic activity | Necrosis may be present | V–VI, sometimes indeterminate | Architectural/mitotic criteria may require histology |
| Anaplastic thyroid carcinoma (ATC) | Dispersed pleomorphic malignant cells; spindle/giant cells | Marked pleomorphism, coarse chromatin, prominent nucleoli, atypical mitoses | Often necrotic/inflammatory background | V–VI, often VI | Differential includes other high-grade malignancies; immunophenotyping may be needed |
| Thyroid lymphoma | Dispersed atypical lymphoid population | Lymphoid morphology rather than follicular epithelial features | Lymphoglandular bodies may be present | Variable, often V–VI | Not a thyroid carcinoma; flow cytometry may be needed |

## Feature glossary: operational definitions for image annotation

| Feature | What to annotate | Common pitfalls |
|---|---|---|
| Honeycomb sheet | Flat, cohesive cells with evenly spaced nuclei | Folds can look three-dimensional |
| Microfollicle | Small ring/rosette of follicular cells around a tiny lumen | Overlapping cells may mimic lumens |
| Papillary fragment | Branching cell group, ideally with a fibrovascular core | FNA fragments do not prove the tumor's overall growth pattern |
| Nuclear enlargement | Relative increase in nuclear area vs nearby comparable cells | Magnification and staining affect measurements |
| Nuclear elongation | Oval/elongated rather than round nuclei | Smear artifact can elongate nuclei |
| Nuclear groove | Linear infolding of nuclear membrane | Can occur in benign/reactive cells |
| Intranuclear cytoplasmic pseudoinclusion | Well-defined cytoplasm-like inclusion within nuclear outline | Not the same as a groove; can be confused with artifacts |
| Chromatin clearing | Pale, finely dispersed chromatin | Stain/preparation dependent |
| Nuclear overlap/crowding | Nuclei touch or superimpose in groups | Thickness of smear matters |
| Colloid | Extracellular thyroid follicular protein material | Viscosity/appearance varies by preparation |
| Psammoma body | Concentric calcified spherule | Not specific without context |
| Amyloid-like material | Amorphous extracellular material that may accompany MTC | Confirmation may need special stains |
| Necrosis | Degenerative cellular debris | Sampling and fixation artifacts can mimic |

## Suggested research annotation schema

`image_id, patient_id, site, stain, preparation, magnification, image_quality, cell_group_pattern, nuclear_size, nuclear_shape, nuclear_overlap, chromatin, grooves, pseudoinclusions, colloid, lymphocytes, necrosis, possible_amyloid, feature_confidence, artifact_flag, bethesda_label, histology_label, label_source, reviewer_id`

Use **not assessable** for a feature obscured by blur, stain, overlap, or insufficient cells. Never encode 'not visible' as 'biologically absent'. Have a cytopathologist validate a subset of feature annotations and assess inter-rater agreement.

## Practice sequence
1. Open [NUS Pathweb FNA thyroid atlas](https://medicine.nus.edu.sg/pathweb/cytopath/picture-atlas/fna-thyroid/) and describe the first benign case without looking at the diagnosis.
2. Compare follicular neoplasm and PTC examples; explicitly separate **cell grouping** from **nuclear morphology**.
3. Compare PTC, MTC, and ATC cases. Which features are potentially resolvable in a smartphone image?
4. Read [Ohori et al. (2026)](https://doi.org/10.1002/cncy.70100), especially its classical-papillary versus papillary-like nuclear comparison.
5. Write down what **cannot** be inferred from FNA: invasion, definitive NIFTP, and many prognostic claims.

## Sources
- [NUS Pathweb thyroid FNA atlas](https://medicine.nus.edu.sg/pathweb/cytopath/picture-atlas/fna-thyroid/)
- [Papanicolaou Society image atlas](https://www.papsociety.org/atlas/)
- [The 2023 Bethesda System for Reporting Thyroid Cytopathology](https://pubmed.ncbi.nlm.nih.gov/37427847/)
- [Bethesda 2023 overview](https://pubmed.ncbi.nlm.nih.gov/37438235/)
- [Ohori et al. 2026](https://doi.org/10.1002/cncy.70100)
