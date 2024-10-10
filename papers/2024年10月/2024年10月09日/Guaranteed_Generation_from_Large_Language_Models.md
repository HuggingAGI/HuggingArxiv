# 大型语言模型的生成保障

发布时间：2024年10月09日

`LLM理论` `人工智能`

> Guaranteed Generation from Large Language Models

# 摘要

> 随着 LLM 在各领域的广泛应用，控制文本生成以满足特定需求变得愈发重要。一个核心问题是：如何在尽量保持原始模型分布的前提下，确保生成内容严格符合约束？我们首先定义了理想分布——即最接近原始模型且始终满足约束的分布，作为保证生成的终极目标。然而，仅靠自回归训练无法实现这一目标，这促使我们结合训练和推理时方法来强化保证。基于此，我们提出了 GUARD，一种结合自回归提议分布和拒绝采样的简单有效方法。通过 GUARD，我们展示了如何通过控制 KL 散度来同时优化推理速度和分布接近度。实验证明，GUARD 在几乎不损失理想分布的情况下，完美满足了约束，并大幅提升了推理效率。GUARD 为 LLM 在不削弱生成能力的前提下实施严格保证提供了有力方案。

> As large language models (LLMs) are increasingly used across various applications, there is a growing need to control text generation to satisfy specific constraints or requirements. This raises a crucial question: Is it possible to guarantee strict constraint satisfaction in generated outputs while preserving the distribution of the original model as much as possible? We first define the ideal distribution - the one closest to the original model, which also always satisfies the expressed constraint - as the ultimate goal of guaranteed generation. We then state a fundamental limitation, namely that it is impossible to reach that goal through autoregressive training alone. This motivates the necessity of combining training-time and inference-time methods to enforce such guarantees. Based on this insight, we propose GUARD, a simple yet effective approach that combines an autoregressive proposal distribution with rejection sampling. Through GUARD's theoretical properties, we show how controlling the KL divergence between a specific proposal and the target ideal distribution simultaneously optimizes inference speed and distributional closeness. To validate these theoretical concepts, we conduct extensive experiments on two text generation settings with hard-to-satisfy constraints: a lexical constraint scenario and a sentiment reversal scenario. These experiments show that GUARD achieves perfect constraint satisfaction while almost preserving the ideal distribution with highly improved inference efficiency. GUARD provides a principled approach to enforcing strict guarantees for LLMs without compromising their generative capabilities.

[Arxiv](https://arxiv.org/abs/2410.06716)