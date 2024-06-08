# 揭秘“答案”：探索大型语言模型隐藏状态在问答任务中的奥秘

发布时间：2024年06月04日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在基于知识的问答任务中的解释机制，通过分析模型的隐藏状态来理解其行为。这种研究属于对LLMs内部工作机制的理论分析，旨在提高模型的可解释性和性能，因此归类为LLM理论。` `人工智能` `问答系统`

> I've got the "Answer"! Interpretation of LLMs Hidden States in Question Answering

# 摘要

> 随着大型语言模型（LLMs）的迅猛发展，AI的可解释性和可解释性日益受到重视。本文探讨了在基于知识的问答任务中，LLMs的解释机制。研究的核心假设是，通过分析模型的隐藏状态，可以辨别其行为的正确与否。我们采用了LLaMA-2-7B-Chat、Mistral-7B、Vicuna-7B等量化模型，并结合MuSeRC问答数据集进行验证。研究结果证实了我们的假设，并揭示了哪些层级对模型性能产生不利影响。展望未来，我们建议对这些“薄弱”层进行额外训练，以期提升问答任务的解决质量。

> Interpretability and explainability of AI are becoming increasingly important in light of the rapid development of large language models (LLMs). This paper investigates the interpretation of LLMs in the context of the knowledge-based question answering. The main hypothesis of the study is that correct and incorrect model behavior can be distinguished at the level of hidden states. The quantized models LLaMA-2-7B-Chat, Mistral-7B, Vicuna-7B and the MuSeRC question-answering dataset are used to test this hypothesis. The results of the analysis support the proposed hypothesis. We also identify the layers which have a negative effect on the model's behavior. As a prospect of practical application of the hypothesis, we propose to train such "weak" layers additionally in order to improve the quality of the task solution.

[Arxiv](https://arxiv.org/abs/2406.02060)