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
* Ph.D. in Computer Science, Khoury College of Computer Sciences, Northeastern University, 2023–Present (Advisor: Olga Vitek)
* M.S. in Applied Biostatistics, Boston University School of Public Health, 2020
* B.S. in Statistics, James Madison University (Honors College), 2019

Research Experience
======
* **Doctoral Researcher**, Olga Vitek Lab, Khoury College, Northeastern University (Sep 2023–Present)
  * *Causal AI for drug response and mechanism of action* (ongoing collaboration with AstraZeneca)
    * Leading development of **Causomic**, a Python package that combines prior knowledge networks (INDRA) with Bayesian structural causal models in Pyro to predict how drug and genetic perturbations propagate through -omics data, with uncertainty
    * Applying the framework to compound-induced hepatotoxicity and Perturb-seq genetic screens, and to drug repurposing and off-target case studies that explain the mechanisms behind toxicity and drug resistance
    * Extending it to integrate multi-omics perturbation data (proteomics, phosphoproteomics, transcriptomics, chemoproteomics) with chemical structure (SMILES-based graph embeddings), and studying how well predictions transport across cell systems (HepG2 cells and primary human hepatocytes)
  * *MSstatsResponse: Statistical methods for proteome-wide drug target identification* (collaboration with Pfizer)
    * Built MSstatsResponse, a semi-parametric framework and R/Bioconductor package for identifying drug-protein interactions from dose-response chemoproteomics
    * Designed isotonic regression-based methods that relax traditional sigmoidal assumptions, increasing sensitivity while maintaining specificity, especially for partial or non-canonical response shapes, outliers, and low-dose designs
    * Built simulation-based experimental design tools for weighing dose coverage against biological replication, showing that replication often matters more for target detection
    * First-author paper published in *Molecular & Cellular Proteomics* (2026); the package is integrated with the MSstats ecosystem and used in a collaborative dose-response phosphoproteomics study (bioRxiv 2026)
  * *A unified statistical framework for ordinal (chemo)proteomics experiments* (manuscript in preparation)
    * Unimodal isotonic regression to detect hook effects, common in PROTAC dose-response experiments
    * Protein turnover curves over time to classify long- and short-lived proteins (Pfizer collaboration)
    * Thermal proteome profiling, to detect drug-induced shifts in protein melting curves

Industry Experience
======
* **Expert I Data Scientist** (2022–2023) / **Research Scientist II** (2020–2022), Oncology Data Science, Novartis Institutes for BioMedical Research (Jun 2020–Jul 2023)
  * Lead data scientist for the meta-analysis of all internal T cell–cancer cell co-culture pooled CRISPR screens, spanning six cancer lineages, to identify genes regulating immune-mediated tumor killing
  * Co-developed an internal single-cell cancer atlas of ~2 million cells from 26 public scRNA-seq datasets across 10 cancer indications, with scVI batch integration, cell type annotation, and cellxgene browsers for oncology collaborators
  * Led the pancreatic cancer analysis within a group-wide surfaceome project, ranking cell surface targets for radioligand, T-cell engager, and antibody-drug conjugate programs
  * Nominated targets for CRBN molecular glue degraders by integrating CRISPR dependency data with structural and literature evidence of degradability
  * Organized and led a molecular subtyping working group that evaluated published methods for classifying bulk RNA-seq tumor samples into cancer-specific subtypes, and released a shared annotation framework and code tutorials

Earlier Research
======
* **Master's Research Rotation**, Boston University, 2020: Random forest selection of T cell measurements predictive of alcohol abuse in HIV+ patients (Advisor: Prasad Patil)
* **Master's Research Rotation**, Boston University, 2019–2020: Demographic differences in TCGA head and neck cancer transcriptomes (Advisor: Stefano Monti)
* **Undergraduate Honors Thesis**, James Madison University, 2018–2019: Combining chicken retina RNA-seq data across studies to strengthen biomarker detection (Advisor: Nusrat Jahan)
* **QSURE Fellow**, Memorial Sloan Kettering Cancer Center, Summer 2018: Exploring handling effects in microarray data using statistical methods (Mentor: Jaya M. Satagopan)

Skills
======
* **Omics data**: Mass spectrometry-based proteomics (DIA, TMT, chemoproteomics, thermal proteome profiling, protein turnover, post-translational modifications, single-cell), bulk RNA-seq, scRNA-seq, pooled CRISPR screens, CITE-seq, spatial transcriptomics
* **Statistical methods**: Isotonic and unimodal regression, mixed-effects models, bootstrap inference, Bayesian causal modeling, simulation-based power analysis and experimental design
* **Machine learning & deep learning**: PyTorch, PyTorch Geometric, graph neural networks, causal graph neural networks, pre-trained protein sequence embeddings (ProtT5), 1D CNNs, LLM fine-tuning (Hugging Face Transformers), scikit-learn
* **Molecular & network modeling**: RDKit, SMILES-based molecular graph representations, causal biological network construction (INDRA API), NetworkX, Neo4j, OmniPath, STRING
* **Programming**: Python (NumPy, SciPy, pandas, Pyro), R (Bioconductor package development, Shiny, lme4), SQL, Linux, Git

