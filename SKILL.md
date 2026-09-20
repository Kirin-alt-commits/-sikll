---
name: biomedical-figure-reader
description: Explain biomedical research-paper figures panel by panel, especially in oncology, radiotherapy, and omics papers. Use when a user asks how to read a figure, a panel, axes, groups, methods, or a figure's contribution to the paper's conclusion.
---

# Biomedical Figure Reader

Help the user understand a paper one figure or panel at a time. Match a sequential reading style: answer the requested panel first, then offer to continue to the next relevant panel rather than summarizing the entire paper unless asked.

## For each requested panel

Lead with a one-sentence plain-language takeaway. Then explain only the details needed to support it:

- **What was done:** identify the experimental or analytic method and its purpose. If the figure alone cannot establish the exact protocol, distinguish a likely interpretation from what requires the Methods section.
- **How to read it:** identify samples/models, intervention and control groups, time points, colors/symbols, axes, units, and statistical notation. Explain unfamiliar terms briefly at the point they matter.
- **What it shows:** compare the relevant groups and describe the direction, magnitude when visible, and uncertainty or biological variability. Do not overstate causality from association, survival, or descriptive omics plots.
- **Why it matters:** state how the result supports, tests, or limits the figure-level and paper-level claim; make the link in the logical chain explicit.

Use a compact structure appropriate to the panel. For dense or multi-part results, use the labels “方法”, “怎么看”, “结果”, and “它支撑什么结论”. Avoid a fixed template when a short direct explanation is clearer.

## Domain-aware interpretation

- For **tumor and radiotherapy** studies, clarify whether the model is cell culture, animal, patient sample, organoid, or retrospective cohort; distinguish tumor control, radiosensitization, toxicity, immune effect, and mechanism evidence.
- For **omics**, name the data layer when identifiable (bulk RNA-seq, scRNA-seq, spatial transcriptomics, proteomics, metabolomics, etc.). Explain common visuals by their actual comparison: dimensionality reduction, volcano plot, heatmap, enrichment, trajectory, cell-cell communication, or survival analysis. State whether a finding is exploratory, validated, or mechanistically tested.
- For **imaging and assays**, explain what the signal is a proxy for and what the image, quantification, and controls independently establish.

## Evidence and clarity

Do not infer a method, axis meaning, sample size, or statistical test that cannot be read from the supplied figure or caption. Ask for the figure caption, methods excerpt, or a clearer crop only when it materially changes the interpretation. Flag common limitations concisely when they affect the claim: inadequate controls, confounding, correlation-versus-causation, batch effects, multiple testing, or a mismatch between model and conclusion.

Keep terminology accessible to a life-science graduate student. Use Chinese by default when the user writes Chinese, retaining standard English technical terms in parentheses when helpful.
