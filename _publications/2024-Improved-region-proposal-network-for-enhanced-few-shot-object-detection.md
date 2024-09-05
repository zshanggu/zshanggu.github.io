---
title: "Improved Region Proposal Network for Enhanced Few-shot Object Detection"
collection: publications
permalink: /publication/2024-Improved-region-proposal-network-for-enhanced-few-shot-object-detection
excerpt: 'Few-shot object detection'
date: 2024-09-03
venue: 'Neural Networks (NeuNet)'
paperurl: 'https://doi.org/10.1016/j.neunet.2024.106699'
citation: 'Zeyu Shangguan, Mohammad Rostami, &quot;Improved Region Proposal Network for Enhanced Few-shot Object Detection.&quot; <i>Neural Networks</i>, vol. 2024, 106699, 0893-6080, 2024.'


---

Despite significant success of deep learning in object detection tasks, the standard training of deep neural networks requires access to a substantial quantity of annotated images across all classes. Data annotation is an arduous and time-consuming endeavor, particularly when dealing with infrequent objects. Few-shot object detection (FSOD) methods have emerged as a solution to the limitations of classic object detection approaches based on deep learning. FSOD methods demonstrate remarkable performance by achieving robust object detection using a significantly smaller amount of training data. A challenge for FSOD is that instances from novel classes that do not belong to the fixed set of training classes appear in the background and the base model may pick them up as potential objects. These objects behave similarly to label noise because they are classified as one of the training dataset classes, leading to FSOD performance degradation. We develop a semi-supervised algorithm to detect and then utilize these unlabeled novel objects as positive samples during the FSOD training stage to improve FSOD performance. Specifically, we develop a hierarchical ternary classification region proposal network (HTRPN) to localize the potential unlabeled novel objects and assign them new objectness labels to distinguish these objects from the base training dataset classes. Our improved hierarchical sampling strategy for the region proposal network (RPN) also boosts the perception ability of the object detection model for large objects. We test our approach and COCO and PASCAL VOC baselines that are commonly used in FSOD literature. Our experimental results indicate that our method is effective and outperforms the existing state-of-the-art (SOTA) FSOD methods.
