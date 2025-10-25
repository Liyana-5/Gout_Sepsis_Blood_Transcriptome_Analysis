### Overview 

This repository contains an R-based transcriptomic analysis exploring gene expression differences in blood samples from patients with gout and sepsis.
The aim of this study is to uncover molecular distinctions between these two inflammatory diseases, identify disease-specific biomarkers.
Different statistical tests were applied to test hypotheses, including Chi-square, t-test, regression (GLM models), and ANOVA.

## Hypothesis
Although both gout and sepsis involve systemic inflammation, the underlying transcriptional programs differ in immune regulation, cytokine signaling and metabolic pathways.
We hypothesize that distinct gene expression signatures in blood can effectively differentiate gout from sepsis, reflecting disease-specific immune activation patterns.

## Files
- Analysis.R — main R script used for analysis

- Sample-information.csv — contains sample metadata

- Annotations.csv — gene annotation file

- DE_GOUT_vs_HC.csv — DE table of genes between gout and healthy samples

- DE_SA_vs_HC.csv — DE table of genes between sepsis (SA) and healthy samples

## Results Summary

- Identified distinct sets of upregulated and downregulated genes between gout and sepsis.
` Observed separation of samples in PCA space, indicating transcriptional divergence.
- Findings support the hypothesis that gout and sepsis, despite shared inflammation, are driven by unique immune signatures.
and blood transcriptomics can be used to seerate between them to an extend.

## Skills Developed
- Statistical testing methods

- Differential expression (DE) analysis

- Transcriptomics data analysis

- R scripting and reproducible workflow

- Hypothesis-driven data analysis
