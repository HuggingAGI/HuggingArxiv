# ORAN-Bench-13K：一款开源基准，专为评估大型语言模型在开放无线接入网络中的表现而设计。

发布时间：2024年07月08日

`LLM应用` `网络分析`

> ORAN-Bench-13K: An Open Source Benchmark for Assessing LLMs in Open Radio Access Networks

# 摘要

> 大型语言模型 (LLM) 通过提升网络分析、异常检测和代码生成能力，显著增强了开放无线接入网络 (O-RAN) 的效率和可靠性，从而革新了其部署与运营方式。本文介绍了首个针对 O-RAN 背景下 LLM 性能评估的综合基准——ORAN-Bench-13K，包含从 116 份规范文档中精选的 13,952 道多选题。我们采用创新的三阶段 LLM 框架，将问题按难度分类，全面覆盖 ORAN 知识。通过评估 Gemini、Chat-GPT 和 Mistral 等顶尖 LLM，我们发现当前主流模型在 O-RAN 领域表现不佳，凸显了定制模型的需求。引入基于 RAG 的 ORANSight 管道后，性能显著提升，宏精度与加权精度分别达到 0.784 和 0.776，平均优于其他 LLM 21.55% 和 22.59%。

> Large Language Models (LLMs) can revolutionize how we deploy and operate Open Radio Access Networks (O-RAN) by enhancing network analytics, anomaly detection, and code generation and significantly increasing the efficiency and reliability of a plethora of O-RAN tasks. In this paper, we present ORAN-Bench-13K, the first comprehensive benchmark designed to evaluate the performance of Large Language Models (LLMs) within the context of O-RAN. Our benchmark consists of 13,952 meticulously curated multiple-choice questions generated from 116 O-RAN specification documents. We leverage a novel three-stage LLM framework, and the questions are categorized into three distinct difficulties to cover a wide spectrum of ORAN-related knowledge. We thoroughly evaluate the performance of several state-of-the-art LLMs, including Gemini, Chat-GPT, and Mistral. Additionally, we propose ORANSight, a Retrieval-Augmented Generation (RAG)-based pipeline that demonstrates superior performance on ORAN-Bench-13K compared to other tested closed-source models. Our findings indicate that current popular LLM models are not proficient in O-RAN, highlighting the need for specialized models. We observed a noticeable performance improvement when incorporating the RAG-based ORANSight pipeline, with a Macro Accuracy of 0.784 and a Weighted Accuracy of 0.776, which was on average 21.55% and 22.59% better than the other tested LLMs.

[Arxiv](https://arxiv.org/abs/2407.06245)