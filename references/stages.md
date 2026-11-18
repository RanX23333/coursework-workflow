# Stage guide

Use the stages relevant to the student's current request. Existing coursework can enter at implementation, review, or final audit.

## 1. Collect and identify resources

Inventory the brief, rubric, announcements, cover, datasets, starter files, submission instructions, lectures, labs, and handbook. Record filenames, versions, and source locations. Keep original files recoverable and distinguish original material from derived text or working copies.

When the student requests platform downloads, use the connected course service or authenticated browser. If an applicable course-platform skill is available, read its instructions before using it. Record what was actually downloaded and when. A local inventory establishes which files are present. A fresh platform check establishes what is currently available online.

For a new project, use an arrangement such as originals, requirements/progress, work/results, learning notes, and submission. Reuse equivalent existing folders. The output is a navigable project with identified sources and a clear next action.

## 2. Decompose the brief and rubric

Turn verbs such as explore, justify, compare, implement, investigate, and discuss into evidence obligations. Record the subquestion weights and deliverable constraints. Include procedural requirements such as keeping the algorithm, features, preprocessing, and split fixed for a comparison.

Tie each rubric criterion to a location in the planned artifact. An experimental report may need model formulation, loss, fitted model, validation protocol, metrics, error analysis, figures, and limitations. A database assignment may instead need a schema, queries, constraints, and demonstrations.

Expose material source conflicts early. Preserve source attribution for written rules, teacher announcements, and student-reported clarification. Use explicit uncertainty when a conflict remains unresolved.

## 3. Map course knowledge and teach

Search lecture and lab titles and content, then inspect the relevant pages or cells. Record file/page references with the concept and its use in the solution. Distinguish a method introduced in class from an extension that combines classroom ideas with additional techniques.

Build only the learning notes requested by the student. A useful question-level tutorial contains the question, a clear explanation of the task, a few necessary concepts, the implementation approach, key code, and how to read the output. Screenshots and examples should help the learner resolve a concrete difficulty.

The student's demonstrated understanding or explicit confirmation determines the understanding status. Executed code establishes execution status.

## 4. Develop and run each part

Start with data quality and the task's comparison conditions. Use transparent baselines and explain methodological choices. Prefer methods that satisfy the assignment with proportionate complexity. Choose evaluation metrics for the task and target distribution.

For machine-learning coursework, consider these invariants when they apply.

- Fit preprocessing and training-derived thresholds inside each fitting fold.
- Keep feature construction and model selection compatible with the validation protocol.
- Select weights and decision thresholds with training evidence, and identify exploratory comparisons if development involved prior test inspection.
- Apply training-defined evaluation regions consistently to the test set.
- Use controls to distinguish combined changes such as loss weighting and threshold adjustment.
- Match explanations of fitted losses, kernels, gradients, decision rules, and parameter conversion to the code.
- Inspect numerical stability and solver residuals when they matter. Report solver status and an independent convergence criterion with their own meanings.

Run the complete current implementation in its intended environment. Record versions, data placement, randomness, outputs, and failures as relevant. Generate tables, figures, and metrics from the run. Each completed subquestion should have enough evidence for its report passage.

## 5. Assemble the report

Follow the brief's language, structure, formatting, references, and page/word constraints. Write from actual outputs with consistent rounding. Link each main figure and table to a discussion in the text. Justify choices and interpret trade-offs with the evidence available.

Use relevant primary sources for academic claims and verify bibliographic details. Keep scientific limitations specific to the result. State sampling gaps, validation scope, or conditional uncertainty where these change the interpretation.

For a word count, define the counting convention and treat local section limits separately. Confirm the official cover and any consent fields from the student's instructions. Render the actual final PDF and inspect every page for readability, clipping, overlaps, broken references, tables, legends, formulas, and page transitions.

## 6. Integrate feedback

Read the exact review document, identify its target artifact version, and retain its priority order when requested. Verify claims against code, current outputs, and the official requirements. Record the proposed action and its reason, including suggestions that require a new experiment.

An evaluator may miscount parameter candidates or infer a solver termination cause from insufficient evidence. Recompute the available evidence before adopting a numerical or causal claim. Treat predicted grades as reviewer estimates.

Fix confirmed issues within the authorised scope, then rerun affected computations or rendering. Keep numeric artifacts and report assets synchronised. Preserve the user's chosen incremental review workflow when one is active.

## 7. Audit the actual submission

Check all relevant requirements and artifacts, including the following for notebook/report submissions.

1. Extract the candidate archive and verify its exact file set.
2. Place the supplied data using the documented portable layout.
3. Clear notebook outputs in isolated copies and execute all cells in fresh kernels.
4. Check execution counts, errors, relevant warnings, and saved numerical and image outputs.
5. Recalculate important metrics from predictions and original labels when this adds independent assurance.
6. Compare report values with generated results and rounding conventions.
7. Match report images to their generated sources. Pixel comparison is appropriate when exact visual identity is expected.
8. Inspect every final rendered page and check length limits, local word limits, cover fields, references, and figure/table callouts.
9. Verify archive integrity and equality between its contents and the final reviewed files.

Keep verification records alongside the submission workspace when needed. The official archive should contain the files required or allowed by the brief. Update verification scope after later edits, and rerun checks affected by those edits.

## 8. Handoff and submission record

Give the student one clearly identified final archive or other requested deliverable. State material verification limits. Record platform submission only after observing a successful submission or receiving the student's report that it was submitted.

If the student requests distillation into a reusable public skill, extract methods and decision rules. Prepare a deliberate publishable file set and inspect it for student identifiers, private paths, credentials, course-owned materials, and assessment answers before publishing.
