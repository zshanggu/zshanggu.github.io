---
title: "SCOOP'D: State-based Sim2Real Generative Policy for Generalizable Mixed-Liquid-Solid Scooping"
collection: publications
category: conferences
permalink: /publication/2026-SCOOPD-State-based-Sim2Real-Generative-Policy-for-Generalizable-Mixed-Liquid-Solid-Scooping
excerpt: 'Scooping'
date: 2026-01-31
venue: 'International Conference on Robotics and Automation (ICRA)'
paperurl: 'https://scoopdiff.github.io/'
citation: 'Kuanning Wang, Yongchong Gu, Yuqian Fu, Zeyu Shangguan, Sicheng He, Xiangyang Xue, Yanwei Fu, Daniel Seita (2026). &quot;SCOOP&#39D: State-based Sim2Real Generative Policy for Generalizable Mixed-Liquid-Solid Scooping.&quot; <i>ICRA</i>.'
---

Scooping items with tools such as spoons and ladles is common in daily life, ranging from assistive feeding to retrieving items from environmental disaster sites. However, developing a general and autonomous robotic scooping policy is challenging since it requires reasoning about complex tool-object interactions. Furthermore, scooping often involves manipulating deformable objects, such as granular media or liquids, which is challenging due to their infinite-dimensional configuration spaces and complex dynamics. We propose a method, SCOOP'D, which uses simulation from OmniGibson (built on NVIDIA Omniverse) to collect scooping demonstrations using algorithmic procedures that rely on privileged state information. Then, we use generative policies via diffusion to imitate demonstrations from observational input. We directly apply the learned policy in diverse real-world scenarios, testing its performance on various unseen item quantities, item characteristics, and container types. In zero-shot deployment, our method demonstrates promising results across 465 trials in diverse scenarios, including objects of different difficulty levels that we categorize as "Level 1" and "Level 2." SCOOP'D outperforms all baselines and ablations, suggesting that this is a promising approach to acquiring robotic scooping skills. We will post code, data and videos online after acceptance.