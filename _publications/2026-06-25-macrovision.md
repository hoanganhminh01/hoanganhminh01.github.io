---
title: "MacroVision: A Two-Stage Localization and Fine-Grained Classification Pipeline for High-Cardinality Food Ingredient Recognition"
collection: publications
permalink: /publications/macrovision/
date: 2026-06-25
venue: "23rd International Joint Conference on Computer Science and Software Engineering (JCSSE)"
authors: "Vinh Khai Han, Ngan Bui Thanh Pham, Minh Anh Hoang"
paperurl: "https://ieeexplore.ieee.org/document/11596987"
citation: "V. K. Han, N. B. T. Pham and M. A. Hoang, MacroVision: A Two-Stage Localization and Fine-Grained Classification Pipeline for High-Cardinality Food Ingredient Recognition, 2026 23rd International Joint Conference on Computer Science and Software Engineering (JCSSE), Bangkok, Thailand, 2026, pp. 115-120, doi: 10.1109/JCSSE68839.2026.11596987."
category: conferences
---

# Abstract
Automatic recognition of Vietnamese food ingredients presents a significant challenge due to the high visual similarity across hundreds of fine-grained categories, combined with the absence of any ingredient-level visual benchmark for Vietnamese cuisine. We introduce Vingredient, a dataset of 4,884 images across 207 Vietnamese ingredient classes with bounding-box annotations generated via automated Grounding DINO labeling and refined through human-in-the-loop validation. We further propose MacroVision, a two-stage pipeline that decouples localization from classification: Stage 1 uses Grounding DINO zero-shot to achieve 98.9% recall, and Stage 2 classifies each crop with a frozen DINOv3 ViT-S/16 and linear Softmax head, achieving 84.81% Top-1 and 97.52% Top-5 accuracy on the validation set.
