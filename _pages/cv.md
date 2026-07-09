---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Computer Science, Khoury College of Computer Sciences, Northeastern University, 2023–Current
* M.S. in Applied Biostatistics, Boston University School of Public Health, 2020
* B.S. in Statistics, James Madison University (Honors College), 2019

Research Experience
======
* **Doctoral Researcher**, Olga Vitek Lab, Khoury College, Northeastern University (Sep 2023–Present)
  * *Project 1 — MSstatsResponse: Computational framework for proteome-wide drug target identification*
    * Built MSstatsResponse, an end-to-end computational pipeline (R/Bioconductor) for identifying drug-protein interactions from high-throughput dose-response proteomics, enabling systematic target deconvolution for small molecules
    * Designed isotonic regression-based methods that relax traditional sigmoidal assumptions, improving sensitivity for detecting non-canonical dose-response relationships in chemoproteomics screens
    * Engineered simulation-based power analysis frameworks to optimize experimental design trade-offs (replicates vs. dose levels) for proteome-wide drug target profiling
    * First-author manuscript submitted to *Molecular & Cellular Proteomics* (March 2026)
  * *Project 2 — Causal inference for distinguishing on- and off-target drug effects*
    * Developing methods that draw on known biological networks to explain how a proteome responds to a drug perturbation
    * Distinguishing effects that follow from a drug's intended target from those that do not, using the unexplained responses to point toward possible off-target effects

Industry Experience
======
* **Industry Collaboration**, Pfizer Inc. (Sep 2023–Present)
  * Collaborating with Pfizer scientists on MSstatsResponse development: a statistical framework and R/Bioconductor package for analyzing mass spectrometry-based chemoproteomics dose-response experiments, including hypothesis testing, IC50 estimation, and experimental design optimization
  * Developing analysis workflows and interactive tools for novel protein turnover datasets from labeling-based proteomics experiments

* **Expert I Data Scientist** (Mar 2022–Jul 2023) / **Research Scientist II** (Jun 2020–Mar 2022), Oncology Data Science, Novartis Institutes for BioMedical Research
  * Led CRISPR screening initiatives including pooled T-cell + cancer cell co-culture screens to identify genes regulating immune-mediated tumor killing, applying statistical models for hit detection
  * Developed a computational framework integrating CRISPR knockout dependency data with protein degradability metrics (structural features, proteomics hits, literature evidence) to prioritize targets for targeted protein degradation programs
  * Conducted surfaceome analysis and multi-omics profiling (RNA-seq, scRNA-seq, CITE-seq, spatial transcriptomics) to identify and validate cell surface targets for antibody-based therapeutics including T-cell engagers, antibody-drug conjugates, and radioligand therapies

Skills
======
* **Machine learning & deep learning**: PyTorch, PyTorch Geometric, graph neural networks, pre-trained protein sequence embeddings (ProtT5), 1D CNNs for sequence embedding, causal graph neural networks, LLM fine-tuning (Hugging Face Transformers)
* **Molecular & protein modeling**: RDKit, SMILES-based molecular graph representations, protein sequence embedding, causal biological network construction (INDRA API), NetworkX
* **Scientific computing & data analysis**: NumPy, SciPy, Pandas, scikit-learn, R/Bioconductor package development
* **Biological data analysis**: Mass spectrometry-based proteomics, chemoproteomics, dose-response experiments, single-cell RNA-seq, bulk RNA-seq, pooled CRISPR screens
* **Programming**: Python, R, SQL, Linux

Selected Publications
======
* Szvetecz S, Kohler D, et al. MSstatsResponse: semi-parametric statistical model enhances detection of drug-protein interactions in chemoproteomics experiments. *Submitted, Molecular and Cellular Proteomics*, March 2026.
* Xu Y, Billy E, Dai W, German R, Szvetecz S, et al. Unveiling Human Cancer Cell Intrinsic Pathways Impacting T Cell Recognition and Killing via Genome-Wide CRISPR Screening. *Under review, Nature Communications*, October 2025.
* Lee E, Szvetecz S, et al. PAX8 lineage-driven T cell engaging antibody for the treatment of high-grade serous ovarian cancer. *Sci Rep* 2021;11(1):14841.

Selected Presentations
======
* Szvetecz S, et al. Proteome-wide drug perturbation screens motivate new statistical frameworks for downstream analysis. Abstract submitted, JSM Conference, August 2026.
* Szvetecz S, et al. MSstatsResponse: Semi-parametric statistical model enhances drug-protein interaction detection and IC50 estimation in chemoproteomics experiments. Poster, ASBMB International Symposium on Proteomics in the Life Sciences, August 2025.
* Szvetecz S, et al. Optimal experimental design and semi-parametric methods improve detection accuracy for drug-protein interactions in chemoproteomics. Poster, ASMS Annual Conference, June 2025.
* Szvetecz S, et al. Evaluating statistical methods and experimental designs for chemoproteomics experiments. Poster, ASMS Annual Conference, June 2024.

Teaching and Mentoring
======
* Instructor, EMBL-EMBO Short Course: Quantitative Proteomics, Heidelberg, Germany, March 2025
* Research Mentor, Khoury Research Apprenticeship Program, Northeastern University, January 2026–Present
* Teaching Assistant, Statistical Methods for Computer Science, Northeastern University, Fall 2024
* Summer Intern Mentor, Novartis Institutes for BioMedical Research, Summer 2023

Awards and Honors
======
* Khoury Distinguished Fellowship, Northeastern University, 2023–2024 — competitive 1-year fellowship ($60k) awarded to top incoming PhD students
