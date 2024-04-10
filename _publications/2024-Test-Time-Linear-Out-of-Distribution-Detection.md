---
title: "Test-Time Linear Out-of-Distribution Detection"
collection: publications
permalink: /publication/2024-Test-Time-Linear-Out-of-Distribution Detection
excerpt: 'Out-of-Distribution'
date: 2024-02-27
venue: 'Conference on Computer Vision and Pattern Recognition (CVPR)'
paperurl: 'https://openreview.net/forum?id=q5EtUIyD5M'
citation: 'Ke Fan, Tong Liu, Xingyu Qiu, Yikai Wang, Lian Huai, Zeyu Shangguan, Shuang Gou, Fengjian Liu, Yuqian Fu, Yanwei Fu, Xingqun Jiang (2024). &quot;Test-Time Linear Out-of-Distribution Detection.&quot; <i>CVPR</i>.'
---

Out-of-Distribution (OOD) detection aims to address the excessive confidence prediction by neural networks by triggering an alert when the input sample deviates significantly from the training distribution (in-distribution), indicating that the output may not be reliable. Current OOD detection approaches explore all kinds of cues to identify OOD data, such as finding irregular patterns in the feature space, logit space, gradient space, or the raw image space. Surprisingly, we observe a linear trend between the OOD score produced by current OOD detection algorithms and the network features on several datasets. We conduct a thorough investigation, theoretically and empirically, to analyze and understand the meaning of such a linear trend in OOD detection. This paper proposes a Robust Test-time Linear method (RTL) to utilize such linear trends like a 'free lunch' when we have a batch of data to perform OOD detection. By using a simple linear regression as a test time adaptation, we can make a more precise OOD prediction. We further propose an online variant of the proposed method, which achieves promising performance and is more practical for real applications. Theoretical analysis is given to prove the effectiveness of our methods. Extensive experiments on several OOD datasets show the efficacy of RTL for OOD detection tasks, significantly improving the results of base OOD detectors.
