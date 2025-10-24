# Mike Wolfe, Ph.D.

I am a Bioinformatician (Scientist III) in the Cancer Informatics
Shared Resource (CISR) at the Carbone Cancer Center at the University of
Wisconsin-Madison. I received my Ph.D. in Biological Chemistry and M.S. in
Bioinformatics from the University of Michigan and my B.S. in
Biomedical Engineering from the Ohio State University.

I am broadly interested in the molecular mechanisms of gene regulation
that underlie how cancer cells respond to treatment, how bacteria
develop antibiotic resistance, and how immune cells respond to their
environment.

A couple things about me:
- I have over 10 years of experience as an interdisciplinary researcher with
  training in computational biology, biochemistry, and biomedical
  engineering.
- I have extensive experience with many -Omics methodologies including bulk
  and scRNA-seq, ChIP-seq, and Hi-C.
- I am well-versed in computational and statistical methods including
  regression modeling, machine learning, and analysis pipeline
  development.
- I have a wide-breadth of biology expertise working with experimental systems
  from bacteria to humans and at scales from the molecular to the
  systems-level.

This README is intended to be a table of contents for my github
repositories.

## Pipelines

These are a series of
[snakemake](https://snakemake.readthedocs.io/en/stable/) for
processing illumina sequencing data. Each is general purpose with
a simple sample sheet as the expected input. Each was designed with
the smaller genome sizes of bacteria in mind.

| Pipeline | Description |
| -------- | ----------- |
|[Strandedseq_pipeline](https://github.com/mikewolfe/Strandedseq_pipeline)     | Snakemake pipeline for analyzing bacterial illumina sequencing where strand matters. I.e. RNA-seq, NET-seq |
|[ChIPseq_pipeline](https://github.com/mikewolfe/ChIPseq_pipeline)             | Snakemake pipeline for analyzing bacterial ChIP-seq data |
|[Bacterial_reseq](https://github.com/mikewolfe/Bacterial_reseq)               | Snakemake pipeline for analyzing bacterial whole-genome sequencing using [breseq](https://barricklab.org/twiki/bin/view/Lab/ToolsBacterialGenomeResequencing) |
|[HiC_pipeline](https://github.com/mikewolfe/HiC_pipeline)                     | Snakemake pipeline for analyzing bacterial Hi-C data. Currently private. |


## Code associated with publications

Here are repositories with code that is associated with a publication
that I have contributed to.

| Repo | Description |
| -------- | ----------- |
|[ShapeME](https://github.com/freddolino-lab/ShapeME)     | Mutual information-based tool for finding DNA-shape based binding motifs https://doi.org/10.1101/2025.01.28.635290 |
|[Shen_H-NS_2022](https://github.com/mikewolfe/Shen_H-NS_2022)     | Bayesian model for analyzing E. coli H-NS footprinting data https://doi.org/10.1016/j.isci.2022.104429 |
|[2018_Lrp_ChIP](https://github.com/freddolino-lab/2018_Lrp_ChIP)     | Custom ChIP-seq workflow to analyze E. coli Lrp gene regulation https://doi.org/10.1128/jb.00411-18 |
|[2018_genomeProfiling](https://github.com/freddolino-lab/2018_genomeProfiling)     | Utilities to calculate windowed summaries of features to predict positional transcription of a reporter in E. coli  https://doi.org/10.1016/j.cels.2019.02.004 |

## Quarto

Here are some extensions for working with quarto

| Extension | Description |
| -------- | ----------- |
|[front-van](https://github.com/mikewolfe/front-van) | Journal extension for writing Frontiers-in articles in quarto |

## Contributions to widely-used software

Here are some repositories I have made contributions to.

| Repo | Description |
| -------- | ----------- |
|[MultiQC](https://github.com/mikewolfe/MultiQC) | Added support for some `pairtools` Hi-C reports |
|[pyGenomeTracks](https://github.com/mikewolfe/pyGenomeTracks) | Added ability to specify an alpha for genome tracks |

## Analysis tools and helper scripts

Here are some utility tools and scripts I have developed.

| Repo | Description |
| -------- | ----------- |
|[pytools3](https://github.com/mikewolfe/pytools3) | A series of utility scripts and classes for dealing with genomic data |
|[CMARRT_python](https://github.com/mikewolfe/CMARRT_python) | A python re-implementation of CMARRT peak caller https://pmc.ncbi.nlm.nih.gov/articles/PMC2862456/ |


## Teaching and Personal Development

Here are some repositories associated with workshops, teaching, or
personal development in my own continued education.

| Repo | Description |
| -------- | ----------- |
|[UWMadisonMLM25](https://github.com/mikewolfe/UWMadisonMLM25) | Repo for the 2025 UW-Madison Machine Learning Challenge predicting changes in protein function due to changes in sequence |
|[R4DSNotes](https://github.com/mikewolfe/R4DSNotes) | Personal notes on the excellent R for Data Science book https://r4ds.had.co.nz/ |
|[2019-05-23-shapiro](https://github.com/mikewolfe/2019-05-23-shapiro) | Software carpentry workshop at University of Michigan where I was a lead instructor |
|[SICP](https://github.com/mikewolfe/SICP) | Personal notes on the Structure and Interpretation of Computer Programs book https://web.mit.edu/6.001/6.037/sicp.pdf |


