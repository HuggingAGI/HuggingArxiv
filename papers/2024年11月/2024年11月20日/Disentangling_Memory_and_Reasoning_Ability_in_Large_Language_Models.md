# 解析大型语言模型中的记忆与推理能力

发布时间：2024年11月20日

`LLM应用` `语言模型`

> Disentangling Memory and Reasoning Ability in Large Language Models

# 摘要

> 大型语言模型（LLMs）在应对既需广博知识又要推理能力的复杂任务时，展现出了强劲的性能。然而，当下的 LLM 推理流程运作不透明，知识检索与推理步骤之间未作明确区分，致使模型的决策过程含混不清、杂乱无章。这种模糊状况可能引发诸如幻觉和知识遗忘之类的问题，严重影响了 LLMs 在高风险领域的可靠性。在本文中，我们提出了一种全新的推理模式，将复杂的推理过程拆解为两个清晰且不同的动作：（1）记忆召回：用于检索相关知识；（2）推理：依据召回的知识进行逻辑步骤的操作。为推动这种拆解，我们引入了两个特殊标记“memory”和“reason”，引导模型区分需要知识检索的步骤和涉及推理的步骤。我们的实验结果显示，这种拆解不但提升了模型性能，还增强了推理过程的可解释性，让用户能够找出错误源头并有效优化模型响应。相关代码可在 https://github.com/MingyuJ666/Disentangling-Memory-and-Reasoning 获取。

> Large Language Models (LLMs) have demonstrated strong performance in handling complex tasks requiring both extensive knowledge and reasoning abilities. However, the existing LLM inference pipeline operates as an opaque process without explicit separation between knowledge retrieval and reasoning steps, making the model's decision-making process unclear and disorganized. This ambiguity can lead to issues such as hallucinations and knowledge forgetting, which significantly impact the reliability of LLMs in high-stakes domains. In this paper, we propose a new inference paradigm that decomposes the complex inference process into two distinct and clear actions: (1) memory recall: which retrieves relevant knowledge, and (2) reasoning: which performs logical steps based on the recalled knowledge. To facilitate this decomposition, we introduce two special tokens memory and reason, guiding the model to distinguish between steps that require knowledge retrieval and those that involve reasoning. Our experiment results show that this decomposition not only improves model performance but also enhances the interpretability of the inference process, enabling users to identify sources of error and refine model responses effectively. The code is available at https://github.com/MingyuJ666/Disentangling-Memory-and-Reasoning.

[Arxiv](https://arxiv.org/abs/2411.13504)