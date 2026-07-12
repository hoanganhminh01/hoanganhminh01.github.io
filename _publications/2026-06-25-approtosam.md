---title: "AP-ProtoSAM: Enhancing ProtoSAM with Mask-Aware Prototypes and Adaptive Prompting for One-Shot Segmentation"
collection: publications
permalink: /publications/approtosam/
date: 2026-06-25
venue: "23rd International Joint Conference on Computer Science and Software Engineering (JCSSE)"
authors: "Khang Vinh Nguyen, Thao Thanh Bui, Minh Anh Hoang, Khuong Nguyen-Vinh"
paperurl: "https://ieeexplore.ieee.org/document/11597071"
citation: "K. V. Nguyen, T. T. Bui, M. A. Hoang and K. Nguyen-Vinh, "AP-ProtoSAM: Enhancing ProtoSAM with Mask-Aware Prototypes and Adaptive Prompting for One-Shot Segmentation," 2026 23rd International Joint Conference on Computer Science and Software Engineering (JCSSE), Bangkok, Thailand, 2026, pp. 219-224, doi: 10.1109/JCSSE68839.2026.11597071."
category: conferences
---

# Abstract
One-shot object segmentation aims to characterize all instances of a target object in an unseen image using only a single annotated reference example, without task-specific training. Recent foundation models, such as self-supervised vision transformers and promptable segmentation models, offer strong generalization but remain sensitive to prototype quality, object localization, and prompt design. In this work, we propose AP-ProtoSAM, an enhanced, training-free framework that improves robustness and accuracy for general-purpose one-shot segmentation. Our method introduces mask-aware dual-level prototypes, combining global semantic representations with spatially localized foreground prototypes to better handle objects with internal structures and fine details. To accurately localize and count multiple instances, we design a two-stage Voronoi-regularized localization strategy that separates high-confidence object cores from boundary expansion while preventing instance merging. Finally, we propose an adaptive prompt selection mechanism for SAM3, which dynamically chooses between point, box, and mask prompts based on localization consistency and model confidence, ensuring efficiency while maintaining segmentation quality. Extensive experiments on FSS-1000, PASCAL-5i, and COCO-20i demonstrate that our approach consistently outperforms existing training-free SAM-based baselines, achieving very strong performance under the one-shot setting while preserving strong generalization across diverse object categories.
