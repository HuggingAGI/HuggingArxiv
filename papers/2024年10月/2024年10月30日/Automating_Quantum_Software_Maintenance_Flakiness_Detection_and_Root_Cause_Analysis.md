# 实现量子软件维护的自动化：脆弱性检测与根本原因剖析

发布时间：2024年10月30日

`LLM应用` `软件工程` `量子软件`

> Automating Quantum Software Maintenance: Flakiness Detection and Root Cause Analysis

# 摘要

> 不稳定测试，即在代码未变的情况下通过或失败情况不稳定，因其复杂性和概率性，在软件工程尤其是量子软件工程中是个重大挑战，会引发隐藏问题，浪费开发者精力。
  我们打算创建一个能检测量子软件中不稳定测试的自动化框架以及一个扩展的量子不稳定测试数据集，以克服手动方法的局限。
  基于对 14 个量子软件库的先前手动分析，我们扩充了数据集，并利用转换器和余弦相似度实现了不稳定测试检测的自动化。我们用来自 OpenAI GPT 和 Meta LLaMA 系列的大型语言模型（LLMs）做实验，评估它们从代码和问题描述中检测及分类不稳定测试的能力。
  嵌入转换器效果显著：我们发现了 25 个新的不稳定测试，使数据集扩充了 54%。顶级 LLMs 在不稳定检测方面的 F1 分数达 0.8871，但在根本原因识别方面仅为 0.5839。
  我们引入了借助机器学习的自动化不稳定测试检测框架，成果喜人，但也凸显出在大型量子代码库中改进根本原因检测和分类的必要性。未来工作将聚焦于优化检测技术和开发自动不稳定测试修复手段。

> Flaky tests, which pass or fail inconsistently without code changes, are a major challenge in software engineering in general and in quantum software engineering in particular due to their complexity and probabilistic nature, leading to hidden issues and wasted developer effort.
  We aim to create an automated framework to detect flaky tests in quantum software and an extended dataset of quantum flaky tests, overcoming the limitations of manual methods.
  Building on prior manual analysis of 14 quantum software repositories, we expanded the dataset and automated flaky test detection using transformers and cosine similarity. We conducted experiments with Large Language Models (LLMs) from the OpenAI GPT and Meta LLaMA families to assess their ability to detect and classify flaky tests from code and issue descriptions.
  Embedding transformers proved effective: we identified 25 new flaky tests, expanding the dataset by 54%. Top LLMs achieved an F1-score of 0.8871 for flakiness detection but only 0.5839 for root cause identification.
  We introduced an automated flaky test detection framework using machine learning, showing promising results but highlighting the need for improved root cause detection and classification in large quantum codebases. Future work will focus on improving detection techniques and developing automatic flaky test fixes.

[Arxiv](https://arxiv.org/abs/2410.23578)