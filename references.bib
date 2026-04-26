# Literature Review: TomoFair

## The Clinical Problem: Breast Cancer Burden and Racial Disparities

Breast cancer remains the second leading cause of cancer death among women in the United States, with 2.3 million new cases and 685,000 deaths globally in 2020 (Arnold et al., 2022; CDC, 2025). The burden is unevenly distributed. Black women die from breast cancer at rates roughly 42% higher than White women despite comparable screening rates over the past decade (American Cancer Society Cancer Action Network, 2025; Miles, 2020). The disparity is not explained by differential incidence, which is roughly comparable across racial groups (ACSCAN, 2025), but by stage at diagnosis, access to timely follow-up, and treatment quality (Lawson et al., 2025). In New York City specifically, the setting for TomoFair's proposed deployment, nearly 16,000 women are diagnosed annually and over 2,500 die, with screening coverage lowest among the uninsured and in medically underserved neighborhoods (Van den Bruele et al., 2022).

This disparity frames the question TomoFair exists to answer: when AI enters the screening workflow, does it close or widen the gap?

## Mammography, Density, and the Biological–Social Entanglement

Digital breast tomosynthesis (DBT), a 3D reconstruction from multi-angle X-ray imaging, has progressively replaced 2D digital mammography given its improved detection and recall-rate profile (Conant et al., 2019; Lehman et al., 2015). Fung and Ray (2021) reported that DBT performs equivalently across racial groups, making it a useful baseline against which to evaluate AI-augmented workflows, any downstream inequity introduced by an AI layer cannot be attributed to the imaging modality itself.

The clinically relevant covariate is breast density; the ratio of fibrous to fatty tissue, both elevates cancer risk and reduces mammographic sensitivity (McCarthy et al., 2016; Nayak et al., 2020). Density distributions vary across racial and ethnic groups, but within-group variation overlaps substantially with between-group variation and shifts with body composition (Moore et al., 2020). This is where the methodological difficulty begins. Race is a social construct (American Medical Association, 2020; Fischer & Bunikis, 2020), yet AI systems can reliably infer self-reported race from medical images (Gichoya et al., 2022), apparently leveraging features correlated with but not reducible to density. The result is a regime in which algorithmic outputs differ by race for reasons that are neither purely biological nor cleanly socially constructed which is precisely why measurement, rather than theoretical debate, is the research need.

## AI-Assisted Mammography: The Efficacy Case

A substantial body of literature documents efficacy gains from AI-assisted mammography. Louis et al. (2025), in the largest real-world US analysis, reported cancer detection rates approximately 21% higher under an AI-driven workflow than standard screening. Eisemann et al. (2025) found comparable gains in nationwide German implementation, and Lauritzen et al. (2024) documented improved detection, reduced false-positive rates, and higher PPV in Danish screening. Multi-reader studies (van Winkel et al., 2021), multi-vendor evaluations across 275,900 mammograms (Sharma et al., 2023), and large-scale competition benchmarks (Schaffter et al., 2020) have consistently shown AI gains across configurations — concurrent reader, independent reader, prescreening triage.

Commercial AI-CAD products are now widely deployed in screening workflows: Hologic's Genius AI Detection, iCAD, Lunit INSIGHT MMG, MammoScreen, and ScreenPoint's Transpara (Hologic, n.d.; iCAD, n.d.; Lunit, 2025; MammoScreen, n.d.; ScreenPoint Medical, 2025). Adoption is partly a response to sustained radiologist workload (Parikh & Lexa, 2026; Smith-Bindman et al., 2008). National and multinational bodies, including the UK National Screening Committee (Taylor-Phillips et al., 2022) and Korean multicenter AI-STREAM (Chang et al., 2022), have begun publishing frameworks for prospective evaluation.

The aggregate literature supports a strong efficacy signal. What it has largely not done, until recently, is disaggregate that signal by race.

## Algorithmic Bias in Medical AI: The Mechanism

Obermeyer et al. (2019) established the foundational case that clinical algorithms can encode and amplify structural inequity: their analysis of a widely deployed care-management algorithm found that Black patients were assigned systematically lower risk scores than equally sick White patients because the algorithm optimized for historical cost — which is itself a function of unequal access. The paper moved algorithmic bias in medicine from a hypothetical concern into a measurable failure mode with direct patient consequence.

