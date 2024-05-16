# 大型语言模型的巧妙越狱：自适应密集至稀疏约束优化策略

发布时间：2024年05月15日

`LLM理论

这篇论文主要探讨了大型语言模型（LLM）的安全性问题，特别是针对越狱攻击的防御。它提出了一种新的攻击手段——自适应稠密至稀疏约束优化（ADC），并展示了这种攻击手段在多个开源大型语言模型上的有效性。论文的核心贡献在于其提出的攻击方法和实验结果，这些内容更偏向于LLM的理论研究，因为它关注的是模型的内部机制和潜在的安全漏洞。虽然这种攻击手段可能会被用于实际的LLM应用中，但论文的主要焦点是理论层面的分析和优化方法的提出，因此更适合归类为LLM理论。` `网络安全` `人工智能安全`

> Efficient LLM Jailbreak via Adaptive Dense-to-sparse Constrained Optimization

# 摘要

> 最新研究发现，大型语言模型易受越狱攻击，产生有害内容。本文提出了一种创新的令牌级攻击手段——自适应稠密至稀疏约束优化（ADC），成功破解了多个开源大型语言模型。我们的方法将离散越狱优化转化为连续优化，并逐步提升优化向量的稀疏性，有效弥合了离散与连续优化间的鸿沟。实验证明，ADC方法在效率和效果上均超越了现有令牌级攻击手段。在Harmbench测试中，ADC在八种大型语言模型中，有七种达到了顶尖的攻击成功率。相关代码将公开发布。请注意：本文内容可能包含令人不适的模型行为。

> Recent research indicates that large language models (LLMs) are susceptible to jailbreaking attacks that can generate harmful content. This paper introduces a novel token-level attack method, Adaptive Dense-to-Sparse Constrained Optimization (ADC), which effectively jailbreaks several open-source LLMs. Our approach relaxes the discrete jailbreak optimization into a continuous optimization and progressively increases the sparsity of the optimizing vectors. Consequently, our method effectively bridges the gap between discrete and continuous space optimization. Experimental results demonstrate that our method is more effective and efficient than existing token-level methods. On Harmbench, our method achieves state of the art attack success rate on seven out of eight LLMs. Code will be made available. Trigger Warning: This paper contains model behavior that can be offensive in nature.

[Arxiv](https://arxiv.org/abs/2405.09113)