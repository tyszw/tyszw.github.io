---
title: 'Avoiding Reward Hacking in Multi-Objective Molecular Design: A Data-Driven Generative Strategy with a Reliable Design Framework'
authors:
- Tatsuya Yoshizawa
- Shoichi Ishida
- Tomohiro Sato
- Masateru Ohta
- Teruki Honma
- Kei Terayama
date: '2024-06-01'
publishDate: '2025-02-01T05:35:48.354459Z'
publication_types:
- article
publication: '*ChemRxiv*'
doi: 10.26434/chemrxiv-2024-dh681
# links:
# - name: URL
#   url: http://dx.doi.org/10.26434/chemrxiv-2024-dh681
url_code: 'https://github.com/ycu-iil/DyRAMO'

abstract: Molecular design using data-driven generative models has emerged as a promising technology, impacting various fields such as drug discovery and the development of functional materials. However, this approach is often susceptible to optimization failure due to reward hacking, where prediction models fail to accurately predict properties for designed molecules that considerably deviate from the training data. While methods for estimating prediction reliability, such as the applicability domain (AD), have been proposed for mitigating reward hacking, multi-objective optimization makes it challenging. The difficulty arises from the need to determine in advance whether the multiple ADs with some reliability levels overlap in chemical space, and to appropriately adjust the reliability levels for each property prediction. Herein, we propose a reliable design framework to perform multi-objective optimization using generative models while preventing reward hacking. To demonstrate the effectiveness of the proposed framework, we designed candidates for anticancer drugs as a typical example of multi-objective optimization. We successfully designed molecules with high predicted values and reliabilities, including an approved drug. In addition, the reliability levels can be automatically adjusted according to the property prioritization specified by the user without any detailed settings. Our approach presents a solution to the essential problem of designing molecules using data-driven generative models.
---
