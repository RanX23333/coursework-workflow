# AIP CW1 case

This anonymised case describes a machine-learning coursework workflow reconstructed from project records, the related coursework chat context, and the final review conversation. The student reported submission on 18 November 2026. It provides examples for adapting the workflow to another course.

## Resource intake and learning

The project contained the official brief, rubric, cover, three datasets, lecture slides, and labs. The initial local records documented existing downloaded files and their organisation. Platform download and update-check steps belong to the reusable workflow when actually requested and performed.

A requirement checklist mapped the subquestions to marks and deliverables. Course material supplied logistic regression and gradient descent, Gaussian kernels, model selection, and task-specific methods. The student wanted short Chinese explanations with each major question and its subquestions together. English was used for the submission.

## Implementation and evidence

- Q1 used training-only geometry exploration, a simple radial representation, model formulation and loss, cross-validation, fitted coefficients and decision boundaries, and test-error localisation.
- Q2 compared an imbalanced classifier with moderated class weighting and threshold controls. The same weighting idea was adapted to linear regression over a training-defined rare-price region. The report discussed improvements and costs across regions.
- Q3 fitted a continuous kernel surface and searched for its minimum. Investigation covered kernel parameters, stability, gradients, optimiser comparisons, starting points, spatial validation, and local measurement support.

These choices satisfied the source assignment. New coursework should derive its own models, parameters, validation, and evidence from its requirements and data.

## Report and revision

The workflow moved from executed notebooks and result files to report text, figures, tables, citations, and a rendered PDF. External review suggested changes which were checked against current evidence.

Observed lessons included the following.

- Locate the exact feedback file before claiming it includes or omits a priority.
- Recount admissible parameter combinations from results. One external review's count required correction.
- Show a table's selection scope when it contains a subset of candidates.
- Distinguish solver success flags from a shared projected-gradient tolerance.
- Run tuning before a fixed-selected-parameter feature comparison so execution order explains parameter provenance.
- Remove statements describing experiments absent from the implementation.
- Reconcile the current report, cover word count, README, packaged files, and verification records after revisions.
- Review AI-use wording against actual project assistance and applicable course context.

## Final verification

The final audit read the complete brief and rubric, including rotated rubric tables. The archive contained a report and three executed notebooks. Isolated clean runs completed all 37 code cells. Independent checks recalculated classification metrics, regional regression errors, and evidence supporting the estimated minimum. Saved notebook images and report image assets matched the regenerated sources. All ten report pages were inspected, and the section-specific word limit was checked with expanded citations.

The broader lesson is to audit the exact archive intended for submission with checks that fit its artifacts. The source assignment's ten-page limit, question count, file count, seed, models, colors, and numerical results are case details.
