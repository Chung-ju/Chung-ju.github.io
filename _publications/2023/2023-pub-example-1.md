---
title:          "Vertical Federated Knowledge Transfer via Representation Distillation for Healthcare Collaboration Networks"
# date:           2023-01-05 00:01:00 +0800
selected:       true
pub:            "ACM Web Conference"
pub_date:       "2023"
abstract: >-
  Collaboration between healthcare institutions can significantly lessen the imbalance in medical resources across various geographic areas. However, directly sharing diagnostic information between institutions is typically not permitted due to the protection of patients' highly sensitive privacy. As a novel privacy-preserving machine learning paradigm, federated learning (FL) makes it possible to maximize the data utility among multiple medical institutions. These feature-enrichment FL techniques are referred to as vertical FL (VFL). Traditional VFL can only benefit multi-parties' shared samples, which strongly restricts its application scope. In order to improve the information-sharing capability and innovation of various healthcare-related institutions, and then to establish a next-generation open medical collaboration network, we propose a unified framework for vertical federated knowledge transfer mechanism (VFedTrans) based on a novel cross-hospital representation distillation component. Specifically, our framework includes three steps. First, shared samples' federated representations are extracted by collaboratively modeling multi-parties' joint features with current efficient vertical federated representation learning methods. Second, for each hospital, we learn a local-representation-distilled module, which can transfer the knowledge from shared samples' federated representations to enrich local samples' representations. Finally, each hospital can leverage local samples' representations enriched by the distillation module to boost arbitrary downstream machine learning tasks. The experiments on real-life medical datasets verify the knowledge transfer effectiveness of our framework.
cover:          /assets/images/covers/cover1.jpg
authors:
- Chung-ju Huang*
- Leye Wang
- Xiao Han
links:
  Paper: https://arxiv.org/pdf/2302.05675
---