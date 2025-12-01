---
permalink: /research/
title: "Research motivation"
author_profile: true
redirect_from:
  - /research.html
---


My research interests focus on exploring how artificial intelligence, specifically computer vision techniques, can be 
used to enhance patient prognosis in the medical field. I strongly believe that AI can help physicians and healthcare
professionals in the near future by accelerating the diagnosis process and offering more personalized medicine. 
Therefore, any advance in medical image analysis is a step forward in the right direction.

However, despite the rapid growth of the AI field, most of the systems developed for the
medical domain remain largely distant from clinical practice. Thus, developing methodologies that
bridge the gap between AI and trustworthy clinical applications is crucial.


## Data validation and integrity

Data constitute the raw material of AI models. In recent years, a large number of datasets have been published, which
has facilitated model training. However, not all studies carry out a thorough understanding of the data, often leading 
to incorrect conclusions.

In this line of research, we emphasize that data integrity is fundamental. In previous work, I developed an algorithm 
for detecting "duplicate" images within a dataset, providing a curated and more reliable version known as Curated BUSI.

- **C. Aumente-Maestro**, J. Díez, B. Remeseiro, [A multi-task framework for breast cancer segmentation and classification in ultrasound imaging](https://doi.org/10.1016/j.cmpb.2024.108540), Available at Computer Methods and Programs in Biomedicine - Elsevier Journal


## Resource-efficient deep learning models

As part of this research line, I developed a lightweight deep learning method and explored image analysis methodologies 
to enhance the efficiency and interpretability of medical imaging systems in limited computational scenarios for brain
tumor segmentation in MRI.

The trend over recent years has been to build more powerful AI systems at the cost of drastically increasing 
computational requirements (e.g., LLMs, VLMs, VLAs). Finding a balance between achieving sufficiently good performance 
in delineating brain tumors and managing resource consumption is necessary. From a practical standpoint, this is 
essential not only due to resource limitations in hospitals but also to support environmental sustainability by 
promoting green AI and reducing the carbon footprint.

- **C. Aumente-Maestro**, D. R. González, D. Martinez, B. Remeseiro, [BTS U-Net: A data-driven approach to brain tumor segmentation through deep learning](https://doi.org/10.1016/j.bspc.2025.107490), Available at Biomedical Signal Processing and Control - Elsevier Journal

- **C. Aumente-Maestro**, J. Díez, B. Remeseiro, [A multi-task framework for breast cancer segmentation and classification in ultrasound imaging](https://doi.org/10.1016/j.cmpb.2024.108540), Available at Computer Methods and Programs in Biomedicine - Elsevier Journal


## Evaluation of medical image segmentation AI models

While AI has demonstrated its potential to transform medical imaging workflows, the field still faces ongoing challenges.
Despite the efforts to evaluate AI systems, general limitations persist. Most tools primarily focus on evaluating 
model performance using standardized metrics; however, they often overlook the critical aspect of evaluating model 
improvements over time. There is also a lack of mechanisms for assessing and visualizing potential shifts between training and 
test sets (domain shift), and a high demand for sophisticated analysis into model behavior across diverse clinical 
scenarios, particularly in those cases deemed as "challenging".

In response to these clinical and technical challenges, in this research line I presented AUDIT, an open-source Python 
library designed to advance the evaluation of AI models in medical imaging. The main objective here is to 
develop a unified framework that supports both population-level and subject-level performance analysis, facilitates 
longitudinal performance assessment, and enables visualization of potential data shifts between training and testing.

- **C. Aumente-Maestro**, M. Müller, B. Remeseiro, J. Díez, M. Reyes, [AUDIT: An open-source Python library for AI model evaluation with use cases in MRI brain tumor segmentation](https://doi.org/10.1016/j.cmpb.2025.108991), Available at Computer Methods and Programs in Biomedicine - Elsevier Journal


Research ethics
======

I strongly believe in:

 * Open publishing
 * Papers with code
 * Diversity in research
 * Slowing down the publishing cycle
