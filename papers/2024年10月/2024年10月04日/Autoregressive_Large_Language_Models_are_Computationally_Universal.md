# 自回归大型语言模型具备计算上的通用性

发布时间：2024年10月04日

`LLM理论` `计算机科学` `人工智能`

> Autoregressive Large Language Models are Computationally Universal

# 摘要

> 我们揭示了基于transformer的语言模型通过自回归解码实现通用计算的潜力，无需外部干预或权重调整。关键在于理解模型如何以有限上下文处理任意长输入。我们推广了自回归解码，使发出的token随上下文窗口推进而附加到序列末尾。结果系统等同于经典的Lag计算模型，已知其具备计算通用性。通过新证明，我们证实通用图灵机可由2027规则的Lag系统模拟。进一步，我们验证了现有大型语言模型能否模拟此Lag系统。实验表明，gemini-1.5-pro-001仅需单一系统提示，在确定性解码下即可准确执行所有2027规则。由此，依据丘奇-图灵论题，扩展自回归解码的gemini-1.5-pro-001堪称通用计算机。

> 
Abstract:We show that autoregressive decoding of a transformer-based language model can realize universal computation, without external intervention or modification of the model's weights. Establishing this result requires understanding how a language model can process arbitrarily long inputs using a bounded context. For this purpose, we consider a generalization of autoregressive decoding where, given a long input, emitted tokens are appended to the end of the sequence as the context window advances. We first show that the resulting system corresponds to a classical model of computation, a Lag system, that has long been known to be computationally universal. By leveraging a new proof, we show that a universal Turing machine can be simulated by a Lag system with 2027 production rules. We then investigate whether an existing large language model can simulate the behaviour of such a universal Lag system. We give an affirmative answer by showing that a single system-prompt can be developed for gemini-1.5-pro-001 that drives the model, under deterministic (greedy) decoding, to correctly apply each of the 2027 production rules. We conclude that, by the Church-Turing thesis, prompted gemini-1.5-pro-001 with extended autoregressive (greedy) decoding is a general purpose computer.
    

[Arxiv](https://arxiv.org/pdf/2410.03170)