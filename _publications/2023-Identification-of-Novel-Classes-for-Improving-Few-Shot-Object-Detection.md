---
title: "Identification of Novel Classes for Improving Few-Shot Object Detection"
collection: publications
permalink: /publication/2023-Identification-of-Novel-Classes-for-Improving-Few-Shot-Object-Detection
excerpt: 'Few-shot learning, object detection'
date: 2023-12-25
venue: 'International Conference on Computer Vision Workshops (ICCVW)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10350852'
citation: 'Zeyu Shangguan, Mohammad Rostami, &quot;Identification of Novel Classes for Improving Few-Shot Object Detection&quot; <i>2023 IEEE/CVF International Conference on Computer Vision Workshops (ICCVW)</i>, Paris, France, 2023, pp. 3348-3358, doi: 10.1109/ICCVW60793.2023.00360.'
---

Conventional training of deep neural networks requires a large number of the annotated image which is a laborious and time-consuming task, particularly for rare objects. Few-shot object detection (FSOD) methods offer a remedy by realizing robust object detection using only a few training samples per class. A challenge for FSOD is that instances from unlabeled novel classes that do not belong to the fixed set of training classes appear in the background. These objects behave similarly to label noise, leading to FSOD performance degradation. We develop a semi-supervised algorithm to detect and then utilize these unlabeled novel objects as positive samples during training to improve FSOD performance. Specifically, we propose a hierarchical ternary classification region proposal network (HTRPN) to localize the potential unlabeled novel objects and assign them new objectness labels. Our improved hierarchical sampling strategy for the region proposal network (RPN) also boosts the perception ability of the object detection model for large objects. Our experimental results indicate that our method is effective and outperforms the existing state-of-the-art (SOTA) FSOD methods.
