---
title: "Latent-based diffusion model for long-tailed recognition"
collection: publications
category: conferences
permalink: /publication/2024-cvprw
excerpt: 'Long-tailed imbalance distribution is a common issue in practical computer vision applications. Previous works proposed methods to address this problem which can be categorized into several classes: re-sampling re-weighting transfer learning and feature augmentation. In recent years diffusion models have shown an impressive generation ability in many sub-problems of deep computer vision. However its powerful generation has not been explored in long-tailed problems. We propose a new approach the Latent-based Diffusion Model for Long-tailed Recognition (LDMLR) as a feature augmentation method to tackle the issue. First we encode the imbalanced dataset into features using the baseline model. Then we train a Denoising Diffusion Implicit Model (DDIM) using these encoded features to generate pseudo-features. Finally we train the classifier using the encoded and pseudo-features from the previous two steps. The models accuracy shows an improvement on the CIFAR-LT and ImageNet-LT datasets by using the proposed method.'
date: 2024-06-11
venue: 'CVPR Workshop'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2024W/L3D-IVU/papers/Han_Latent-based_Diffusion_Model_for_Long-tailed_Recognition_CVPRW_2024_paper.pdf'
bibtexurl: 'http://academicpages.github.io/files/cvprw2024.bib'
citation: 'Han, Pengxiao, Changkun Ye, Jieming Zhou, Jing Zhang, Jie Hong, and Xuesong Li. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 2639-2648. 2024.'
---