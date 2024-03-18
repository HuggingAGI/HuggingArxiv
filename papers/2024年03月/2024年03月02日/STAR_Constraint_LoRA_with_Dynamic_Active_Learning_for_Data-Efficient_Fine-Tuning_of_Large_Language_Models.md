# [STAR 方法将动态主动学习与约束版的 LoRA 结合，旨在提升大型语言模型在数据有限条件下的微调效率。](https://arxiv.org/abs/2403.01165)

发布时间：2024年03月02日

`LLM应用`

> STAR: Constraint LoRA with Dynamic Active Learning for Data-Efficient Fine-Tuning of Large Language Models

> 虽然LLMs已展现出通过提示法进行少量样本学习的强大能力，但在处理复杂推理任务时仍需依赖监督训练。为解决LLMs因参数众多和内存占用大带来的问题，科研人员分别提出了参数高效微调及内存高效微调策略。然而，如何有效减少对大量标注数据的依赖这一目标——即数据高效微调，尚待深入探索。直观的做法是将PEFT方法与主动学习相结合，遗憾的是，实验发现这种组合并不直观且效果欠佳。经探查实验揭示，这主要归因于两大因素：不确定性差距和模型校准不准确。因此，本文创新性地提出了一种融合基于不确定性主动学习与LoRA的新方法。针对不确定性差距问题，我们设计了一种结合基础模型与全模型在主动学习迭代过程中的动态不确定性测量方式；而对于模型校准问题，则在LoRA训练阶段加入正则化手段，抑制模型过度自信，并运用蒙特卡洛dropout机制以提升不确定性估算精度。实验证明，该新方法在三项复杂推理任务上的表现均优于现有基准模型。

> Though Large Language Models (LLMs) have demonstrated the powerful capabilities of few-shot learning through prompting methods, supervised training is still necessary for complex reasoning tasks. Because of their extensive parameters and memory consumption, both Parameter-Efficient Fine-Tuning (PEFT) methods and Memory-Efficient Fine-Tuning methods have been proposed for LLMs. Nevertheless, the issue of large annotated data consumption, the aim of Data-Efficient Fine-Tuning, remains unexplored. One obvious way is to combine the PEFT method with active learning. However, the experimental results show that such a combination is not trivial and yields inferior results. Through probe experiments, such observation might be explained by two main reasons: uncertainty gap and poor model calibration. Therefore, in this paper, we propose a novel approach to effectively integrate uncertainty-based active learning and LoRA. Specifically, for the uncertainty gap, we introduce a dynamic uncertainty measurement that combines the uncertainty of the base model and the uncertainty of the full model during the iteration of active learning. For poor model calibration, we incorporate the regularization method during LoRA training to keep the model from being over-confident, and the Monte-Carlo dropout mechanism is employed to enhance the uncertainty estimation. Experimental results show that the proposed approach outperforms existing baseline models on three complex reasoning tasks.

[Arxiv](https://arxiv.org/abs/2403.01165)