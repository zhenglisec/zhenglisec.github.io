---
title:          "Enhanced Label-Only Membership Inference Attacks with Fewer Queries"
date:           2025-01-03
selected:       false
#type:           publication
#tags:           ["# continual learning", "# few-shot learning"]
pub:            "USENIX Security 2025"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
# pub_date:       "2025"
semantic_scholar_id: 66660d0c2595da2fa77d24325a1b777f1e0ee87e  # use this to retrieve citation count
abstract: >-
  Machine Learning (ML) models are vulnerable to membership inference attacks (MIAs), where an adversary aims to determine whether a specific sample was part of the model’s  training data. Traditional MIAs exploit differences in the model’s output posteriors, but in more challenging scenarios  (label-only scenarios) where only predicted labels are available, existing works directly utilize the shortest distance of samples reaching decision boundaries as membership signals, denoted as the shortestBD. However, they face two key challenges: low distinguishability between members and non-members due to sample diversity,and high query requirements stemming from direction diversity. ...
cover:          /assets/images/covers/2025-3Usenix.png
authors:
  - Hao Li*
  - Zheng Li*
  - Siyuan Wu
  - Yutong Ye
  - Min Zhang#
  - Dengguo Feng
links:
  Paper: https://www.usenix.org/system/files/usenixsecurity25-li-hao.pdf
  Code: https://github.com/AIPAG/DHAttack
---
