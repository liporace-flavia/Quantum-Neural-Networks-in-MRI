# Quantum Neural Networks in MRI: A Systematic Review – Reproducibility Materials
This repository accompanies the manuscript “Quantum Neural Networks in Magnetic Resonance Imaging: Advancing Diagnostic Precision Through Emerging Computational Paradigms”
It provides the materials required to support transparency, reproducibility and data availability..

# Overview of the study

This work explores the application of Quantum Neural Networks (QNNs) in the field of Magnetic Resonance Imaging (MRI).
By combining quantum computing with artificial intelligence, QNNs offer promising strategies for handling the high-dimensional and complex nature of MRI data. These models have the potential to improve feature extraction, accelerate optimization processes and support emerging applications in clinical imaging.

To understand the current landscape, the review systematically examined research indexed in Scopus and PubMed. From an initial set of 61 studies, 20 peer-reviewed original research articles were analyzed in depth. The review compared their datasets, architectures, hardware, tasks and performance metrics, highlighting both promising results and key limitations—including the reliance on simulators, limited quantum hardware accessibility and heterogeneous datasets.

# Contents of This Repository

This repository includes all replication artefacts required to reproduce the key quantitative components of the review.

# 1. Tables summarizing the nine-criteria evaluation

Two CSV tables are provided in the Scores folder:

- Scores_criteria_tableS1.csv
A table reporting the nine adopted evaluation criteria, their meaning and associated score.

- Scores_works_table2.csv
A table reporting the scores obtained, for each criterion and in total, for the works considered in this review.

These files ensure that readers and reviewers can directly inspect and reuse the scoring data used in the manuscript.

# 2. Code used to generate the figures

The figures_code contains the scripts or pseudocode used to create the figures presented in the manuscript. These scripts allow users to reproduce results reported in Fig. 3,4,5,6.

Any helper functions needed for loading and processing the scores

These files are intentionally lightweight to ensure reusability and clarity

# Purpose of This Repository

The goal of this repository is to provide full reproducibility by making all the artefacts publicly accessible.
Researchers can examine the scoring framework, reproduce the visualizations, or adapt the scripts for future QNN-MRI studies.

