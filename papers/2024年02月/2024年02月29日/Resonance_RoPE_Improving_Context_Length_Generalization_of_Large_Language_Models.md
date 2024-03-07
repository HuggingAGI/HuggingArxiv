# [Resonance RoPE技术致力于增强大型语言模型对不同上下文长度的适应与泛化能力。](https://arxiv.org/abs/2403.00071)

> Resonance RoPE: Improving Context Length Generalization of Large Language Models

发布时间：2024年02月29日

> 面对具备RoPE技术的LLMs中训练短样本而测试长样本（TSTL）的难题，本篇论文提出了一项名为“共振RoPE”的新方案。该方案优化了对OOD位置处RoPE特征的插值处理，有效减小了模型在TSTL场景下的泛化鸿沟，并在不增加实时计算开销的前提下，显著提升了模型的表现力。同时，我们精心打造了一个名为PosGen的新型合成基准，用于细致分析TSTL场景下的行为表现，力求从识别新令牌位置的问题中独立出在长背景中生成令牌愈发艰难的挑战。实验证明，应用共振RoPE后的Transformer能够更精准且稳定地识辨OOD位置。进一步的广泛LLM实验揭示，在采用最先进RoPE扩展方法YaRN进行上游语言模型任务和各类下游长文本应用时，经过共振RoPE优化后的模型展现出了卓越的性能提升。

> This paper addresses the challenge of train-short-test-long (TSTL) scenarios in Large Language Models (LLMs) equipped with Rotary Position Embedding (RoPE), where models pre-trained on shorter sequences face difficulty with out-of-distribution (OOD) token positions in longer sequences. We introduce Resonance RoPE, a novel approach designed to narrow the generalization gap in TSTL scenarios by refining the interpolation of RoPE features for OOD positions, significantly improving the model performance without additional online computational costs. Furthermore, we present PosGen, a new synthetic benchmark specifically designed for fine-grained behavior analysis in TSTL scenarios, aiming to isolate the constantly increasing difficulty of token generation on long contexts from the challenges of recognizing new token positions. Our experiments on synthetic tasks show that after applying Resonance RoPE, Transformers recognize OOD position better and more robustly. Our extensive LLM experiments also show superior performance after applying Resonance RoPE to the current state-of-the-art RoPE scaling method, YaRN, on both upstream language modeling tasks and a variety of downstream long-text applications.

`LLM应用`