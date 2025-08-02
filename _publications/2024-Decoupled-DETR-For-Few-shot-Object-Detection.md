---
title: "Decoupled DETR For Few-shot Object Detection"
collection: publications
category: conferences
permalink: /publication/2024-Decoupled-DETR-For-Few-shot-Object-Detection
excerpt: 'Few-shot object detection'
date: 2024-12-08
venue: 'Asian Conference on Computer Vision (ACCV, <span style="color:blue">oral</span>)'
paperurl: 'https://openaccess.thecvf.com/content/ACCV2024/html/Shangguan_Decoupled_DETR_For_Few-shot_Object_Detection_ACCV_2024_paper.html'
citation: 'Zeyu Shangguan, Lian Huai, Tong Liu, Yuyu Liu, Xingqun Jiang (2024). &quot;Decoupled DETR For Few-shot Object Detection.&quot; <i>In Proceedings of the Asian Conference on Computer Vision</i>, pp. 286-302. 2024.'
---

Few-shot object detection (FSOD), an efficient method for addressing the severe data-hungry problem, has been extensively discussed. Current works have significantly advanced the problem in terms of model and data. However, the overall performance of most FSOD methods still does not fulfill the desired accuracy. In this paper we improve the FSOD model to address the severe issue of sample imbalance and weak feature propagation. To alleviate modeling bias from data-sufficient base classes, we examine the effect of decoupling the parameters for classes with sufficient data and classes with few samples in various ways. We design a base-novel categories decoupled DETR (DeDETR) for FSOD. We also explore various types of skip connection between the encoder and decoder for DETR. Besides, we notice that the best outputs could come from the intermediate layer of the decoder instead of the last layer; therefore, we build a unified decoder module that could dynamically fuse the decoder layers as the output feature. We evaluate our model on commonly used datasets such as PASCAL VOC and MSCOCO. Our results indicate that our proposed module could achieve stable improvements of 5% to 10% in both fine-tuning and meta-learning paradigms and has outperformed the highest score in recent works.
