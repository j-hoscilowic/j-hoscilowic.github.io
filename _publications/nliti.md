---
title: "Non-Linear Inference Time Intervention Improving LLM Truthfulness"
collection: publications
permalink: /publication/nliti/
excerpt: 'Jakub Hoscilowicz, Adam Wiacek, Jan Chojnacki, Adam Cieslak, Leszek Michon, Vitalii Urbanevych, Artur Janicki'
venue: 'Interspeech 2024'
date: 2024-09-01
---
# abstract:
Large Language Models (LLM) are prone to returning false information. It constitutes one of major challenges in the AI field. In our work, we explore paradigm introduced by Inference-Time-Intervention (ITI). In the first stage, it identifies attention heads that contain the most relevant type of knowledge (e.g., truthful information). Afterwards, during inference, LLM activations are shifted for a chosen subset of attention heads. We further improved the ITI framework by introducing a nonlinear probing and multi-token intervention - Non-Linear ITI (NL-ITI). NL-ITI is tested on diverse multiple-choice benchmarks, including TruthfulQA, on which we report around 14% MC1 metric improvement with respect to the baseline ITI results. NL-ITI achieves also encouraging results on other testsets - on Business Ethics subdomain of MMLU, around 18% MC1 improvement over baseline LLaMA2-7B. Additionally, NL-ITI performs better while being less invasive in the behavior of LLM at the same time (as measured by Kullback-Leibler divergence).