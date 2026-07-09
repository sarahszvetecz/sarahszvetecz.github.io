---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a Ph.D. candidate in Computer Science at Northeastern University's Khoury College of Computer Sciences, advised by Olga Vitek. My research develops statistical and machine learning methods for drug-protein interaction modeling and drug discovery, spanning on/off target identification, target engagement, and the characterization of drug mechanism of action at proteome scale. I work across a range of data modalities, including bulk and single-cell mass spectrometry-based proteomics, bulk and single-cell RNA-seq, and pooled CRISPR screens.

One line of my work centers on **MSstatsResponse**, an open-source framework I developed for analyzing how proteomes respond to perturbation. Proteome-wide drug screens take many forms — chemoproteomics dose-response, protein turnover time-courses, phosphoproteomics, thermal proteome profiling — and while they share a common experimental logic, each has traditionally relied on its own tools built around a specific assumed curve shape. MSstatsResponse instead uses a semi-parametric approach that only assumes responses are monotonic, letting a single framework handle curve fitting, responder identification, and potency or half-life estimation across all of these assays. It's freely available as an R/Bioconductor package and usable without coding through a graphical interface, and it grew out of collaborative work with Pfizer's proteomics group.

A second line of my work moves from detecting responses to explaining them. Here I develop methods that draw on known biological networks to make sense of how a proteome responds to a drug: distinguishing the effects that follow from its intended target from those that don't, and using the unexplained ones to point toward possible off-target effects.

Before my doctoral studies, I spent three years as a data scientist in the Oncology Data Science group at the Novartis Institutes for BioMedical Research, where I analyzed large-scale multi-omics datasets to support target identification across therapeutic modalities including T-cell engagers, antibody-drug conjugates, and radioligand therapies.

That experience motivates how I approach my research today. As I develop new statistical and machine learning methods, my goal is to accelerate the messy world of drug discovery and to build models rooted in biological knowledge, creating explainable methods that the wider community can use and that hold up across the experimental and computational teams that rely on them.
