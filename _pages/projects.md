---
title: Projects
permalink: /projects/
author_profile: true
---

## Modelling multiple single cell genomics experiments with a joint latent space and imputing missing metadata

Joint analysis of multiple single cell RNA-sequencing (scRNA-seq) data is confounded by technical batch effects across experiments, biological or environmental variability across cells, and different capture processes across sequencing platforms. Manifold alignment is a principled, effective tool for integrating multiple data sets and controlling for confounding factors. We demonstrate that the semi-supervised t-distributed Gaussian process latent variable model (sstGPLVM), which projects the data onto a mixture of fixed and latent dimensions, can learn a unified low-dimensional embedding for multiple single cell experiments with minimal assumptions. We show the efficacy of the model as compared with state-of-the-art methods for single cell data integration on simulated data, pancreas cells from four sequencing technologies, stem cells from male and female donors, and mouse brain cells from both spatial seqFISH+ and traditional scRNA-seq.

Preprint [here](https://doi.org/10.1101/2020.01.14.906313)

## Robust dimension reduction for noisy single cell RNA-seq genomic data

Modern developments in single cell sequencing technologies enable broad insights into cellular state. Single cell RNA sequencing (scRNA-seq) can be used to explore cell types, states, and developmental trajectories to broaden understanding of cell heterogeneity in tissues and organs. Analysis of these sparse, high-dimensional experimental results requires dimension reduction. Several methods have been developed to estimate low-dimensional embeddings for filtered and normalized single cell data. However, methods have yet to be developed for unfiltered and unnormalized count data. We present a nonlinear latent variable model with robust, heavy-tailed error and adaptive kernel learning to estimate low-dimensional nonlinear structure in scRNA-seq data. Gene expression in a single cell is modeled as a noisy draw from a Gaussian process in high dimensions from low-dimensional latent positions. This model is called the Gaussian process latent variable model (GPLVM). We model residual errors with a heavy-tailed Student’s t-distribution to estimate a manifold that is robust to technical and biological noise. We compare our approach to common dimension reduction tools to highlight our model’s ability to enable important downstream tasks, including clustering and inferring cell developmental trajectories, on available experimental data. We show that our robust nonlinear manifold is well suited for raw, unfiltered gene counts from high throughput sequencing technologies for visualization and exploration of cell states.

Preprint [here](https://doi.org/10.1101/443044)

## Nonparametric Deconvolution Model (NDM) (work with Allison Chaney)

We developed a family of Bayesian nonparametric models for collections of data in whcih each observation is the average over the features from heterogeneous particles. Election data, for example, is usually in the form of precint-level vote tallies of individual citizen's votes (particles) across several candidations or measures (observations). NDMs consist of two layers of Dirichlet processes to explain the data with an unknown number of latent factors. The model recovers the local variation of each factor, unlike models such as Latent Dirichlet Allocation or Hierarchical Dirichlet Processes. We present a variational inference method to fit the model and apply it to voting data from the 2016 California elections. 

Preprint coming soon

## Uncovering spatial signaling between cells with point processes (work with Sidu Jena)

Genetic expression in cells is a results of both autonomous cell processes and spatial signalling networks. Given time series measurments of a gene using tools such as flourescent imaging, we aim to quantify the mangitude of the spatial and autonomous effects on gene expresssion. We use a structured point process to model the bursting times of gene expression that explicitly models the distance between cells to quantify the relative levels of autonomous to spatial inputs.

Preprint coming soon
