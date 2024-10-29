# 超越自回归：通过时间上的自蒸馏实现快速的大型语言模型

发布时间：2024年10月28日

`LLM应用` `模型性能优化`

> Beyond Autoregression: Fast LLMs via Self-Distillation Through Time

# 摘要

> 自回归（AR）大型语言模型（LLM）在众多任务中已取得显著成功。然而，AR 建模范式存在一定的局限性；例如，当代的自回归 LLM 被训练为一次生成一个标记，这可能导致明显的延迟。最近的进展表明，搜索和重复采样可以通过在推理过程中利用更多的计算资源来提高在诸如定理证明、代码生成和对齐等各种应用中的性能。在本研究中，我们证明扩散语言模型能够同时生成至少 32 个标记，同时在文本质量和 LAMBADA 自然语言理解基准上超过 AR 模型的性能。这一结果是通过一种用于离散扩散模型的新型蒸馏方法实现的，该方法将推理步骤的数量减少了 32 - 64 倍。实际上，我们的模型即使没有缓存，生成标记的速度也比使用 KV 缓存的 AR 模型快多达 8 倍，并且我们预计加入缓存后会有进一步的改进。此外，我们证明了我们的方法对多达 8.6 亿参数的扩散语言模型的有效性。

> Autoregressive (AR) Large Language Models (LLMs) have demonstrated significant success across numerous tasks. However, the AR modeling paradigm presents certain limitations; for instance, contemporary autoregressive LLMs are trained to generate one token at a time, which can result in noticeable latency. Recent advances have indicated that search and repeated sampling can enhance performance in various applications, such as theorem proving, code generation, and alignment, by utilizing greater computational resources during inference. In this study, we demonstrate that diffusion language models are capable of generating at least 32 tokens simultaneously, while exceeding the performance of AR models in text quality and on the LAMBADA natural language understanding benchmark. This outcome is achieved through a novel distillation method for discrete diffusion models, which reduces the number of inference steps by a factor of 32-64. Practically, our models, even without caching, can generate tokens at a rate that is up to 8 times faster than AR models employing KV caching, and we anticipate further improvements with the inclusion of caching. Moreover, we demonstrate the efficacy of our approach for diffusion language models with up to 860M parameters.

[Arxiv](https://arxiv.org/abs/2410.21035)