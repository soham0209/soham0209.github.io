---
title: 'GEFL: Extended filtration learning for graph classification'
authors:
- Simon Zhang
- Soham Mukherjee
- Tamal K Dey
date: '2022-01-01'
publishDate: '2025-04-25T03:35:23.269074Z'
publication_types:
- paper-conference
publication: '*Learning on Graphs Conference*'
abstract: 'Extended persistence is a technique from topological data analysis to obtain global multiscale topological information from a graph. This includes information about connected components and cycles that are captured by the so-called persistence barcodes. We introduce extended persistence into a supervised learning framework for graph classification. Global topological information, in the form of a barcode with four different types of bars and their explicit cycle representatives, is combined into the model by the readout function which is computed by extended persistence. The entire model is end-to-end differentiable. We use a link-cut tree data structure and parallelism to lower the complexity of computing extended persistence, obtaining a speedup of more than 60x over the state-of-the-art for extended persistence computation. This makes extended persistence feasible for machine learning. We show that, under certain conditions, extended persistence surpasses both the WL[1] graph isomorphism test and 0-dimensional barcodes in terms of expressivity because it adds more global (topological) information. In particular, arbitrarily long cycles can be represented, which is difficult for finite receptive field message passing graph neural networks. Furthermore, we show the effectiveness of our method on real world datasets compared to many existing recent graph representation learning methods.'
url_pdf: 'uploads/papers/zhang-2022-gefl.pdf'
---
