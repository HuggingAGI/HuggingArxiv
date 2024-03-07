# [在大型语言模型中，采用自合成复习方法有效减轻灾难性遗忘问题。](https://arxiv.org/abs/2403.01244)

> Mitigating Catastrophic Forgetting in Large Language Models with Self-Synthesized Rehearsal

发布时间：2024年03月02日

> 面对LLMs在连续学习中出现的灾难性遗忘现象，常规依赖旧有训练数据的复习方法在实际场景下往往难以实现。针对基于公开LLM检查点进行连续学习而原始训练数据无法获取的问题，我们创新性地提出了一个名为“自我合成复习”（SSR）的框架。这个框架巧妙地利用LLM自动生成模拟样本，先通过基础LLM进行上下文学习产生初步合成实例，再借助最新版本LLM依据这些合成输入优化实例输出，从而保护已获得的能力不被遗忘。最终，在后续的学习阶段挑选出丰富且高质量的合成样本进行强化复习。实验证明，SSR不仅在性能上超越或至少媲美传统基于复习的方法，而且在数据利用效率上更胜一筹，并能在通用领域有效维护LLMs的良好泛化能力。

> Large language models (LLMs) suffer from catastrophic forgetting during continual learning. Conventional rehearsal-based methods rely on previous training data to retain the model's ability, which may not be feasible in real-world applications. When conducting continual learning based on a publicly-released LLM checkpoint, the availability of the original training data may be non-existent. To address this challenge, we propose a framework called Self-Synthesized Rehearsal (SSR) that uses the LLM to generate synthetic instances for rehearsal. Concretely, we first employ the base LLM for in-context learning to generate synthetic instances. Subsequently, we utilize the latest LLM to refine the instance outputs based on the synthetic inputs, preserving its acquired ability. Finally, we select diverse high-quality synthetic instances for rehearsal in future stages. Experimental results demonstrate that SSR achieves superior or comparable performance compared to conventional rehearsal-based approaches while being more data-efficient. Besides, SSR effectively preserves the generalization capabilities of LLMs in general domains.

`LLM应用`