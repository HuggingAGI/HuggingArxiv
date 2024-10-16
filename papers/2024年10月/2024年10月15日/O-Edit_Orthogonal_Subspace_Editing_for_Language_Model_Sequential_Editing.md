# O-Edit：一种用于语言模型序列编辑的正交子空间编辑方法

发布时间：2024年10月15日

`LLM理论` `人工智能`

> O-Edit: Orthogonal Subspace Editing for Language Model Sequential Editing

# 摘要

> 大型语言模型（LLM）在预训练中获取知识，但随着时间推移，这些知识可能变得不准确或过时，需要更新。现有的知识编辑技术无需重新训练，但大多仅适用于单次编辑，且多次编辑会导致模型性能下降。为此，我们提出了正交子空间编辑（O-Edit），通过正交化每次更新的方向，减少连续更新间的干扰，并降低对无关知识的影响。O-Edit 无需重放历史数据，能高效处理每次编辑，并在主流 LLM 上实现数千次编辑，平均性能提升是现有方法的 4.2 倍，同时保持下游任务性能，且额外参数开销极小。

> Large language models (LLMs) acquire knowledge during pre-training, but over time, this knowledge may become incorrect or outdated, necessitating updates after training. Knowledge editing techniques address this issue without the need for costly re-training. However, most existing methods are designed for single edits, and as the number of edits increases, they often cause a decline in the model's overall performance, posing significant challenges for sequential editing. To overcome this, we propose Orthogonal Subspace Editing, O-Edit. This algorithm orthogonalizes the direction of each knowledge update, minimizing interference between successive updates and reducing the impact of new updates on unrelated knowledge. Our approach does not require replaying previously edited data and processes each edit knowledge on time. It can perform thousands of edits on mainstream LLMs, achieving an average performance improvement that is 4.2 times better than existing methods while effectively preserving the model's performance on downstream tasks, all with minimal additional parameter overhead.

[Arxiv](https://arxiv.org/abs/2410.11469)