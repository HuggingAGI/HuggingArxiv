# LITO：为真实性优化而设计的可学习干预机制

发布时间：2024年04月30日

`LLM应用` `问答系统`

> LITO: Learnable Intervention for Truthfulness Optimization

# 摘要

> 大型语言模型（LLMs）虽能产出长篇连贯文本，却常出现事实性错误，影响了其可信度。为提高可靠性，研究者提出了一种推理阶段的方法，通过调整LLM的表示向“真实导向”靠拢，以引出真实的回答。但这种方法若一视同仁地应用，却难以适应多变的问题情境。我们引入了LITO，一种自动确定最佳干预强度的可学习干预方法，以适应不同上下文的真实性优化需求。LITO通过递增的干预强度生成模型序列，并在预测不确定性高时选择最准确的答案或选择不回答。在多个大型语言模型和问答数据集上的实验显示，LITO在确保任务准确性的同时，有效提升了回答的真实性。LITO的自适应特性克服了通用干预方法的局限，通过在模型信心充足时反映其内在知识，实现了模型真实性的最大化。

> Large language models (LLMs) can generate long-form and coherent text, but they still frequently hallucinate facts, thus limiting their reliability. To address this issue, inference-time methods that elicit truthful responses have been proposed by shifting LLM representations towards learned "truthful directions". However, applying the truthful directions with the same intensity fails to generalize across different question contexts. We propose LITO, a Learnable Intervention method for Truthfulness Optimization that automatically identifies the optimal intervention intensity tailored to a specific context. LITO explores a sequence of model generations based on increasing levels of intervention intensities. It selects the most accurate response or refuses to answer when the predictions are highly uncertain. Experiments on multiple LLMs and question-answering datasets demonstrate that LITO improves truthfulness while preserving task accuracy. The adaptive nature of LITO counters issues with one-size-fits-all intervention-based solutions, maximizing model truthfulness by reflecting internal knowledge only when the model is confident.

[Arxiv](https://arxiv.org/abs/2405.00301)