---
title: "Cross-Domain Few-Shot Object Detection via Enhanced Open-Set Object Detector"
collection: publications
category: conferences
permalink: /publication/2024-Cross-Domain-Few-Shot-Object-Detection-via-Enhanced-Open-Set-Object-Detector
excerpt: 'Cross-domain few-shot object detection'
date: 2024-09-29
venue: 'European Conference on Computer Vision (ECCV)'
paperurl: 'http://yuqianfu.com/CDFSOD-benchmark/'
citation: 'Yuqian Fu, Yu Wang, Yixuan Pan, Lian Huai, Xingyu Qiu, Zeyu Shangguan, Tong Liu, Yanwei Fu, Luc Van Gool, Xingqun Jiang. &quot;Cross-Domain Few-Shot Object Detection via Enhanced Open-Set Object Detector.&quot; <i>In European Conference on Computer Vision</i>, pp. 247-264. Springer, Cham, 2025.'
---

This paper studies the challenging cross-domain few-shot object detection (CD-FSOD), aiming to develop an accurate object detector for novel domains with minimal labeled examples. While transformer-based open-set detectors, such as DE-ViT, show promise in traditional few-shot object detection, their generalization to CD-FSOD remains unclear: 1 can such open-set detection methods easily generalize to CD-FSOD? 2 If not, how can models be enhanced when facing huge domain gaps? To answer the first question, we employ measures including style, inter-class variance (ICV), and indefinable boundaries (IB) to understand the domain gap. Based on these measures, we establish a new benchmark named CD-FSOD to evaluate object detection methods, revealing that most of the current approaches fail to generalize across domains. Technically, we observe that the performance decline is associated with our proposed measures: style, ICV, and IB. Consequently, we propose several novel modules to address these issues. First, the learnable instance features align initial fixed instances with target categories, enhancing feature distinctiveness. Second, the instance reweighting module assigns higher importance to high-quality instances with slight IB. Third, the domain prompter encourages features resilient to different styles by synthesizing imaginary domains without altering semantic contents. These techniques collectively contribute to the development of the Cross-Domain Vision Transformer for CD-FSOD (CD-ViTO), significantly improving upon the base DE-ViT. Experimental results validate the efficacy of our model.
