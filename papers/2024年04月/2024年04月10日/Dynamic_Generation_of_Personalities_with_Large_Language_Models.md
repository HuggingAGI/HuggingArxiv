# 借助大型语言模型，实现个性化人格的动态塑造

发布时间：2024年04月10日

`LLM应用` `人工智能` `心理学`

> Dynamic Generation of Personalities with Large Language Models

# 摘要

> 在模拟人类决策的过程中，大型语言模型（LLMs）展现出了令人瞩目的表现，进一步凸显了这一研究领域的重要性。决策既受逻辑也受个性的影响。然而，过去的研究往往偏重于LLMs的逻辑推理，而忽略了个性特征的挖掘。在本项工作中，我们提出了一种名为动态个性生成（DPG）的创新方法，该方法基于超网络技术。我们首先将五大性格理论整合进GPT-4，构建了一个能够自动从对话中分析角色性格特质的性格评估系统。基于此，我们设计了一种新的性格生成能力评估指标。接着，我们利用这一评估系统对剧本对话进行评价，创建了一个性格-对话数据集。最终，我们在该数据集上对DPG进行了精细调优。实验结果显示，经过这一数据集调优后的DPG在个性生成方面的能力超越了传统的微调方法，甚至超过了基于提示的GPT-4。

> In the realm of mimicking human deliberation, large language models (LLMs) show promising performance, thereby amplifying the importance of this research area. Deliberation is influenced by both logic and personality. However, previous studies predominantly focused on the logic of LLMs, neglecting the exploration of personality aspects. In this work, we introduce Dynamic Personality Generation (DPG), a dynamic personality generation method based on Hypernetworks. Initially, we embed the Big Five personality theory into GPT-4 to form a personality assessment machine, enabling it to evaluate characters' personality traits from dialogues automatically. We propose a new metric to assess personality generation capability based on this evaluation method. Then, we use this personality assessment machine to evaluate dialogues in script data, resulting in a personality-dialogue dataset. Finally, we fine-tune DPG on the personality-dialogue dataset. Experiments prove that DPG's personality generation capability is stronger after fine-tuning on this dataset than traditional fine-tuning methods, surpassing prompt-based GPT-4.

[Arxiv](https://arxiv.org/abs/2404.07084)