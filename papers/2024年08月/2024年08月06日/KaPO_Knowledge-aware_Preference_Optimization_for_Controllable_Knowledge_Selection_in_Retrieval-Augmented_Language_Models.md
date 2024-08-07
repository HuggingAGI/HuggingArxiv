# KaPO：增强检索语言模型中，针对可控知识选择的知识感知偏好优化方案

发布时间：2024年08月06日

`LLM应用` `人工智能` `知识管理`

> KaPO: Knowledge-aware Preference Optimization for Controllable Knowledge Selection in Retrieval-Augmented Language Models

# 摘要

> 结合外部知识，RAG 有效缓解了 LLM 在知识密集型任务中的幻觉问题。但在整合内外知识时，知识冲突难免，影响模型响应。为提升 LLM 的知识选择能力，研究者尝试通过指令调优优化其行为。然而，缺乏明确负面信号和比较目标，模型在复杂检索场景中仍可能表现不佳。为此，我们提出 KaPO，旨在实现真实场景中的可控知识选择。我们探索并模拟不同上下文中的错误类型，通过偏好优化学习避免负面信号。同时，平衡响应长度与偏好数据比例，增强 LLM 的遵循能力和抗噪鲁棒性。实验表明，KaPO 在处理知识冲突上优于以往方法 37% 以上，且在多种分布外数据集上泛化能力强。

> By integrating external knowledge, Retrieval-Augmented Generation (RAG) has become an effective strategy for mitigating the hallucination problems that large language models (LLMs) encounter when dealing with knowledge-intensive tasks. However, in the process of integrating external non-parametric supporting evidence with internal parametric knowledge, inevitable knowledge conflicts may arise, leading to confusion in the model's responses. To enhance the knowledge selection of LLMs in various contexts, some research has focused on refining their behavior patterns through instruction-tuning. Nonetheless, due to the absence of explicit negative signals and comparative objectives, models fine-tuned in this manner may still exhibit undesirable behaviors in the intricate and realistic retrieval scenarios. To this end, we propose a Knowledge-aware Preference Optimization, dubbed KaPO, aimed at achieving controllable knowledge selection in real retrieval scenarios. Concretely, we explore and simulate error types across diverse context combinations and learn how to avoid these negative signals through preference optimization methods. Simultaneously, by adjusting the balance between response length and the proportion of preference data representing different behavior patterns, we enhance the adherence capabilities and noise robustness of LLMs in a balanced manner. Experimental results show that KaPO outperforms previous methods for handling knowledge conflicts by over 37%, while also exhibiting robust generalization across various out-of-distribution datasets.

[Arxiv](https://arxiv.org/abs/2408.03297)