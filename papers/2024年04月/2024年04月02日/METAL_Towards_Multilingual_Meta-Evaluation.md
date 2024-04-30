# METAL：探索多语言元评估的新境界

发布时间：2024年04月02日

`LLM应用` `评估工具`

> METAL: Towards Multilingual Meta-Evaluation

# 摘要

> 随着大型语言模型（LLMs）在各种任务中精准度的不断提升，它们在现实世界应用中的运用也日益广泛。多项研究证实，LLMs在众多标准的自然语言处理（NLP）基准测试中表现优异。然而，由于测试数据集的污染问题和传统评估标准的局限，对LLMs的评估变得复杂。鉴于收集人类评估的难度，社区越来越倾向于利用LLMs作为主观度量的无参考评估工具。但先前研究指出，基于LLM的评估器可能存在偏见，且与人类判断的契合度不高。本研究提出了一个用于全面评估多语言环境下LLMs作为评估器的框架。我们构建了一个精心设计的数据集，覆盖10种语言，包含了母语者对摘要任务的评估。该数据集专为评估基于LLM的评估器而设计，我们称之为元评估（METAL）。我们对比了采用GPT-3.5-Turbo、GPT-4和PaLM2构建的基于LLM的评估器的性能。研究发现，基于GPT-4的评估器在跨语言评估中表现最佳，而GPT-3.5-Turbo的表现不尽人意。此外，我们对基于LLM的评估器提供的推理分析表明，其推理往往与人类裁判的推理不一致。

> With the rising human-like precision of Large Language Models (LLMs) in numerous tasks, their utilization in a variety of real-world applications is becoming more prevalent. Several studies have shown that LLMs excel on many standard NLP benchmarks. However, it is challenging to evaluate LLMs due to test dataset contamination and the limitations of traditional metrics. Since human evaluations are difficult to collect, there is a growing interest in the community to use LLMs themselves as reference-free evaluators for subjective metrics. However, past work has shown that LLM-based evaluators can exhibit bias and have poor alignment with human judgments. In this study, we propose a framework for an end-to-end assessment of LLMs as evaluators in multilingual scenarios. We create a carefully curated dataset, covering 10 languages containing native speaker judgments for the task of summarization. This dataset is created specifically to evaluate LLM-based evaluators, which we refer to as meta-evaluation (METAL). We compare the performance of LLM-based evaluators created using GPT-3.5-Turbo, GPT-4, and PaLM2. Our results indicate that LLM-based evaluators based on GPT-4 perform the best across languages, while GPT-3.5-Turbo performs poorly. Additionally, we perform an analysis of the reasoning provided by LLM-based evaluators and find that it often does not match the reasoning provided by human judges.

![METAL：探索多语言元评估的新境界](../../../paper_images/2404.01667/x1.png)

![METAL：探索多语言元评估的新境界](../../../paper_images/2404.01667/x2.png)

![METAL：探索多语言元评估的新境界](../../../paper_images/2404.01667/x3.png)

![METAL：探索多语言元评估的新境界](../../../paper_images/2404.01667/x4.png)

![METAL：探索多语言元评估的新境界](../../../paper_images/2404.01667/x5.png)

![METAL：探索多语言元评估的新境界](../../../paper_images/2404.01667/x6.png)

![METAL：探索多语言元评估的新境界](../../../paper_images/2404.01667/x7.png)

![METAL：探索多语言元评估的新境界](../../../paper_images/2404.01667/x8.png)

![METAL：探索多语言元评估的新境界](../../../paper_images/2404.01667/x9.png)

![METAL：探索多语言元评估的新境界](../../../paper_images/2404.01667/x10.png)

[Arxiv](https://arxiv.org/abs/2404.01667)