Selected Publications
======
* **Szvetecz S**, Kohler D, Federspiel JD, Field SD, Jean-Beltran P, Seward RJ, Suh H, Xue L, Vitek O. MSstatsResponse: Semi-parametric statistical model enhances detection of drug-protein interactions in chemoproteomics experiments. *Molecular & Cellular Proteomics* 2026;25(9):101637.
* Brademan DR, Mullarkey AA, Greeson ML, **Szvetecz S**, Vitek O, Blythe EE, Hüttenhain R. Systematic optimization and benchmarking of synchro-PASEF for high-throughput phosphoproteome profiling. *bioRxiv* 2026.06.26.734570.
* Xu Y, Billy E, Dai W, German R, **Szvetecz S**, et al. Unveiling human cancer cell intrinsic pathways impacting T cell recognition and killing via genome-wide CRISPR screening. *Under review, Nature Communications*.
* **Szvetecz S**, Boekweg H, Kohler D, Kaneda G, Zilberg L, Song Y, Mastali M, Kreimer S, Haghani A, Parker S, Payne SH, Vitek O. Statistical design and analysis of single-cell proteomic experiments increase the accuracy of differential analysis. *In preparation*.
* Lee E, **Szvetecz S**, et al. PAX8 lineage-driven T cell engaging antibody for the treatment of high-grade serous ovarian cancer. *Sci Rep* 2021;11(1):14841.

Selected Presentations
======
* Szvetecz S, et al. Evaluating differential analysis approaches for single-cell proteomics data with MSstats. Poster, European Symposium on Single-Cell Proteomics, September 2026.
* Szvetecz S, et al. Proteome-wide drug perturbation screens motivate new statistical frameworks for downstream analysis. Oral presentation, Joint Statistical Meetings (JSM), August 2026.
* Szvetecz S, et al. MSstatsResponse: Semi-parametric statistical model enhances drug-protein interaction detection and IC50 estimation in chemoproteomics experiments. Poster, ASBMB International Symposium on Proteomics in the Life Sciences, August 2025.
* Szvetecz S, et al. Optimal experimental design and semi-parametric methods improve detection accuracy for drug-protein interactions in chemoproteomics. Poster, ASMS Annual Conference, June 2025.
* Szvetecz S, et al. Evaluating statistical methods and experimental designs for chemoproteomics experiments. Poster, ASMS Annual Conference, June 2024.

Teaching and Mentoring
======
* Instructor, May Institute Short Course: PTMs & Chemoproteomics, November 2026 (lectures on MSstatsPTM and MSstatsResponse)
* Instructor, May Institute Short Course: Statistics for Quantitative Mass Spectrometry, May 2025 and May 2026
* Instructor, EMBL-EMBO Short Course: Quantitative Proteomics, Heidelberg, Germany, 2025 and 2027 (lecture and hands-on session on MSstats)
* Workstream Lead, Cell Type Annotation, scverse × Single-Cell Proteomics Hackathon, Vienna, September 2026
* Research Mentor, Khoury Research Apprenticeship Program, Northeastern University, Spring 2026 (two master's students: cross-dataset harmonization of cancer proteomics; cell type deconvolution of bulk proteomics)
* Teaching Assistant, Statistical Methods for Computer Science (PhD level), Northeastern University, Fall 2024
* Summer Intern Mentor, Novartis Summer of Science Internship Program, 2023 (DepMap CRISPR screen analysis)
* Research Project Mentor, Novartis Data Science Mentoring Program, 2022–2023
* STEM Club Mentor, Novartis, 2021 and 2022

Service
======
* Peer reviewer: *Bioinformatics*, *Molecular & Cellular Proteomics*, *Journal of Proteome Research*

Awards and Honors
======
* Khoury Distinguished Fellowship, Northeastern University, 2023–2024: competitive 1-year fellowship ($60k) awarded to top incoming PhD students
* Merit Scholarship, Boston University, 2019–2020
* Undergraduate Research Award, James Madison University, 2019
* Frances Hughes Pitts Memorial Scholarship, James Madison University, 2018–2019: awarded annually to one female JMU student in STEM
* Mathematics Department Scholarship, James Madison University, 2018–2019
