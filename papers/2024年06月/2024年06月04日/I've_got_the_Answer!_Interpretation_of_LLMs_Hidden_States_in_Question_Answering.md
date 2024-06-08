# 揭秘“答案”：探索大型语言模型在问答任务中隐藏状态的奥秘

发布时间：2024年06月04日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）在基于知识的问答任务中的解释机制，并通过对模型的隐藏状态进行分析来验证其假设。这种研究属于对LLMs内部工作机制的理论探讨，因此应归类为LLM理论。` `人工智能` `问答系统`

> I've got the "Answer"! Interpretation of LLMs Hidden States in Question Answering

# 摘要

> 随着大型语言模型（LLMs）的迅猛发展，AI的可解释性和可解释性日益受到重视。本文探讨了在基于知识的问答任务中，LLMs的解释机制。研究的核心假设是，模型行为的正确与否可在隐藏状态层面得以区分。我们运用量化模型LLaMA-2-7B-Chat、Mistral-7B、Vicuna-7B以及MuSeRC问答数据集验证了这一假设，并得到了支持。此外，我们还揭示了那些对模型性能产生不利影响的层级。展望未来，我们建议对这些“薄弱”层进行额外训练，以期提升任务解决的质量。

> Interpretability and explainability of AI are becoming increasingly important in light of the rapid development of large language models (LLMs). This paper investigates the interpretation of LLMs in the context of the knowledge-based question answering. The main hypothesis of the study is that correct and incorrect model behavior can be distinguished at the level of hidden states. The quantized models LLaMA-2-7B-Chat, Mistral-7B, Vicuna-7B and the MuSeRC question-answering dataset are used to test this hypothesis. The results of the analysis support the proposed hypothesis. We also identify the layers which have a negative effect on the model's behavior. As a prospect of practical application of the hypothesis, we propose to train such "weak" layers additionally in order to improve the quality of the task solution.

[Arxiv](https://arxiv.org/abs/2406.02060)