In mammography specifically, Nguyen et al. (2024) provide the most directly relevant empirical evidence: a retrospective analysis of 4,855 DBT mammograms interpreted by an FDA-cleared algorithm found elevated false-positive rates in Black patients relative to White patients, with the disparity persisting after adjustment for breast density and age. Race-correlated imaging features independent of clinical covariates appear to drive differential algorithmic outputs, consistent with Gichoya et al.'s (2022) finding that deep learning models recover race from medical images across modalities, and with Lotter's (2024) demonstration that even acquisition parameters carry race-correlated signal that can be partially mitigated through targeted preprocessing.

Systematic reviews confirm the pattern at population level. Corti et al. (2022) reviewed the design and reporting of AI breast cancer treatment models and found pervasive weaknesses in cohort construction and outcome reporting. Miyawaki et al. (2025) conducted a scientometric analysis of mammography AI research and found training and evaluation cohorts globally skewed toward high-income, majority-White populations. Kundu et al. (2025) proposed subgroup bias detection frameworks specific to breast cancer AI. Stanley et al. (2026) modeled the sociotechnical consequences of deploying even well-calibrated algorithms into structurally inequitable healthcare systems, finding that upstream unfairness propagates regardless of algorithmic fairness properties.

The National Institute for Health Care Management's (2021) landscape review brings these threads together: racial bias in clinical AI is driven not by a single locus but by the compounding of unrepresentative training data, race-correlated imaging features, human–AI interaction effects, and structural inequity in the data-generating system itself. No single intervention: more diverse training data, fairer loss functions, tighter FDA review, is sufficient in isolation.

## Measurement, Drift, and the Evaluation Gap

Standard classification metrics: AUC, sensitivity, specificity, precision, false positive rate, false negative rate - form the vocabulary of AI model evaluation (Evidently AI, 2025; Iterate.ai, 2025). Equity gap analysis extends that vocabulary by computing each metric within demographic strata and reporting the magnitude of cross-strata variation as a summary statistic of fairness (Fung & Ray, 2021; Kundu et al., 2025).

A parallel methodological concern is calibration drift: divergence between training and deployment distributions over time, which degrades model performance unevenly across subgroups (Sahiner et al., 2023). Chi et al. (2022) proposed lifelong learning approaches to mitigate drift in clinical prediction models, though these remain largely outside regulatory practice.

Regulatory frameworks lag both the methodology and the evidence. The FDA's Software as a Medical Device classification (FDA, 2025a) evaluates effectiveness on the aggregate population rather than requiring stratified performance reporting. FDA guidance on demographic data collection in clinical trials (FDA, 2024) standardizes terminology without creating enforcement mechanisms. The Mammography Quality Standards Act (FDA, 2025b) sets quality standards for mammography facilities but does not extend to AI system performance auditing. HIPAA (45 C.F.R. Parts 160 & 164, 2000) constrains how demographic outcomes can be linked and reported, adding friction to retrospective equity audits. The regulatory regime thus permits an AI mammography system to receive clearance on aggregate performance while producing materially different outcomes across racial strata - the pattern Nguyen et al. (2024) documented after clearance rather than before.

## Positioning TomoFair

The literature establishes three claims. First, AI-assisted mammography improves aggregate cancer detection at scale. Second, it produces race-differentiated outputs with measurable clinical consequence. Third, current evaluation and regulatory practice does not require the disaggregated measurement that would surface those disparities prospectively. What is missing is a standardized, prospective evaluation framework that measures equity gaps across the six performance metrics most consequential to screening harm — AUC, FPR, FNR, recall, true negative rate, and precision - disaggregated across FDA-defined demographic strata and across human–AI interaction conditions.

TomoFair occupies that gap. Rather than proposing a new algorithm or a new mitigation technique, it proposes an evaluation protocol: a prospective, randomized, stratified-sampling study design that produces equity gap scores comparable across commercial vendors, deployment settings, and time periods. The contribution is methodological - a measurement instrument for a harm that is currently quantifiable only retrospectively, inconsistently, and at deployment scale.

---

# Source Taxonomy

