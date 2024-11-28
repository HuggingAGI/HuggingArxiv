# 草案模型知晓何时停止：针对推测解码的自验证长度策略

发布时间：2024年11月27日

`LLM应用` `语言模型` `推理优化`

> Draft Model Knows When to Stop: A Self-Verification Length Policy for Speculative Decoding

# 摘要

> 推测解码（SD）已成为提升大型语言模型推理速度的关键技术。传统的 SD 方法采用固定的草案长度，未考虑不同任务中令牌生成的难度。为此，本文解决了这一问题，引入了 SVIP——一种适用于推测解码系统、能感知难度的动态草案长度策略。基于草案令牌接受率的理论下限及其推理时的近似值，SVIP 依据每个草案令牌分布的熵来灵活确定草案序列的长度。主流 SD 基准和框架上的实验结果显示，SVIP 性能卓越，在 SpecBench 上较基线 SD 方法运行时间最多加快 20％，在 MT-Bench 上对于长达 8K 令牌的长文本生成运行时间最多加快 60％。而且，SVIP 无需训练，与任何现有的自动回归生成草案令牌的 SD 方法都兼容。实验结果还表明，SVIP 在 GliDe & CaPE 和 EAGLE-2 之上均能持续改善运行时间。

> Speculative Decoding (SD) has become an important technique in accelerating the inference speed of large language models. Conventional SD methods employ a fixed draft length, which ignores the token generation difficulty across tasks. Consequently, in this paper, we address such an issue and introduce SVIP - a difficulty-aware dynamic draft length policy for speculative decoding systems. Based on a theoretical lower bound of draft token acceptance rate and its inference-time approximation, SVIP adaptively determines the lengths of draft sequences based on the entropy of each draft token distribution. Experimental results on mainstream SD benchmarks and frameworks demonstrate the superior performance of SVIP, achieving up to 20\% walltime speedup on SpecBench over baseline SD methods and 60\% speedup on MT-Bench for long-form generation of up to 8K tokens. Moreover, SVIP is totally training-free and compatible with any existing SD methods that generate draft tokens autoregressively. Experimental results also show that SVIP yields consistent walltime improvement on top of GliDe & CaPE and EAGLE-2.

[Arxiv](https://arxiv.org/abs/2411.18462)