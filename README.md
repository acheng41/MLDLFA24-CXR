# Final Project Repository for EN.601.482/682 Deep Learning Fall 2024

## Domain Generalization for Chest X-Ray Imaging
Group 7: Rena Bi, Andrea Cheng, Emily Guan, Aprina Wang


### Background and Prior Work
 In real-world healthcare settings, variations in imaging practices create domain shifts that can reduce the model performance when applied to new clinical sites. Challenges in medical data privacy make collecting comprehensive datasets from all domains infeasible, and labeling datasets can be extremely labor intensive. Our goal is to design a domain-generalizable classification model to identify 3 pathological states on chest X-rays: pneumonia, non-pneumonia disease, and normal.  

Overall, previous work focuses on two aspects for domain generalization of medical imaging data: architecture and training scheme. A skin lesion classification model introduced latent feature learning, and another Chest X-Ray model created image and feature-level perturbations. Other work modifies the training scheme to mock domain generalization, like using semi-supervised training and different domains in episodic training. Thus, we can make modifications to the architecture and training style to enhance generalizability.


### Repository Details

* alexnet_baseline.ipynb : negative and positive controls trained on AlexNet Backbone
* srm_il_fl.ipynb : SRM model with Image-Level (IL) and Feature-Level (FL) perturnbations
* episodic_srm_il_fl.ipynb : Episodic Training Scheme on SRM model
* model_comparison.ipynb : Plotting Training Metrics and Results

---
2024 Rena Bi, Andrea Cheng, Emily Guan, Aprina Wang supervised by Xuzhe Zhi and Dr. Mathias Unberath



