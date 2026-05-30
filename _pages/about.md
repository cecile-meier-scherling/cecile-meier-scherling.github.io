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

I am a PhD candidate at the [Center for Computational Molecular Biology at Brown University](https://ccmb.brown.edu), advised by Dr. Lorin Crawford and Dr. Jeffrey Bailey. My work sits at the intersection of machine learning, Bayesian statistics, and translational biology.

My research focuses on a single through-line: **how do we build AI systems that extract reliable, interpretable signal from the messy, heterogeneous biological data that actually exists in the real world?** That means genomic surveillance data with sparse sampling, multi-omics cohorts with missing modalities, and clinical datasets with confounded outcomes.

I work closely with domain experts such as biologists, clinicians, and public health scientists to ensure that models don't just perform well in silico, but **directly improve how decisions are mad**e in biotechnology, pharmaceutical research, and public-health settings.

During the summer 2025 I was a Research Intern at Microsoft Research New England. Currently, I am a Visiting PhD Researcher at Oxford University and Imperial College London, and will be a Computational Biology Intern at Takeda Pharmaceutical (Jun–Aug 2026). I am a [Frontera Computational Science Fellowship Fellow 2025-2026](https://frontera-portal.tacc.utexas.edu/fellowship/) (Texas Advanced Computing Center). My work has been cited in the WHO World Malaria Report 2025.

## Research Interests
- Interpretable ML
- Generative models
- Biomarker discovery
- Drug discovery
- Multi-omics integration
- Clinical decision-making
- Translational AI
- Precision medicine
- Infectious disease

## Mentors
I have over seven years of research training, advised by:
- Dr. Lorin Crawford ([Microsoft Research](http://www.lcrawlab.com/) and Brown University)
- Dr. Jeffrey Bailey ([Center for Computational Biology, Brown University](https://baileylab.org/)).
- Dr. Ashley Conard ([Microsoft Research](https://www.microsoft.com/en-us/research/people/ashleyconard/))
- Dr. Robert (Bob) Verity ([Imperial College London](https://profiles.imperial.ac.uk/r.verity))
- Dr. Oliver James (OJ) Watson ([Imperial College London](https://www.ojwatson.co.uk/))
- Dr. Mary L. Gray ([Microsoft Research](https://marylgray.org/))
- Dr. Franziska Michor ([Department of Data Science, Dana-Farber Cancer Institute](http://michorlab.dfci.harvard.edu/))
- Dr. Simona Cristea ([Department of Data Science, Dana-Farber Cancer Institute](https://labs.dana-farber.org/aguirrelab/people/simona-cristea-phd))

--- 
# Key research projects

## Transformer-Based Generative Model for Population Genetic Inference
A forward-time generative simulator and transformer-based deep learning model for simulation-based inference of population genetic dynamics. Generates large-scale synthetic biological sequence trajectories under realistic evolutionary dynamics, enabling downstream ML inference without explicit likelihoods. A novel framework applicable to genomic and protein sequence modeling.

## Multimodal AI for Personalized Blood Biomarker Prediction
A **multimodal generative framework** that integrates genomic, clinical, and environmental data to predict blood biomarkers, moving beyond genetic determinism to provide quantitative, modality-level interpretability. Enables actionable insights into which data types drive disease-linked predictions, directly supporting personalized medicine pipelines.

## Spatiotemporal Bayesian Model for Drug Resistance Surveillance
A Bayesian spatiotemporal ML framework that maps the continuous prevalence of antimalarial drug resistance mutations across Africa from sparse, heterogeneous genomic surveillance data. Provides calibrated uncertainty quantification for early hotspot detection, before clinical efficacy is lost, enabling proactive drug strategy decisions at scale. [Preprint](https://pubmed.ncbi.nlm.nih.gov/41480040/) | [Code](https://github.com/mrc-ide/GRFFmap/).

## Clinical Relevance of Toxicity Metrics in Drug Combination Models
Systematic evaluation of whether ML-driven synergy scores and toxicity metrics in cancer drug combination models reflect clinically observed adverse interactions. Integrated large-scale synergy datasets with curated clinical toxicity databases, revealing a critical gap: optimizing for synergy alone can inadvertently prioritize toxic combinations. Directly informs safer ML-guided drug discovery pipelines. [Paper in Bioinformatics](https://academic.oup.com/bioinformatics/article/42/2/btag007/8426183) | [Code](https://github.com/amw14/toxicity-cancer-drug-combination).

## Bayesian Mixed-Effects Modeling for Drug-Resistance Forecasting
Bayesian mixed-effects model estimating the speed of antimalarial drug-resistance spread across Uganda and southeast Asia from sparse genomic surveillance data. Forecasts show combined resistance mutations could reach near fixation within a decade. These findings were cited in the WHO World Malaria Report 2025 and directly inform global drug policy. Demonstrates how calibrated, uncertainty-aware ML can turn incomplete real-world biological data into actionable public health decisions. [Paper in Lancet Microbe](https://www.thelancet.com/journals/lanmic/article/PIIS2666-5247(24)00295-7/fulltext) | [Code](https://github.com/bailey-lab/selmar).

## Interpretable Evolutionary Modeling of Tumor Progression from scRNA-seq
An evolutionary ML framework integrating copy-number variation features from single-cell RNA-seq data to classify tumor evolutionary modes across cancer types. Random Forest ensemble learning captured non-linear interactions underlying clonal expansion, intratumoral heterogeneity, and treatment pressure — providing interpretable insights into cell-state dynamics for drug target identification.

