---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# About me

I am a PhD student in Computational Biology at the [Center for Computational Molecular Biology at Brown](https://ccmb.brown.edu) advised by 
[Lorin Crawford, Ph.D.](http://www.lcrawlab.com/) and [Jeffrey Bailey, Ph.D, MD](https://baileylab.org/). My research interests are broadly 
at the **intersection of computational modeling, computer science, statistics, and biology**.  Specifically, I am interested in 
**developing and applying machine learning, deep learning and statistical methods to interpret complex and high-dimensional biological data** to drive innovations in biomedical research.My work emphasizes building scalable models to analyze complex omics and electronic health record data, with applications in cancer evolution, drug resistance, rare diseases and infectious disease. 

Collaborating alongside leading experts, I contribute to impactful research combining AI with real-world genomics datasets, enabling actionable insights for public health and biotechnology. With over four years of experience in computational biology, I am committed to advancing data-driven discovery in precision medicine and translational science.


--- 
# Key research projects

## Bayesian Mixed-Effects Modeling for Drug-Resistance Forecasting
Built a scalable, interpretable Bayesian modeling pipeline to estimate and predict the spatial spread and selection of drug-resistance mutations using genomic surveillance data collected across regions and time. The framework leverages partial pooling and hierarchical structure to handle sparse and noisy observations while producing calibrated uncertainty estimates suitable for downstream decision support.

The project emphasizes model transparency and interpretability, enabling stakeholders to understand mutation-specific drivers, regional heterogeneity, and forecast uncertainty rather than relying on black-box predictions. Development was carried out in close collaboration with biologists and public-health researchers, ensuring that model assumptions aligned with domain knowledge and that outputs were actionable in real-world monitoring workflows.

Find more information in the [published paper in Lancet Microbe](https://www.thelancet.com/journals/lanmic/article/PIIS2666-5247(24)00295-7/fulltext) or implement our method with our [code](https://github.com/bailey-lab/selmar).

## A Statistical and Machine Learning Approach to Investigating Unmapped Regions of the Malaria Parasite Genome
While the malaria parasite's genome (*Plasmodium falciparum*) shows limited overall genetic variation, much of it is concentrated in highly dynamic subtelomeric regions. These regions encode genes that help the parasite evade human immunity, making them crucial for its survival. I am developing an AI-driven framework that leverages statistical methods and Variational Autoencoders to analyze these challenging genomic regions. This approach aims to uncover their role in shaping parasite population structure and identify shared genetic variants across populations. Insights from this research could improve our understanding of malaria progression and guide the development of novel drug targets.

## A Mathematical Approach to Understanding the Role of Human Mobility in the Spread of Antimalarial Drug Resistance
Resistance to Artemisinin Combination Therapies (ACTs) is spreading in malaria-endemic regions, driven by parasites with K13 mutations. I am developing a Bayesian model to estimate the movement of ACT-resistant infections between regions via humans and mosquitoes. By integrating mutation prevalence and selection dynamics, this work identifies high-risk regions and predicts how resistance spreads via mobility. These insights will guide public health strategies to combat drug-resistant malaria and improve global intervention efforts.

## Pancancer evolutionary model analyzing scRNAseq data
While at Dana-Farber, I developed an evolutionary modeling framework aimed at characterizing the progression of cancer across various tumor types. This project focused on analyzing copy number variations from single-cell RNA sequencing data to estimate distinct evolutionary modes in tumors. By applying machine learning techniques, the model identified patterns of clonal evolution and adaptive mechanisms used by cancer cells, providing valuable insights into tumor heterogeneity. The findings contributed to a better understanding of how tumors evolve over time and respond to different treatment pressures.

