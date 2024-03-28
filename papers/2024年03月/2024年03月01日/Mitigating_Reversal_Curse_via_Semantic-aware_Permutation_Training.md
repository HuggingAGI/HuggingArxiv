# 为了解决反转诅咒问题，我们提出了一种基于语义感知排列训练的方法。该方法通过精心设计的训练策略，能够有效抑制模型在处理特定任务时出现的反转诅咒效应，从而提升模型性能和鲁棒性。

发布时间：2024年03月01日

`LLM理论`

> Mitigating Reversal Curse via Semantic-aware Permutation Training

# 摘要

> 虽然LLMs在众多任务上表现出色，但最近研究揭示它们遭遇了“反转难题”，例如模型能理解“A的父亲是B”，却难以推理出“B的孩子是A”。这一局限阻碍了AGI的进步，暴露了模型在双向推理理解与运用中的短板。本文通过详尽评估发现，“反转难题”的根源在于训练和推断阶段间的词序差异，具体表现为因果性语言模型在预测训练数据中的先行词时能力欠佳。为此，我们提出采用排列训练数据的方法来应对这个问题，但这可能导致完整短语或实体被打乱，加大模型理解和学习训练数据的难度。因此，我们创新设计了语义感知排列训练（SPT），借助辅助语言模型将训练句切割成有意义的单元（实体或短语），并在此基础上重新排列后输入模型。广泛的实验证明，SPT能够有效缓解反转难题，使得模型在反转问题上的表现接近正向问题，并且显著提升现有技术的性能水平。

> While large language models (LLMs) have achieved impressive performance across diverse tasks, recent studies showcase that causal LLMs suffer from the "reversal curse". It is a typical example that the model knows "A's father is B", but is unable to reason "B's child is A". This limitation poses a challenge to the advancement of artificial general intelligence (AGI), as it suggests a gap in the models' ability to comprehend and apply bidirectional reasoning. In this paper, we first conduct substantial evaluation and identify that the root cause of the reversal curse lies in the different word order between the training and inference stage, namely, the poor ability of causal language models to predict antecedent words within the training data. Accordingly, permutation on the training data is considered as a potential solution, since this can make the model predict antecedent words or tokens. However, previous permutation methods may disrupt complete phrases or entities, thereby posing challenges for the model to comprehend and learn from training data. To address this issue, we propose Semantic-aware Permutation Training (SPT), which addresses this issue by segmenting the training sentences into semantic units (i.e., entities or phrases) with an assistant language model and permuting these units before feeding into the model. Extensive experiments demonstrate that SPT effectively mitigates the reversal curse since the performance on reversed questions approximates that on the forward ones, and significantly advances the performance of existing works.

[Arxiv](https://arxiv.org/abs/2403.00758)