---
layout: post
title:  "DP-SGD vs PATE: Which Has Less Disparate Impact on Model Accuracy?"
date:   2021-10-27 22:21:59 +00:00
image: /images/jcdl2019.png
categories: research
author: "Sasikanth Kotti"
authors: "Archit Uniyal, Rakshit Naidu, <strong>Sasikanth Kotti</strong>, Sahib Singh, Patrik Joslin Kenfack, Fatemehsadat Mireshghallah, Andrew Trask"
venue: "International Conference on Machine Learning (2021) Workshop - ML4data"
arxiv: https://arxiv.org/abs/2106.12576
slides: /pdfs/DP-SGD vs PATE_ Which Has Less Disparate Impact on Model Accuracy_.pdf
code: https://github.com/sahibsin/Private_ClassImbalance
---
Recent advances in differentially private deep learning have demonstrated that application of differential privacy– specifically the DP-SGD algorithm– has a disparate impact on different sub-groups in the population, which leads to a significantly high drop-in model utility for subpopulations that are under-represented (minorities), compared to well-represented ones. In this work, we aim to compare PATE, another mechanism for training deep learning models using differential privacy, with DP-SGD in terms of fairness. We show that PATE does have a disparate impact too, however, it is much less severe than DP-SGD. We draw insights from this observation on what might be promising directions in achieving better fairness-privacy trade-offs

