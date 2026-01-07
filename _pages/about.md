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

I am a PhD candidate in Computational Biology at the [Center for Computational Molecular Biology at Brown](https://ccmb.brown.edu), specializing in the development of artificial intelligence (AI) and Bayesian statistics models for complex, high-dimensional biomedical data. My research integrates omics, clinical, and real-world evidence to address translational challenges such as drug resistance, cancer evolution, and infectious disease dynamics, with a strong emphasis on identifying novel biological mechanisms and predictive biomarkers. I work closely with domain experts to translate biological and clinical questions into robust, interpretable AI systems that support both biological discovery and decision-making across biotechnology, pharmaceutical research, and public-health settings. I am also a [Frontera Computational Science Fellowship Fellow 2025-2026](https://frontera-portal.tacc.utexas.edu/fellowship/).

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

## Multimodal AI for Personalized Blood Biomarker Prediction
During my internship at Microsoft Research, I started developing a **multimodal learning framework integrates genomic, clinical, and environmental data to advance blood biomarker prediction and disease modeling**, which I am continuing to work on as part of my Ph.D. Crucially, this method provides a **quantitative assessment of each modality's contribution to the prediction task**, allowing us to identify influential features and determine the specific data modalities that are most vital for understanding and predicting specific disease-linked biomarkers. This moves beyond genetic determinism, providing a scalable and interpretable model for generating actionable insights in personalized medicine.

## Spatiotemporal and Uncertainty-aware Machine Learning Model for Drug Resistance Surveillance
In this study, we integrated large-scale but highly heterogeneous genomic surveillance data using a **machine learning based spatiotemporal framework** to map the prevalence of drug resistance mutations across Africa. The model **infers continuous resistance landscapes and quantifies uncertainty despite sparse sampling**, enabling early identification of emerging hotspots before loss of clinical efficacy is observed. This work demonstrates how ML can extract actionable signals from real-world, incomplete biological data to inform drug strategy and resistance monitoring. More information is available in the [preprint](https://pubmed.ncbi.nlm.nih.gov/41480040/) and our [code](https://github.com/mrc-ide/GRFFmap/).

## Clinical Relevance of Toxicity Metrics in Drug Combination Models
In this study, we systematically evaluated whether commonly used **synergy scores and toxicity penalty metrics in cancer drug combination models reflect clinically observed adverse drug–drug interactions**. By integrating large-scale synergy datasets with curated clinical toxicity databases, we show that **optimizing for synergy alone can inadvertently prioritize toxic combinations** and that existing toxicity proxies lack robust clinical validation. This work highlights a critical gap for ML-driven combination therapy development and underscores the need for clinically grounded toxicity data and modeling strategies. More information is available in the [preprint](https://www.biorxiv.org/content/10.1101/2025.04.13.648641v1) (accepted at Bioinformatics) and [code](https://github.com/amw14/toxicity-cancer-drug-combination).

## Bayesian Mixed-Effects Modeling for Drug-Resistance Forecasting
Built a scalable Bayesian modeling framework to **infer and forecast the spatiotemporal spread of drug-resistance mutations from sparse genomic surveillance data**, with calibrated uncertainty for decision support. The approach emphasizes interpretability and close alignment with biological domain knowledge, enabling actionable insights into mutation-specific dynamics and regional heterogeneity. More information is available in the [published paper in Lancet Microbe](https://www.thelancet.com/journals/lanmic/article/PIIS2666-5247(24)00295-7/fulltext) or implement our method with our [code](https://github.com/bailey-lab/selmar).

## A Statistical and Machine Learning Approach to Investigating Unmapped Regions of the Malaria Parasite Genome
While the malaria parasite's genome (*Plasmodium falciparum*) shows limited overall genetic variation, much of it is concentrated in highly dynamic subtelomeric regions. These regions encode genes that help the parasite evade human immunity, making them crucial for its survival. I am **developing an AI-driven framework that leverages statistical methods and Variational Autoencoders** to analyze these challenging genomic regions. This approach aims to **uncover the role of these genomic regions in shaping parasite population structure** and identify shared genetic variants across populations. Insights from this research could improve our understanding of malaria progression and guide the development of novel drug targets.

## Pancancer evolutionary model analyzing scRNAseq data
During my undergrad, I developed an evolutionary modeling framework to characterize tumor progression across multiple cancer types using single-cell RNA-seq data. The approach integrated copy-number variation features inferred from single-cell transcriptomes with machine-learning models, including Random Forests, to **classify distinct evolutionary modes and identify key genomic drivers of tumor evolution**. By leveraging ensemble learning, the model captured non-linear relationships and interactions underlying clonal expansion, adaptation, and intratumoral heterogeneity. This work provided interpretable insights into how cancer cell populations evolve over time and under treatment pressure, demonstrating the value of ML methods applied to high-dimensional single-cell data for understanding cancer dynamics.

