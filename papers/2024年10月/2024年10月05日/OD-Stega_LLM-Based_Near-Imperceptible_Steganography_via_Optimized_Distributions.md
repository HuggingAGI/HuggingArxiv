# OD-Stega：利用 LLM 技术，通过优化分布实现近乎无痕的隐写术。

发布时间：2024年10月05日

`LLM应用` `信息安全`

> OD-Stega: LLM-Based Near-Imperceptible Steganography via Optimized Distributions

# 摘要

> 我们探讨了一种无覆盖隐写术，利用大型语言模型 (LLM) 驱动算术编码解码器生成隐写文本。高效的方法应尽量减少语言标记的使用，同时确保隐写文本的自然流畅。我们发现，在单个标记层面，这问题等同于在 KL 散度约束下最大化替换概率分布的熵。我们提供了高效的封闭形式解决方案。此外，我们还解决了几个实际问题：1) 通过简单提示选择解决标记化不匹配，2) 结合优化分布与词汇截断技术，3) 结合优化分布与其他序列级选择启发式，进一步提升效率和可靠性。

> We consider coverless steganography where a Large Language Model (LLM) drives an arithmetic coding decoder to generate stego-texts. An efficient method should embed secret message bits in as few language tokens as possible, while still keeping the stego-text natural and fluent. We show that on the individual token level, this problem is mathematically equivalent to maximizing the entropy of a replacement probability distribution of the next token generation, subject to a constraint on the KL divergence between the chosen probability distribution and the original distribution given by the LLM. A closed-form solution is provided for the optimization problem, which can be computed efficiently. Several important practical issues are also tackled: 1) An often-overlooked tokenization mismatch issue is resolved with a simple prompt selection approach, 2) The combination of the optimized distribution and the vocabulary truncation technique is considered, and 3) The combination of the optimized distribution with other sequence-level selection heuristics to further enhance the efficiency and reliability is studied.

[Arxiv](https://arxiv.org/abs/2410.04328)