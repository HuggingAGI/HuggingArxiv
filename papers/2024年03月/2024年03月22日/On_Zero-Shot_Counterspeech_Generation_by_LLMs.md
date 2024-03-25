# 探讨LLMs在零样本情境下生成反仇恨言论的能力

发布时间：2024年03月22日

`LLM应用` `社交媒体/在线言论安全`

> On Zero-Shot Counterspeech Generation by LLMs

> 随着众多LLM的出现，它们在多种NLP应用中的运用日益广泛。在对抗性言论生成这一重要任务上，尽管人们已尝试通过利用仇恨言论-对抗性言论对对LLM进行微调以构建生成模型，但鲜有研究深入探究LLM在零样本场景下的固有特性。本次研究首次系统评估了GPT-2、DialoGPT、ChatGPT及FlanT5四种LLM在零样本环境下对抗性言论生成的表现。尤其对GPT-2和DialoGPT，我们进一步考察了不同规模（小型、中型、大型）下模型性能的变化。同时，我们创新性地提出三种不同的提示策略，以生成不同类型的对抗性言论，并分析了这些策略对各模型性能的影响。结果显示，在部分数据集中（提升17%），模型生成质量得到改善，但随着模型规模增大，生成内容的毒性也随之上升（增加25%）。从模型种类上看，GPT-2和FlanT5在对抗性言论质量上表现出色，但也较DialoGPT具有更高的毒性；而ChatGPT则在各项指标上均展现出卓越的对抗性言论生成能力。此外，我们发现所提出的提示策略能够有效提升各类模型在对抗性言论生成上的整体表现。

> With the emergence of numerous Large Language Models (LLM), the usage of such models in various Natural Language Processing (NLP) applications is increasing extensively. Counterspeech generation is one such key task where efforts are made to develop generative models by fine-tuning LLMs with hatespeech - counterspeech pairs, but none of these attempts explores the intrinsic properties of large language models in zero-shot settings. In this work, we present a comprehensive analysis of the performances of four LLMs namely GPT-2, DialoGPT, ChatGPT and FlanT5 in zero-shot settings for counterspeech generation, which is the first of its kind. For GPT-2 and DialoGPT, we further investigate the deviation in performance with respect to the sizes (small, medium, large) of the models. On the other hand, we propose three different prompting strategies for generating different types of counterspeech and analyse the impact of such strategies on the performance of the models. Our analysis shows that there is an improvement in generation quality for two datasets (17%), however the toxicity increase (25%) with increase in model size. Considering type of model, GPT-2 and FlanT5 models are significantly better in terms of counterspeech quality but also have high toxicity as compared to DialoGPT. ChatGPT are much better at generating counter speech than other models across all metrics. In terms of prompting, we find that our proposed strategies help in improving counter speech generation across all the models.

[Arxiv](https://arxiv.org/abs/2403.14938)