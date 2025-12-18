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

I am a PhD candidate in Computational Biology at the [Center for Computational Molecular Biology at Brown](https://ccmb.brown.edu), specializing in the development of artificial intelligence (AI) models for complex biomedical data. My work focuses on integrating high-dimensional omics and clinical data to address real-world problems such as drug resistance, cancer evolution, and infectious disease dynamics. I collaborate closely with domain experts to translate biological questions into robust AI systems that produce actionable insights for biotechnology and public-health applications. 

## Education
I have over seven years of research training, advised by:
- Dr. Lorin Crawford ([Microsoft Research](http://www.lcrawlab.com/) and Brown University)
- Dr. Jeffrey Bailey ([Center for Computational Biology, Brown University](https://baileylab.org/)).
- Dr. Ashley Conard ([Microsoft Research](https://www.microsoft.com/en-us/research/people/ashleyconard/))
- Dr. Mary L. Gray ([Microsoft Research](https://marylgray.org/))
- Dr. Franziska Michor ([Department of Data Science, Dana-Farber Cancer Institute](http://michorlab.dfci.harvard.edu/))
- Dr. Simona Cristea ([Department of Data Science, Dana-Farber Cancer Institute](https://labs.dana-farber.org/aguirrelab/people/simona-cristea-phd))

I graduated from Boston University's College of Engineering with a Bachelor of Science in Biomedical Engineering in 2022 and a concentration in machine learning. There, my senior thesis was awarded the "Societal Impact Award". I started my PhD in Computational Biology at Brown University in 2022, advised by [Dr. Lorin Crawford](http://www.lcrawlab.com/) and [Dr. Jeffrey Bailey](https://baileylab.org/). During the summer of 2025, I was a Research Intern at Microsoft Research New England working with [Dr. Lorin Crawford](http://www.lcrawlab.com/), [Dr. Ashley Conard](https://www.microsoft.com/en-us/research/people/ashleyconard/) and [Dr. Mary L. Gray](https://marylgray.org/).

--- 
# Key research projects

## Spatiotemporal and Uncertainty-aware Machine Learning Model for Drug Resistance Surveillance
I develop probabilistic machine-learning models that integrate large, heterogeneous genomic datasets to quantify and forecast drug resistance in real-world settings.  I combined over 120,000 pathogen genomes from public surveillance and literature sources and applied a spatiotemporal Gaussian process framework to generate high-resolution, uncertainty-aware maps of emerging antimalarial resistance across Africa. The model disentangles local mutation emergence from geographic spread, enabling early identification of resistance hotspots and co-evolution of partner-drug markers that threaten therapy durability. This work illustrates how scalable, uncertainty-aware ML models can transform sparse biological surveillance data into actionable intelligence for therapeutic strategy, resistance monitoring, and targeted intervention.

## Bayesian Mixed-Effects Modeling for Drug-Resistance Forecasting
Built a scalable Bayesian modeling framework to infer and forecast the spatiotemporal spread of drug-resistance mutations from sparse genomic surveillance data, with calibrated uncertainty for decision support. The approach emphasizes interpretability and close alignment with biological domain knowledge, enabling actionable insights into mutation-specific dynamics and regional heterogeneity.

Find more information in the [published paper in Lancet Microbe](https://www.thelancet.com/journals/lanmic/article/PIIS2666-5247(24)00295-7/fulltext) or implement our method with our [code](https://github.com/bailey-lab/selmar).

## A Statistical and Machine Learning Approach to Investigating Unmapped Regions of the Malaria Parasite Genome
While the malaria parasite's genome (*Plasmodium falciparum*) shows limited overall genetic variation, much of it is concentrated in highly dynamic subtelomeric regions. These regions encode genes that help the parasite evade human immunity, making them crucial for its survival. I am developing an AI-driven framework that leverages statistical methods and Variational Autoencoders to analyze these challenging genomic regions. This approach aims to uncover their role in shaping parasite population structure and identify shared genetic variants across populations. Insights from this research could improve our understanding of malaria progression and guide the development of novel drug targets.

## Pancancer evolutionary model analyzing scRNAseq data
During my undergrad, I developed an evolutionary modeling framework to characterize tumor progression across multiple cancer types using single-cell RNA-seq data. The approach integrated copy-number variation features inferred from single-cell transcriptomes with machine-learning models, including Random Forests, to classify distinct evolutionary modes and identify key genomic drivers of tumor evolution. By leveraging ensemble learning, the model captured non-linear relationships and interactions underlying clonal expansion, adaptation, and intratumoral heterogeneity. This work provided interpretable insights into how cancer cell populations evolve over time and under treatment pressure, demonstrating the value of ML methods applied to high-dimensional single-cell data for understanding cancer dynamics.

