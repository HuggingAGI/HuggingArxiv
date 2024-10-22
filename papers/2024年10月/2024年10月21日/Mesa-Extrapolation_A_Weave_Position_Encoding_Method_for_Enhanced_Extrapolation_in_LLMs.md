# Mesa-Extrapolation：一种提升 LLM 外推能力的编织位置编码方法

发布时间：2024年10月21日

`LLM理论` `人工智能`

> Mesa-Extrapolation: A Weave Position Encoding Method for Enhanced Extrapolation in LLMs

# 摘要

> 尽管大型语言模型 (LLM) 在多个领域取得了革命性进展，但仍面临外推难题，即推理能力在超出训练长度后急剧下降。我们通过理论分析，揭示了无位置编码 (NoPE) 在有效范围外的失效原因，并探讨了位置编码 (PE) 的潜力。研究发现，精心设计的位置编码能有效扩展其作用范围。我们的定理证明，配备编织 PE 的 LLM 无需额外成本即可提升外推性能。此外，我们创新性地提出了 Mesa-Extrapolation 方法，结合块状三角注意力矩阵和 Stair PE，不仅性能卓越，还大幅降低了内存需求和推理时间。实验结果证实了 Mesa-Extrapolation 的有效性，为扩展 LLM 的应用范围提供了可行的解决方案。

> Large language models (LLMs), although having revolutionized many fields, still suffer from the challenging extrapolation problem, where the inference ability of LLMs sharply declines beyond their max training lengths. In this work, we conduct a theoretical analysis to better understand why No Position Encoding (NoPE) fails outside its effective range, as well as examining the power of Position Encoding (PE) in this context. Our findings reveal that with meticulous weave position, PE can indeed be extended beyond effective range. Our theorems establish that LLMs equipped with weave PE can achieve improved extrapolation performance without additional cost. Furthermore, we introduce a novel weave PE method, Mesa-Extrapolation, which utilizes a chunk-based triangular attention matrix and applies Stair PE to manage the final chunk. This method not only retains competitive performance but also offers substantial benefits such as significantly reduced memory demand and faster inference speed. Extensive experiments validate the effectiveness of Mesa-Extrapolation, demonstrating its potential as a scalable solution to enhancing LLMs applicative reach.

[Arxiv](https://arxiv.org/abs/2410.15859)