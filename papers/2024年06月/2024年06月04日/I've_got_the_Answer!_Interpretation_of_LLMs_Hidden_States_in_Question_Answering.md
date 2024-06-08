# 揭秘“答案”：探索大型语言模型隐藏状态在问答任务中的奥秘

发布时间：2024年06月04日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）在知识问答场景下的解释机制，特别是模型行为的正误在隐藏层级的区分。研究使用了多种量化模型和数据集来验证其假设，并识别了对模型表现产生不利影响的层级。这属于对LLMs理论层面的研究，因此应归类为LLM理论。` `知识问答` `人工智能`

> I've got the "Answer"! Interpretation of LLMs Hidden States in Question Answering

# 摘要

> 随着LLMs的迅猛发展，AI的可解释性和可解释性日益受到重视。本文探讨了在知识问答场景下LLMs的解释机制。研究的核心假设是，模型行为的正误可在隐藏层级得以区分。我们运用了LLaMA-2-7B-Chat、Mistral-7B、Vicuna-7B等量化模型及MuSeRC数据集来验证这一假设，结果证实了我们的猜想。同时，我们识别出了那些对模型表现产生不利影响的层级。展望未来，我们建议对这些“薄弱”层进行额外训练，以期提升任务解决的精准度。

> Interpretability and explainability of AI are becoming increasingly important in light of the rapid development of large language models (LLMs). This paper investigates the interpretation of LLMs in the context of the knowledge-based question answering. The main hypothesis of the study is that correct and incorrect model behavior can be distinguished at the level of hidden states. The quantized models LLaMA-2-7B-Chat, Mistral-7B, Vicuna-7B and the MuSeRC question-answering dataset are used to test this hypothesis. The results of the analysis support the proposed hypothesis. We also identify the layers which have a negative effect on the model's behavior. As a prospect of practical application of the hypothesis, we propose to train such "weak" layers additionally in order to improve the quality of the task solution.

[Arxiv](https://arxiv.org/abs/2406.02060)