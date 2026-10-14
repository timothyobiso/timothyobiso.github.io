---
title: "Clustering Analysis for Error Detection in Named Entity Recognition Datasets"
collection: publications
permalink: /publication/ner-clustering
excerpt: ''
date: 2026-07-01
venue: 'LAW XX'
paperurl: 'https://aclanthology.org/2026.law-main.17/'
citation: 'Matthew Flynn, <b>Timothy Obiso</b>, Sam Newman, and Constantine Lignos. 2026. Clustering Analysis for Error Detection in Named Entity Recognition Datasets. In <i>Proceedings of the 20th Linguistic Annotation Workshop (LAW XX)</i>, pages 229–240, San Diego, California, USA. Association for Computational Linguistics.'
---

This paper introduces a method for the automatic detection of annotation errors and corrections in named entity recognition datasets using a novel two-stage dimension reduction of dense sentence embeddings. We first find the top-n principal components of an embedding and then use UMAP for second-stage, non-linear dimension reduction and clustering using different distance metrics. We analyze these clusters using silhouette scores to flag outlier mentions for correction. Using the corrections in the CoNLL# dataset as a benchmark, all of the top-five outliers needed correction, as did 7 of the top-10. This approach also identified 32 of the top-50 outlier mentions that are corrections. This method offers a relatively low-effort way to leverage text embeddings and dimensionality reduction to identify likely annotation errors. We release related code and data at https://github.com/bltlab/clustering-for-ner.
