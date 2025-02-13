---
title: "Deep Learning Based Lung Image Segmentation Using XR-U-Net"
collection: talks
type: "Conference proceedings talk"
permalink: /talks/2024-12-21-talk-Lung-Seg
venue: "27th International Conference on Computer and Information Technology (ICCIT)"
date: 2014-12-21
location: "Cox's Bazar, Bangladesh"
---
<button class = "btn" onclick="window.location.href='http://sajeebray.github.io/files/1057-slides.pdf';">View Slides</button>

In this talk, we explore the implementation of our research on "Deep Learning Based Lung Image Segmentation Using XR-U-Net". This work focuses on enhancing the accuracy of lung image segmentation without preprocessing of images using a novel deep-learning architecture.

---

## Introduction

Lung image segmentation is a crucial process in medical imaging. It involves isolating lung regions in X-rays or CT scans, aiding in diagnosing and treating lung diseases. Accurate segmentation allows medical practitioners to better visualize the lung structure and identify abnormalities.

Chest X-rays are one of the most accessible and cost-effective medical imaging methods globally, accounting for over one-third of all medical imaging. They are essential for diagnosing conditions like tuberculosis, pneumonia, and lung nodules. The U-Net architecture, with its skip connections, excels in medical image segmentation, achieving precise results.

---

## Our Contributions

In our work, we:
- Developed XR-U-Net, an extended U-Net architecture with a five-layer encoder-decoder structure.
- Removed preprocessing steps to simplify the segmentation workflow.
- Conducted detailed visual evaluations of segmented images to validate performance.

---

## Dataset

Our study utilized the Montgomery County chest X-ray dataset:
- 138 images in total, including:
  - 80 normal cases.
  - 58 cases with tuberculosis manifestations.
- The dataset was split into:
  - 112 images for training,
  - 13 for validation, and
  - 13 for testing.

This dataset provides a foundational base for evaluating our model's effectiveness.

---

## System Architecture

The XR-U-Net system architecture enhances the traditional U-Net with a quintuple-layer encoder-decoder structure. This innovation allows for deeper feature extraction and improved segmentation without requiring preprocessing steps.

---

## Metrics and Training

To evaluate performance:
1. IoU (Intersection over Union) measures the overlap between the predicted and actual masks.
2. Dice Coefficient quantifies the similarity between predicted and ground-truth masks.

The model training was carried out over 100 epochs using the Adam optimizer with fine-tuned parameters, achieving strong convergence as seen in the training curves.

---

## Evaluation

The XR-U-Net achieved impressive results:
- Segmentation Accuracy: 95.7%
- IoU: 0.83
- Dice Score: 91%

Visual results showcase accurate lung boundary predictions that align closely with ground truth, as demonstrated in the comparison images.

---

## Comparative Study

When compared with existing methods:
- XR-U-Net achieves a balance of accuracy and computational efficiency.
- While U-Net++ and Deep Residual U-Net achieved higher accuracy, their models were more complex and resource-intensive.

---

## Limitations

Despite promising results, our model has some limitations:
1. Limited dataset diversity restricts generalizability.
2. Focused only on two-dimensional segmentation.
3. Minor discrepancies in segmenting intricate lung structures.
4. Lack of integration with advanced diagnostic frameworks.

---

## Future Work

Future directions for this research include:
1. Expanding datasets to include diverse cases.
2. Exploring three-dimensional segmentation.
3. Integrating the XR-U-Net model with diagnostic frameworks to identify conditions like cardiomegaly.

---

## Conclusion

The XR-U-Net model demonstrates strong potential in advancing lung segmentation accuracy, achieving a Dice score of 91% and an IoU of 0.83%. Its simplicity and efficiency make it suitable for clinical applications, with the promise of further improvements in future work.

---

## Acknowledgment

We extend our gratitude to the Department of Information and Communication Engineering, Pabna University of Science and Technology, for their support and funding of this research.

---

Feel free to contribute, raise issues, or suggest improvements!
