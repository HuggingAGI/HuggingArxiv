# 大型语言模型的参数高效微调：逐步揭秘法

发布时间：2024年08月26日

`LLM理论` `人工智能` `计算机科学`

> Step-by-Step Unmasking for Parameter-Efficient Fine-tuning of Large Language Models

# 摘要

> 在下游任务上微调大型语言模型 (LLM) 需要大量计算资源。参数高效的微调 (PEFT) 类方法通过仅微调模型参数的一小部分来缓解这一挑战。然而，这些技术常因参数选择中的固有偏差而无法达到完全微调的性能。传统 PEFT 技术依赖固定参数集，无法动态评估参数重要性，且易超预算。我们提出的 $\text{ID}^3$ 方法，通过持续评估参数重要性并动态调整参数选择，平衡了探索与利用。实证研究显示，$\text{ID}^3$ 在 15 个任务上优于传统 PEFT 技术，并通过减少梯度更新次数提升计算效率。此外，$\text{ID}^3$ 对神经元初始化稳健，可无缝集成到现有 PEFT 模块中，如适配器和 LoRA，实现动态稀疏化。

> Fine-tuning large language models (LLMs) on downstream tasks requires substantial computational resources. A class of parameter-efficient fine-tuning (PEFT) aims to mitigate these computational challenges by selectively fine-tuning only a small fraction of the model parameters. Although computationally efficient, these techniques often fail to match the performance of fully fine-tuned models, primarily due to inherent biases introduced during parameter selection. Traditional selective PEFT techniques use a fixed set of parameters based on a predefined budget (a process also known as unmasking), failing to capture parameter importance dynamically and often ending up exceeding the budget. We introduce $\text{ID}^3$, a novel selective PEFT method that calculates parameter importance continually and dynamically unmasks parameters by balancing exploration and exploitation in parameter selection. Our empirical study on 15 tasks spanning natural language understanding and generative tasks demonstrates the effectiveness of our method compared to fixed-masking-based PEFT techniques. We analytically show that $\text{ID}^3$ reduces the number of gradient updates by a factor of two, enhancing computational efficiency. $\text{ID}^3$ is robust to random initialization of neurons and, therefore, can be seamlessly integrated into existing additive and reparametrization-based PEFT modules such as adapters and LoRA for dynamic sparsification.

[Arxiv](https://arxiv.org/abs/2408.14470)