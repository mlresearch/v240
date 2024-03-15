---
abstract: Recent advances in single-cell Hi-C (scHi-C) assays allow studying the chromatin
  conformation at the resolution of a single cell or a cluster of cells. A key question
  is to identify changes in the contact strength between two cell types, known as
  differential chromatin contacts (DCCs). While existing statistical methods can identify
  changes in contact strength in bulk Hi-C data, these methods cannot be effectively
  applied to scHi-C data due to its severe sparsity. Thus it is necessary to develop
  methods for identifying differential chromatin contacts in scHi-C data.   Recently-developed
  scHi-C imputation approaches can mitigate the issue of sparsity. We propose an approach
  for identifying differential chromatin contacts using these imputation approaches.
  We build upon the existing SnapHiC-D method by replacing its imputation step with
  recent learning-based imputation approaches. We show that, via analysis of real
  scHi-C datasets with different coverages and at different resolutions, imputation
  approaches that consider the spatial correlation between bin pairs, Higashi, and
  random walk with restart, outperform other approaches. Furthermore, we show that
  careful considerations are needed when imputation is done in preprocessing steps
  as it may invalidate downstream statistical approaches. Finally, our results indicate
  that model-based imputations greatly improve performance when analyzing chromatin
  contacts at moderate resolution (100kb); however, current imputation approaches
  are inefficient in terms of both accuracy and computational complexity when being
  applied to high-resolution scHi-C resolution (10kb).
title: Model-based imputation enables improved resolution for identifying differential
  chromatin contacts in single-cell Hi-C data
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: shokraneh-kenari24a
month: 0
tex_title: Model-based imputation enables improved resolution for identifying differential
  chromatin contacts in single-cell Hi-C data
firstpage: 176
lastpage: 193
page: 176-193
order: 176
cycles: false
bibtex_author: Shokraneh Kenari, Neda and Andrews, Megan and Libbrecht, Max
author:
- given: Neda
  family: Shokraneh Kenari
- given: Megan
  family: Andrews
- given: Max
  family: Libbrecht
date: 2024-03-15
address:
container-title: Proceedings of the 18th Machine Learning in Computational Biology
  meeting
volume: '240'
genre: inproceedings
issued:
  date-parts:
  - 2024
  - 3
  - 15
pdf: https://proceedings.mlr.press/v240/shokraneh-kenari24a/shokraneh-kenari24a.pdf
extras:
- label: Supplementary PDF
  link: https://proceedings.mlr.press/v240/shokraneh-kenari24a/shokraneh-kenari24a-supp.pdf
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
