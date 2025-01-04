---
permalink: /projects/
title: "Projects"
author_profile: true
redirect_from:
  - /projects.html
---


## Data-driven approach for brain tumor segmentation

- **Description:** This work aims to propose a novel lightweight model to deal with brain tumor segmentation while decreasing the computational costs.
- **Languages:** Python, Pytorch
- **Code**: https://github.com/caumente/brain_tumor_segmentation
- **Status:** Accepted (DOI publicly available soon)
- **Main contributions:**
  - We propose a novel efficient lightweight architecture that outperforms some of the most popular architectures previously used in biomedical image segmentation, such as U-Net or V-Net. Our model offers significantly lower training and computational requirements while achieving comparable performance.
  - The study shows statistical differences between LGG and HGG, and suggests a potential shift in glioma segmentation strategies to optimize outcomes, especially for HGG tumors, the most aggressive ones.
  - We prove that the brain tumor segmentation problem can be effectively approached in a 2-step way by first classifying the type of glioma between HGG and LGG, and then segmenting the MRI.


## Multi-task learning: breast cancer classification and segmentation

- **Description:** This project presents a novel multi-task framework designed to enhance the accuracy and efficiency of breast cancer diagnosis using ultrasound imaging.
- **Languages:** Python, Pytorch
- **Code**: https://github.com/caumente/multi_task_breast_cancer
- **Paper:** [A multi-task framework for breast cancer segmentation and classification in ultrasound imaging](https://doi.org/10.1016/j.cmpb.2024.108540)
- **Main contributions:**
  - The multi-task framework significantly outperforms single-task approaches in terms of both segmentation and classification of breast cancer lesions.
  - Comprehensive analysis and curation of the BUSI dataset ensure minimized biases and more reliable outcomes.
  - The methodology showcases better generalization capabilities, crucial for clinical applications in breast cancer detection.