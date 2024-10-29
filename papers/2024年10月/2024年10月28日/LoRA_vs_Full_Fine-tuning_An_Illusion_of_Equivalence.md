# LoRA 与全微调：等效的错觉

发布时间：2024年10月28日

`LLM理论` `模型微调`

> LoRA vs Full Fine-tuning: An Illusion of Equivalence

# 摘要

> 微调是将预训练的大型语言模型适应下游任务的关键范式。最近，像低秩自适应（LoRA）这样的方法已被证明在各种任务上能够以可训练参数数量的极大减少匹配完全微调模型的性能。即使在两种方法学习到类似准确模型的设置中，\emph{它们学习到的解决方案真的等价吗？} 我们通过从模型的频谱特性的角度分析模型的权重矩阵，研究不同的微调方法如何改变预训练模型。我们发现完全微调与 LoRA 产生的权重矩阵，其奇异值分解表现出非常不同的结构；此外，在适应任务分布之外进行测试时，微调后的模型本身表现出不同的泛化行为。更具体地说，我们首先表明用 LoRA 训练的权重矩阵具有新的、高排名的奇异向量，我们称之为\emph{入侵维度}。在完全微调过程中不会出现入侵维度。其次，我们表明具有入侵维度的 LoRA 模型，尽管在目标任务上与完全微调取得类似的性能，但成为预训练分布的更差模型，并且对多个任务的顺序适应不太稳健。更高秩、秩稳定的 LoRA 模型与完全微调非常相似，即使在相同任务上与低秩 LoRA 模型表现相当时也是如此。这些结果表明，用 LoRA 和完全微调更新的模型访问参数空间的不同部分，即使它们在微调分布上表现相同。最后，我们研究了为什么在 LoRA 微调模型中会出现入侵维度，为什么它们是不受欢迎的，以及如何将其影响最小化。

> Fine-tuning is a crucial paradigm for adapting pre-trained large language models to downstream tasks. Recently, methods like Low-Rank Adaptation (LoRA) have been shown to match the performance of fully fine-tuned models on various tasks with an extreme reduction in the number of trainable parameters. Even in settings where both methods learn similarly accurate models, \emph{are their learned solutions really equivalent?} We study how different fine-tuning methods change pre-trained models by analyzing the model's weight matrices through the lens of their spectral properties. We find that full fine-tuning and LoRA yield weight matrices whose singular value decompositions exhibit very different structure; moreover, the fine-tuned models themselves show distinct generalization behaviors when tested outside the adaptation task's distribution. More specifically, we first show that the weight matrices trained with LoRA have new, high-ranking singular vectors, which we call \emph{intruder dimensions}. Intruder dimensions do not appear during full fine-tuning. Second, we show that LoRA models with intruder dimensions, despite achieving similar performance to full fine-tuning on the target task, become worse models of the pre-training distribution and adapt less robustly to multiple tasks sequentially. Higher-rank, rank-stabilized LoRA models closely mirror full fine-tuning, even when performing on par with lower-rank LoRA models on the same tasks. These results suggest that models updated with LoRA and full fine-tuning access different parts of parameter space, even when they perform equally on the fine-tuned distribution. We conclude by examining why intruder dimensions appear in LoRA fine-tuned models, why they are undesirable, and how their effects can be minimized.

[Arxiv](https://arxiv.org/abs/2410.21228)