Citations below are grouped by the role they play in the argument above. Reference numbers match the Deliverable 3 bibliography. Use this to slot in new sources, prune weak citations, or re-scope the review for a shorter or longer venue.

### Clinical burden and disparities (Section 1)

- [1] CDC (2025) — US breast cancer statistics
- [2] Arnold et al. (2022) — Global burden 2020/2040
- [3] ACSCAN (2025) — Breast cancer disparities fact sheet
- [25] Miles (2020) — Mortality gap for African American women
- [27] NCI (2025) — Screening guidelines
- [37] Van den Bruele et al. (2022) — NYC mobile mammography
- [40] Lehman et al. (2015) — Diagnostic accuracy of digital screening mammography (also Section 3)

### Mammography technology and breast density (Section 2)

- [5] Conant et al. (2019) — DBT concurrent AI accuracy/efficiency
- [14] Fung & Ray (2021) — DBT performs equivalently across racial groups
- [38] Moore et al. (2020) — Determinants of mammographic breast density by race
- [45] McCarthy et al. (2016) — Quantitative density differences by race
- [46] Nayak et al. (2020) — Supplemental imaging for dense breasts by race/ethnicity
- [42] AMA (2020) — Race as social, not biological construct
- [47] Fischer & Bunikis (2020) — Abandoning "race" as biological category in biomedical research

### Efficacy of AI-assisted mammography (Section 3)

- [6] Eisemann et al. (2025) — Nationwide AI implementation, Germany
- [9] Lawson et al. (2025) — Disparities in standard-of-care diagnostic services
- [10] van Winkel et al. (2021) — Multi-reader DBT study
- [11] Louis et al. (2025) — 21% detection rate increase, US-wide deployment
- [16] Eriksson et al. (2020) — Identifying women at high risk needing supplemental screening
- [29] Parikh & Lexa (2026) — Radiologist burnout as AI adoption driver
- [31] Schaffter et al. (2020) — JAMA Network Open AI + radiologist benchmark
- [33] Smith-Bindman et al. (2008) — Radiologist workload (adoption context)
- [41] Chang et al. (2022) — AI-STREAM Korean multicenter study
- [44] Taylor-Phillips et al. (2022) — UK NSC evidence review framework
- [49] Sharma et al. (2023) — Multi-vendor evaluation, 275,900 mammograms
- [50] Lauritzen et al. (2024) — Danish real-world implementation
- Commercial products: [18] Hologic, [19] iCAD, [23] Lunit, [24] MammoScreen, [32] ScreenPoint

### Algorithmic bias evidence and mechanisms (Section 4)

- [4] Nguyen et al. (2024) — **Core citation.** Elevated FPR in Black patients, FDA-cleared DBT algorithm
- [7] Gichoya et al. (2022) — AI recovery of race from medical images
- [8] Corti et al. (2022) — Systematic review, AI breast cancer treatment models
- [13] Obermeyer et al. (2019) — **Foundational citation.** Racial bias in care-management algorithm
- [21] Kundu et al. (2025) — Subgroup bias detection framework
- [22] Lotter (2024) — Acquisition parameters and race recovery
- [26] Miyawaki et al. (2025) — Global scientometric analysis of mammography AI equity
- [28] NIHCM (2021) — Landscape review of racial bias in clinical AI
- [51] Stanley et al. (2026) — Sociotechnical simulation of fairness vs. fair outcomes

### Measurement, drift, and evaluation methodology (Section 5)

- [17] Evidently AI (2025) — Accuracy/precision/recall definitions
- [20] Iterate.ai (2025) — AUC reference
- [30] Sahiner et al. (2023) — Data drift in medical ML
- [39] Chi et al. (2022) — Lifelong ML to mitigate calibration drift

### Regulatory and policy framework (Section 5)

- [12] FDA (2024) — Collection of race/ethnicity data in clinical trials (draft guidance)
- [35] FDA (2025a) — AI in SaMD
- [36] FDA (2025b) — MQSA
- [48] HIPAA Privacy Rule — 45 C.F.R. Parts 160 & 164

### Demographic / geographic context

- [34] US Census Bureau — NYC QuickFacts
- [15] BCSC mammography data — referenced as potential data source; not yet cited in prose

---

# Notes and gaps.
- Synthetic data augmentation, fairness-aware reweighting, post-hoc calibration
