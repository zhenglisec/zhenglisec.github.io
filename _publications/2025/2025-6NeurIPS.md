---
title:          "ErrorTrace: A Black-Box Traceability Mechanism Based on Model Family Error Space"
date:           2025-03-03
selected:       false
pub:            "NeurIPS 2025"
semantic_scholar_id: 17cef55807e90fdfe03e788d762d2432ca8654c4  # use this to retrieve citation count
abstract: >-
  The open-source release of large language models (LLMs) enables malicious users to create unauthorized derivative models at low cost, posing significant threats to intellectual property (IP) and market stability. Existing IP protection methods either require access to model parameters or are vulnerable to fine-tuning attacks. To fill this gap, we propose ErrorTrace, a robust and black-box traceability mechanism for protecting LLM IP. Specifically, ErrorTrace leverages the unique error patterns of model families by mapping and analyzing their distinct error spaces, enabling robust and efficient IP protection without relying on internal parameters or specific query responses. Experimental results show that ErrorTrace achieves a traceability accuracy of 0.8518 for 27 base models when the suspect model is not included in ErrorTrace's training set, outperforming the baseline by 0.2593. Additionally,ErrorTrace successfully tracks 34 fine-tuned, pruned and merged models across various scenarios, demonstrating its broad applicability and robustness. In addition, ErrorTrace shows a certain level of resilience when subjected to adversarial attacks. Our code is available at: https://github.com/csdatazcc/ErrorTrace.
cover:          /assets/images/covers/2025-6NeurlPS.png
authors:
  - Chuanchao Zang
  - Xiangtao Meng
  - Wenyu Chen
  - Tianshuo Cong
  - Yaxing Zha
  - Dong Qi
  - Zheng Li#
  - Shanqing Guo#
links:
  Paper: https://openreview.net/pdf?id=3P3PL7aCXM
  Code: https://github.com/csdatazcc/ErrorTrace
---
