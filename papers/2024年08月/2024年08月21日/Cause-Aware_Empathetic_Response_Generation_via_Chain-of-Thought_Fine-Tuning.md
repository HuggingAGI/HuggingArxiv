# 基于链式思维微调，实现因果感知的共情响应生成

发布时间：2024年08月21日

`LLM应用` `人工智能` `情感分析`

> Cause-Aware Empathetic Response Generation via Chain-of-Thought Fine-Tuning

# 摘要

> 共情反应生成使代理能够理解对话情境并回应情感表达。以往研究多依赖情感标签，却忽视了情感原因推理的关键作用，限制了模型的情感理解和推理能力。本文提出一种结合情感与原因的共情生成方法，通过在大型语言模型（LLM）上设计思维链（CoT）提示，有效提升LLM的共情表现，并通过指令调整增强共情听众的角色意识。同时，引入来自COMET的面向原因的外部知识，既增加生成多样性，又缓解了知识冲突。实验显示，该方法在LLaMA-7b上实现了自动和人工评估的双重领先性能。

> Empathetic response generation endows agents with the capability to comprehend dialogue contexts and react to expressed emotions. Previous works predominantly focus on leveraging the speaker's emotional labels, but ignore the importance of emotion cause reasoning in empathetic response generation, which hinders the model's capacity for further affective understanding and cognitive inference. In this paper, we propose a cause-aware empathetic generation approach by integrating emotions and causes through a well-designed Chain-of-Thought (CoT) prompt on Large Language Models (LLMs). Our approach can greatly promote LLMs' performance of empathy by instruction tuning and enhancing the role awareness of an empathetic listener in the prompt. Additionally, we propose to incorporate cause-oriented external knowledge from COMET into the prompt, which improves the diversity of generation and alleviates conflicts between internal and external knowledge at the same time. Experimental results on the benchmark dataset demonstrate that our approach on LLaMA-7b achieves state-of-the-art performance in both automatic and human evaluations.

[Arxiv](https://arxiv.org/abs/2408.11599)