# OneNet：一个无需微调的框架，利用大型语言模型提示实现少样本实体链接。

发布时间：2024年10月09日

`LLM应用` `知识图谱`

> OneNet: A Fine-Tuning Free Framework for Few-Shot Entity Linking via Large Language Model Prompting

# 摘要

> 实体链接 (EL) 是将模糊文本与知识库中特定实体关联的过程。传统方法依赖大型数据集，这在少样本场景下成为问题。为此，我们推出 OneNet，一个无需微调即可利用 LLM 少样本学习能力的创新框架。OneNet 包含三个关键组件：(1) 实体简化处理器，通过总结和过滤简化输入；(2) 双视角实体链接器，结合上下文和先验知识进行精确链接；(3) 实体共识判断器，采用独特算法减少推理中的幻觉。在七个基准数据集上的评估表明，OneNet 超越了现有最先进的方法。

> Entity Linking (EL) is the process of associating ambiguous textual mentions to specific entities in a knowledge base. Traditional EL methods heavily rely on large datasets to enhance their performance, a dependency that becomes problematic in the context of few-shot entity linking, where only a limited number of examples are available for training. To address this challenge, we present OneNet, an innovative framework that utilizes the few-shot learning capabilities of Large Language Models (LLMs) without the need for fine-tuning. To the best of our knowledge, this marks a pioneering approach to applying LLMs to few-shot entity linking tasks. OneNet is structured around three key components prompted by LLMs: (1) an entity reduction processor that simplifies inputs by summarizing and filtering out irrelevant entities, (2) a dual-perspective entity linker that combines contextual cues and prior knowledge for precise entity linking, and (3) an entity consensus judger that employs a unique consistency algorithm to alleviate the hallucination in the entity linking reasoning. Comprehensive evaluations across seven benchmark datasets reveal that OneNet outperforms current state-of-the-art entity linking methods.

[Arxiv](https://arxiv.org/abs/2410.07549)