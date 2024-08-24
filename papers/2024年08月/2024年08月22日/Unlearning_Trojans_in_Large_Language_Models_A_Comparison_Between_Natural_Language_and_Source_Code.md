# 大型语言模型中特洛伊木马的消除：自然语言与源代码的对比研究

发布时间：2024年08月22日

`LLM应用` `网络安全` `人工智能`

> Unlearning Trojans in Large Language Models: A Comparison Between Natural Language and Source Code

# 摘要

> 本研究探索了机器遗忘 (MU) 在减轻传统大型语言模型（包括自然语言模型 Text-LLMs 和代码模型 Code-LLMs）中嵌入的特洛伊木马影响的应用。我们创新性地提出了 LYA 方法，结合梯度上升和基于 Fisher 信息矩阵的弹性权重巩固技术，有效从受污染模型中移除特洛伊木马。通过对比 LYA 与微调、重训练等传统技术，我们发现 LYA 在保护模型原始功能的同时，更有效地消除了特洛伊木马的影响。这是首次在自然语言和编码领域对 LLMs 中的特洛伊木马遗忘进行深入比较的研究。

> This work investigates the application of Machine Unlearning (MU) for mitigating the impact of trojans embedded in conventional large language models of natural language (Text-LLMs) and large language models of code (Code-LLMs) We propose a novel unlearning approach, LYA, that leverages both gradient ascent and elastic weight consolidation, a Fisher Information Matrix (FIM) based regularization technique, to unlearn trojans from poisoned models. We compare the effectiveness of LYA against conventional techniques like fine-tuning, retraining, and vanilla gradient ascent. The subject models we investigate are BERT and CodeBERT, for sentiment analysis and code defect detection tasks, respectively. Our findings demonstrate that the combination of gradient ascent and FIM-based regularization, as done in LYA, outperforms existing methods in removing the trojan's influence from the poisoned model, while preserving its original functionality. To the best of our knowledge, this is the first work that compares and contrasts MU of trojans in LLMs, in the NL and Coding domain.

[Arxiv](https://arxiv.org/abs/2408.12416)