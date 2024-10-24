# 对于大型语言模型的持续训练，采用子空间正则化的受控低秩适应

发布时间：2024年10月22日

`LLM应用` `模型微调`

> Controlled Low-Rank Adaptation with Subspace Regularization for Continued Training on Large Language Models

# 摘要

> 大型语言模型（LLMs）在自然语言处理中展现出卓越的能力，但在学习新任务时面临灾难性遗忘，适应新领域会导致先前任务的性能大幅下降。在本文中，我们提出了受控 LoRA（CLoRA），这是一种在 LoRA 结构上的子空间正则化方法。旨在减少输出变化的规模，同时对模型容量引入最小约束，CLoRA 对更新矩阵零空间的方向施加约束。在常用的 LLM 微调任务上的实验结果表明，CLoRA 在域内和域外评估中都显著优于现有的 LoRA 后续方法，突出了 CLoRA 作为一种有效且参数高效的微调方法在缓解灾难性遗忘方面的优越性。对模型参数的进一步研究表明，CLoRA 有效地平衡了模型容量和遗忘程度之间的权衡。

> Large language models (LLMs) exhibit remarkable capabilities in natural language processing but face catastrophic forgetting when learning new tasks, where adaptation to a new domain leads to a substantial decline in performance on previous tasks. In this paper, we propose Controlled LoRA (CLoRA), a subspace regularization method on LoRA structure. Aiming to reduce the scale of output change while introduce minimal constraint on model capacity, CLoRA imposes constraint on the direction of updating matrix null space. Experimental results on commonly used LLM finetuning tasks reveal that CLoRA significantly outperforms existing LoRA subsequent methods on both in-domain and outdomain evaluations, highlighting the superority of CLoRA as a effective parameter-efficient finetuning method with catastrophic forgetting mitigating. Further investigation for model parameters indicates that CLoRA effectively balances the trade-off between model capacity and degree of forgetting.

[Arxiv](https://arxiv.org/abs/2410.16801)