---
title: "RViT-FusionNet: A Local Cross-Attention Feature Fusion-based Hybrid Framework for Brain Tumor Classification"
collection: publications
category: manuscripts
permalink: /publication/J4-RVitFusionNet
excerpt: 'This manuscript presents RViT-FusionNet, a hybrid deep learning architecture that combines convolutional neural networks (CNNs) with a refined Vision Transformer (RViT) for brain tumor classification using MRI scans. The key contribution is in the local cross-attention feature fusion mechanism, designed to capture both local spatial features and global contextual dependencies across multiple MRI modalities. Extensive experiments on benchmark datasets demonstrate that the proposed framework achieves higher accuracy and robustness compared to standard CNN, ViT, and hybrid transformer models.'
date: 2026-11-05
venue: 'Neural Computing and Applications (Springer-Q1; Cite Score: 12.7; Impact Factor: 4.5)'
# slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://doi.org/10.1007/s00521-026-12290-x'
citation: 'N. Islam, S. K. Ray, M. A. Hossain et al., “RViT-FusionNet: A Local Cross-Attention Feature Fusion-based Hybrid Framework for Brain Tumor Classification,” Neural Computing and Applications, 38, 518 (2026). https://doi.org/10.1007/s00521-026-12290-x'
---

Accurate brain tumor classification via MRI is essential for diagnosis and treatment. This study introduces RViT-FusionNet, a hybrid deep learning model that integrates convolutional and transformer architectures for enhanced tumor detection. The model utilizes ResNet-50 to capture textural details and a Vision Transformer for extracting global context. A Local Cross-Attention (LCA) module is proposed to align and merge these features, allowing the network to model local structures and long-range dependencies concurrently. To enhance generalization across varied imaging conditions and tumor types, a domain discriminator is included to discern spatial and domain-specific patterns, fostering the learning of domain-invariant representations. The approach is validated on four public MRI datasets, yielding classification accuracies of 99.08% ± 0.16%, 99.56% ± 0.17%, 96.20% ± 0.25% and 94.76% ± 0.35% for glioma, meningioma, pituitary tumors, and healthy cases, respectively. For interpretability, Grad-CAM is utilized to create saliency maps highlighting tumor regions, confirming the model's focus on clinically relevant areas. These findings demonstrate that RViT-FusionNet achieves exceptional performance while maintaining high interpretability, positioning it as an effective tool for computer-assisted brain tumor diagnosis. This framework is posited as a robust and scalable solution for multi-class brain tumor classification in clinical practice. The complete source code will be made available in a GitHub repository after acceptance of the manuscript.

*Equal contribution with first author

<button class = "btn" onclick="window.location.href='https://github.com/naimaislam-ice/RViT-FusionNet-LCA-based-brain-tumor-classification';">Code on Github</button>   <button class = "btn" onclick="window.location.href='https://doi.org/10.1007/s00521-026-12290-x';">Paper</button>