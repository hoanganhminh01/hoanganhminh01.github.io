---
title: "EfficientSkinTrans: Enhancing Dermatological Analysis Through a Hybrid ViT Network"
collection: publications
permalink: /publications/efficient-skin-trans/
date: 2026-01-05
venue: "16th IEEE Annual Computing and Communication Workshop and Conference (CCWC)"
authors: "Minh Anh Hoang, Hieu Le Minh Phan, Ngoc Nam Vo, Khuong Nguyen-Vinh"
paperurl: ""
citation: "Hoang, M. A., Phan, H. L. M., Vo, N. N., & Nguyen-Vinh, K. (2026). EfficientSkinTrans: Enhancing Dermatological Analysis Through a Hybrid ViT Network. IEEE CWCC 2026."
category: conferences
---

# Abstract
Accurate diagnosis of skin lesions remains challenging due to high visual variability and overlap among dermatological conditions. While prior work has explored combining CNNs with transformer encoders, many existing hybrids rely on heavy or redundant backbones that limit generalization. To address this, we proposed EfficientSkinTrans, a lightweight yet powerful hybrid architecture that integrates an EfficientNet-style convolutional encoder with a compact transformer module to jointly capture local texture patterns and long-range contextual dependencies. Experiments on the ISIC-2019 dataset showed that EfficientSkinTrans achieved strong performance across all evaluation metrics, outperforming conventional Transformer-based and recent hybrid approaches. The model also demonstrated notable zero-shot generalization to unseen diseases, including Monkeypox images from the MSLD v2.0 dataset, despite receiving no prior exposure to this condition. To ensure clinical trustworthiness, we also employed Grad-CAM++ to confirm that the model consistently attended to medically relevant lesion regions. These results highlighted EfficientSkinTrans as a reliable, interpretable, and generalizable solution for AI-assisted dermatological diagnosis, suitable both for common conditions and emerging infectious diseases.
