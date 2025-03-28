---
title: A data-driven generative strategy to avoid reward hacking in multi-objective
  molecular design
authors:
- Tatsuya Yoshizawa
- Shoichi Ishida
- Tomohiro Sato
- Masateru Ohta
- Teruki Honma
- Kei Terayama
date: '2025-03-01'
publishDate: '2025-03-15T01:52:33.142403Z'
publication_types:
- article-journal
publication: '*Nature Communications*, 16, 2409'
# doi: 10.1038/s41467-025-57582-3
# doi: 10.1002/wcms.1680
links:
- name: DOI
  url: https://doi.org/10.1038/s41467-025-57582-3
- name: プレスリリース：データ駆動型生成AIの限界に迫る －生成AIで信頼性の高い分子設計を実現する戦略－
  url: https://www.yokohama-cu.ac.jp/res-portal/news/2024/20250314terayama.html
url_code: 'https://github.com/ycu-iil/DyRAMO'

abstract: Molecular design using data-driven generative models has emerged as a promising technology, impacting various fields such as drug discovery and the development of functional materials. However, this approach is often susceptible to optimization failure due to reward hacking, where prediction models fail to extrapolate, i.e., fail to accurately predict properties for designed molecules that considerably deviate from the training data. While methods for estimating prediction reliability, such as the applicability domain (AD), have been used for mitigating reward hacking, multi-objective optimization makes it challenging. The difficulty arises from the need to determine in advance whether the multiple ADs with some reliability levels overlap in chemical space, and to appropriately adjust the reliability levels for each property prediction. Herein, we propose a reliable design framework to perform multi-objective optimization using generative models while preventing reward hacking. To demonstrate the effectiveness of the proposed framework, we designed candidates for anticancer drugs as a typical example of multi-objective optimization. We successfully designed molecules with high predicted values and reliabilities, including an approved drug. In addition, the reliability levels can be automatically adjusted according to the property prioritization specified by the user without any detailed settings.
---