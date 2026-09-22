---
title: 'Generalizing molecular design via flexible search space control'
authors:
- Satoru Fujii
- Yuki Murakami
- Tatsuya Yoshizawa
- Shoichi Ishida
- Nobuo Cho
- Masateru Ohta
- Teruki Honma
- Kazuki Yoshizoe
- Masato Sumita
- Koji Tsuda
- Kei Terayama
date: '2026-08-21'
publishDate: '2026-08-21T00:00:00Z'
publication_types:
- article-journal
publication: '*Communications Chemistry*'
links:
- name: DOI
  url: https://doi.org/10.1038/s42004-026-02172-7
url_code: 'https://github.com/molecule-generator-collection/ChemTSv3'

abstract: Recent advances in generative artificial intelligence have made in silico molecular design a powerful approach for exploring chemical space toward specific goals. However, despite the need for trial-and-error adjustment of generative strategies and reward formulations, most methods implicitly fix the searchable chemical space, significantly limiting flexibility in practical design. This paper introduces ChemTSv3, an exploration framework with a flexible architecture that accommodates diverse design scenarios for adaptive molecular design. Specifically, molecular representations are unified as nodes, including string-based encodings, molecular graphs, and protein sequences. Molecular generations and editing operations are abstracted as transitions between nodes, allowing graph-based modifications, sequential mutations, and large-language-model-driven transformations to be handled within the same formulation. Representations and transition types can be dynamically switched to adapt the search space to the stage and nature of the design task. Here we show that this flexibility enables efficient exploration across diverse design spaces, from drug-like small molecules to proteins.
---
