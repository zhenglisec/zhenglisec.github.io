---
title:          "UnGANable: Defending Against GAN-based Face Manipulation"
date:           2023-01-07
selected:       true
#type:           publication
#tags:           ["# continual learning", "# few-shot learning"]
pub:            "USENIX Security 2023"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
# pub_date:       "2025"
semantic_scholar_id: 70e9be708b1fae70c5340d33ca738c6c813da9ae  # use this to retrieve citation count
abstract: >-
  Deepfakes pose severe threats of visual misinformation to our society. One representative deepfake application is face manipulation that modifies a victim's facial attributes in an image, e.g., changing her age or hair color. The state-of-the-art face manipulation techniques rely on Generative Adversarial Networks (GANs). In this paper, we propose the first defense system, namely UnGANable, against GAN-inversion-based face manipulation. In specific, UnGANable focuses on defending GAN inversion, an essential step for face manipulation. Its core technique is to search for alternative images (called cloaked images) around the original images (called target images) in image space. When posted online, these cloaked images can jeopardize the GAN inversion process. We consider two state-of-the-art inversion techniques including optimization-based inversion and hybrid inversion, and design five different defenses under five scenarios depending on the defender's background knowledge. Extensive experiments on four popular GAN models trained on two benchmark face datasets show that UnGANable achieves remarkable effectiveness and utility performance, and outperforms multiple baseline methods. We further investigate four adaptive adversaries to bypass UnGANable and show that some of them are slightly effective.
cover:          /assets/images/covers/2023-7Usenix.png
authors:
  - Zheng Li
  - Ning Yu
  - Ahmed Salem
  - Michael Backes
  - Mario Fritz
  - Yang Zhang#
links:
  Paper: https://arxiv.org/abs/2210.00957
  Code: https://github.com/zhenglisec/UnGANable
---
