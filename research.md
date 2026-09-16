---
layout: default
title: Research
permalink: /research/
---

# Research

<p class="lede">Deep Learning and Agentic AI for cancer: integrating multi-omics data, histopathology images and biological knowledge to explain disease mechanisms and make better clinical predictions.</p>

## Cancer -omics data integration

Tumours are described by many layers of data at once — DNA alterations, gene expression, protein abundance, metabolite levels — and each layer on its own gives a partial view. Our aim is to advance Deep Learning and Agentic AI technologies that integrate these layers. We combine Deep Learning and Large Language Models with high-throughput genomics, transcriptomics, proteomics and metabolomics data, and with existing biological knowledge held in knowledge graphs such as KEGG and Reactome. An agentic approach lets the analysis be flexible and goal-driven rather than fixed to a single pipeline.

<figure>
  <img src="{{ '/assets/img/omics-integration.svg' | relative_url }}" alt="Multi-omics layers and histopathology images, combined with pathway knowledge graphs, feed deep learning and LLM agents that output subtypes, prognosis and mechanisms">
  <figcaption>Integrating multi-omics and image data with curated pathway knowledge to explain and predict cancer.</figcaption>
</figure>

Work in this area includes:

- **Generative models for gene expression** — adversarial generation of realistic transcriptomic data (gGAN; *Bioinformatics* 2022).
- **Massive-scale biclustering** — MCbiclust, which finds large co-regulated gene sets across thousands of transcriptomes, applied to nuclear-encoded mitochondrial genes and cancer metabolism (*NAR* 2017; *Cancer Research* 2024).
- **Epigenomics** — transfer learning for DNA methylation and epigenomic feature detection (LDEncoder).
- **LLMs and biomedical knowledge** — editing language models for long-tail biomedical facts (EMNLP 2025) and representation learning over biomedical pathways.
- **Federated Learning** — knowledge-distillation-based federated methods (LIFE, FedColab, FedKDMR) so that models can learn from distributed clinical data without centralising it.

## Computational histopathology

Alongside molecular data, we apply deep learning to haematoxylin-and-eosin tissue images: detecting and segmenting nuclei, classifying tissue regions, and linking image-derived features to -omics profiles and clinical outcome. This work grew out of collaborations with cancer groups at UCL and continues at Glasgow, including studies in breast cancer and liposarcoma.

<figure>
  <img src="{{ '/assets/img/histopathology.svg' | relative_url }}" alt="Stylised H&E tissue tile beside the same tile with nuclei outlined by a segmentation model">
  <figcaption>From tissue section to nuclear segmentation and classification. Illustration; see the <a href="/software/">Software</a> page for the nuclear image analysis code.</figcaption>
</figure>

## Collaborative and translational work

Much of the group's output comes from collaborations with experimental biologists and clinicians: the metabolic landscape of breast cancer and the oncogene IKKε (*Cancer Research*, *EMBO Reports*), host–microbe co-metabolism and drug efficacy (*Cell* 2017, 2019), epigenetics and pharmacogenomics of depression, and community benchmarking efforts such as CAFA, DREAM and the COVID-19 EHR DREAM challenge.

## Earlier research

**Protein structure and function prediction.** At UCL, with David Jones's group, I was involved in the development of several widely used prediction methods: PSIPRED for secondary structure, DISOPRED for intrinsic disorder, DomPred for domain boundaries, the Genomic Threading Database for structural annotation of whole proteomes, and the PSIPRED Protein Analysis Workbench that unified them. This work also covered fold recognition baselines, metal-binding-site prediction, and protein function prediction by integrating evolutionary and multi-source data.

**Multi-agent systems for bioinformatics.** Before UCL, my Research Fellowships at Warwick and INRA developed autonomous multi-agent architectures for bioinformatics data management and distributed genome annotation (GeneWeaver, AGMIAL), including a system that let several INRA laboratories annotate related *Lactobacillus* genomes collaboratively.

**Mass-spectrometry metabolomics.** At Glasgow I have also contributed to work on metabolomics, including the TopNEXt acquisition framework and simulated-to-real benchmarking of acquisition methods.

**Other Research** Molecular dynamics of polyamine–DNA binding (DPhil), gene duplication in the human lineage, parallel MCMC linkage analysis (SwiftLink), pneumococcal sequetyping, and a platform for citizen-science mapping apps.

## PhD students
- **Zheng Zhiwei** — application of Deep Learning embedding to cancer sample analysis
- **Tayyaba Khalil** - federated Learning applied to cancer clinical data analysis
- **Wenhao Li** — heterogeneous ensembles and federated learning for large-scale multi-feature data
- **Ke Xiao** — resilient learning in edge computing
- **Xinhao Yi** — representation learning of heterogeneous entities in biomedical pathways
