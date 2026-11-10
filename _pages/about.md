---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I’m a Ph.D. candidate in Computer Science at Northeastern University’s Khoury College of Computer Sciences, advised by Olga Vitek. I develop statistical and machine learning methods for drug discovery, with a focus on how drugs interact with proteins: identifying on- and off-targets, measuring target engagement, and characterizing mechanism of action at proteome scale. I work with mass spectrometry-based proteomics (bulk and single-cell), RNA-seq, and pooled CRISPR screens.

Much of my Ph.D. work centers on **MSstatsResponse**, an open-source R/Bioconductor package for analyzing how proteomes respond to perturbation. Assays like chemoproteomics dose-response, protein turnover, phosphoproteomics, and thermal proteome profiling share a common experimental logic but have usually needed separate tools. MSstatsResponse handles them in one framework by assuming only that responses are monotonic. It grew out of a collaboration with Pfizer’s proteomics group and is described in a first-author paper in *Molecular & Cellular Proteomics* (2026).

I also work on **Causomic**, a causal modeling framework developed in our lab that combines biological network knowledge with Bayesian models to predict how perturbations propagate through -omics data. This includes developing benchmarks that test its ability to predict drug toxicity and the effects of genetic perturbations. More broadly, I’m interested in using multiple data modalities, such as transcriptomics, proteomics, phosphoproteomics, and spatial data, to refine dense biological networks into more accurate, context-specific ones. These networks can then be used to generate hypotheses about disease states, serve as the structure for biologically informed neural networks, and transfer across related but distinct cell states or organisms (e.g., mouse to human).

Before my Ph.D., I spent three years as a data scientist in Oncology Data Science at the Novartis Institutes for BioMedical Research. There I led a meta-analysis of T cell–cancer cell co-culture CRISPR screens, co-developed a ~2-million-cell single-cell cancer atlas, and analyzed multi-omics data to support target identification.

I also teach at short courses throughout the year on topics like statistics for chemoproteomics, PTMs, label-free, and TMT experiments. Stay tuned for YouTube recordings from the most recent May Institute (November 2026), including my lectures:

* *Differential analysis of post-translational modifications with MSstatsPTM*
* *Dose-response analysis for chemoproteomics with MSstatsResponse*

In March 2027, I’ll be teaching at the EMBL-EMBO course on quantitative proteomics in Heidelberg, Germany, leading a lecture and hands-on session: *Introduction to statistical analysis of proteomics data with MSstats*.
