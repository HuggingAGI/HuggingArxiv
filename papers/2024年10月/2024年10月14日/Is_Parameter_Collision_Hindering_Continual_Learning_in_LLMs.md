# 参数碰撞是否成为 LLM 持续学习的绊脚石？

发布时间：2024年10月14日

`LLM理论` `人工智能` `机器学习`

> Is Parameter Collision Hindering Continual Learning in LLMs?

# 摘要

> 大型语言模型 (LLM) 在学习多个任务时容易出现灾难性遗忘，因此持续学习 (CL) 对其动态部署至关重要。现有最先进方法如 O-LoRA 主要通过构建正交任务来解耦不同领域参数的相互依赖。本文揭示，构建非碰撞参数是解决 CL 挑战的关键。理论与实验分析表明，非碰撞参数能提供更好的任务正交性，且能保留多领域知识，减少遗忘。基于此，我们提出非碰撞低秩适应 (N-LoRA)，通过降低碰撞率提升 CL 效果。实验显示，N-LoRA 在性能、任务正交性和参数碰撞方面均优于现有方法。

> Large Language Models (LLMs) often suffer from catastrophic forgetting when learning multiple tasks sequentially, making continual learning (CL) essential for their dynamic deployment. Existing state-of-the-art (SOTA) methods, such as O-LoRA, typically focus on constructing orthogonality tasks to decouple parameter interdependence from various domains.In this paper, we reveal that building non-collision parameters is a more critical factor in addressing CL challenges. Our theoretical and experimental analyses demonstrate that non-collision parameters can provide better task orthogonality, which is a sufficient but unnecessary condition. Furthermore, knowledge from multiple domains will be preserved in non-collision parameter subspaces, making it more difficult to forget previously seen data. Leveraging this insight, we propose Non-collision Low-Rank Adaptation (N-LoRA), a simple yet effective approach leveraging low collision rates to enhance CL in LLMs. Experimental results on multiple CL benchmarks indicate that N-LoRA achieves superior performance (+2.9), higher task orthogonality (*4.1 times), and lower parameter collision (*58.1 times) than SOTA methods.

[Arxiv](https://arxiv.org/abs/2410.10179)