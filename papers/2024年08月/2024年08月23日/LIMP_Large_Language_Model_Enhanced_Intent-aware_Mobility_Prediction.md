# LIMP：借助大型语言模型，提升意图感知的移动预测能力

发布时间：2024年08月23日

`LLM应用` `城市规划` `交通管理`

> LIMP: Large Language Model Enhanced Intent-aware Mobility Prediction

# 摘要

> 人类流动性预测对城市规划和交通管理至关重要，但因行为背后的复杂隐含意图而颇具挑战。现有模型多聚焦于时空模式，对移动背后的意图关注不足。大型语言模型（LLMs）的进步为结合常识推理进行预测提供了新视角，但LLMs并非专为移动意图推理设计，且面临可扩展性和集成难题。为此，我们提出了LIMP框架，通过“分析-抽象-推断”（A2I）流程释放LLM的常识推理能力，并设计高效微调方案确保其可扩展性。我们还构建了基于transformer的意图感知预测模型。在真实数据集上的评估显示，LIMP在位置预测和意图推理方面表现卓越，其可解释性更凸显了实际应用潜力。相关代码和数据已公开在https://github.com/tsinghua-fib-lab/LIMP。

> Human mobility prediction is essential for applications like urban planning and transportation management, yet it remains challenging due to the complex, often implicit, intentions behind human behavior. Existing models predominantly focus on spatiotemporal patterns, paying less attention to the underlying intentions that govern movements. Recent advancements in large language models (LLMs) offer a promising alternative research angle for integrating commonsense reasoning into mobility prediction. However, it is a non-trivial problem because LLMs are not natively built for mobility intention inference, and they also face scalability issues and integration difficulties with spatiotemporal models. To address these challenges, we propose a novel LIMP (LLMs for Intent-ware Mobility Prediction) framework. Specifically, LIMP introduces an "Analyze-Abstract-Infer" (A2I) agentic workflow to unleash LLM's commonsense reasoning power for mobility intention inference. Besides, we design an efficient fine-tuning scheme to transfer reasoning power from commercial LLM to smaller-scale, open-source language model, ensuring LIMP's scalability to millions of mobility records. Moreover, we propose a transformer-based intention-aware mobility prediction model to effectively harness the intention inference ability of LLM. Evaluated on two real-world datasets, LIMP significantly outperforms baseline models, demonstrating improved accuracy in next-location prediction and effective intention inference. The interpretability of intention-aware mobility prediction highlights our LIMP framework's potential for real-world applications. Codes and data can be found in https://github.com/tsinghua-fib-lab/LIMP .

[Arxiv](https://arxiv.org/abs/2408.12832)