---
title: Determining clinically relevant features in cytometry data using persistent
  homology
authors:
- Soham Mukherjee
- Darren Wethington
- Tamal K Dey
- Jayajit Das
date: '2022-01-01'
publishDate: '2025-04-25T03:35:23.247868Z'
publication_types:
- article-journal
publication: '*PLoS Computational Biology*'
doi: '10.1371/journal.pcbi.1009931'
abstract: 'Cytometry experiments yield high-dimensional point cloud data that is difficult to interpret manually. Boolean gating techniques coupled with comparisons of relative abundances of cellular subsets is the current standard for cytometry data analysis. However, this approach is unable to capture more subtle topological features hidden in data, especially if those features are further masked by data transforms or significant batch effects or donor-to-donor variations in clinical data. We present that persistent homology, a mathematical structure that summarizes the topological features, can distinguish different sources of data, such as from groups of healthy donors or patients, effectively. Analysis of publicly available cytometry data describing non-naïve CD8+ T cells in COVID-19 patients and healthy controls shows that systematic structural differences exist between single cell protein expressions in COVID-19 patients and healthy controls. We identify proteins of interest by a decision-tree based classifier, sample points randomly and compute persistence diagrams from these sampled points. The resulting persistence diagrams identify regions in cytometry datasets of varying density and identify protruded structures such as ''elbows''. We compute Wasserstein distances between these persistence diagrams for random pairs of healthy controls and COVID-19 patients and find that systematic structural differences exist between COVID-19 patients and healthy controls in the expression data for T-bet, Eomes, and Ki-67. Further analysis shows that expression of T-bet and Eomes are significantly downregulated in COVID-19 patient non-naïve CD8+ T cells compared to healthy controls. This counter-intuitive finding may indicate that canonical effector CD8+ T cells are less prevalent in COVID-19 patients than healthy controls. This method is applicable to any cytometry dataset for discovering novel insights through topological data analysis which may be difficult to ascertain otherwise with a standard gating strategy or existing bioinformatic tools.'
url_pdf: 'uploads/papers/mukherjee-2022-determining.pdf'
---
