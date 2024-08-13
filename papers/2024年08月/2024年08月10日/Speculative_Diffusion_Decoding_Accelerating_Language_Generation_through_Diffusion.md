# 推测性扩散解码技术，通过扩散机制加速语言生成过程。

发布时间：2024年08月10日

`LLM理论` `人工智能` `计算机科学`

> Speculative Diffusion Decoding: Accelerating Language Generation through Diffusion

# 摘要

> 推测解码技术已成为加速大型语言模型推理的主流方法，且不降低输出质量。尽管它通过并行序列验证显著提升了速度，但其效率仍受限于现有模型对逐个生成令牌的依赖。为此，我们提出了一种新方法，利用离散扩散模型生成草稿序列，从而实现草拟和验证的并行化，大幅加快推理速度。我们的\textit{推测扩散解码（SpecDiff）}方法在标准测试中表现出色，实测显示，与传统生成方法相比，速度提升高达8.7倍，与现有推测解码技术相比，速度提升高达2.5倍。

> Speculative decoding has emerged as a widely adopted method to accelerate large language model inference without sacrificing the quality of the model outputs. While this technique has facilitated notable speed improvements by enabling parallel sequence verification, its efficiency remains inherently limited by the reliance on incremental token generation in existing draft models. To overcome this limitation, this paper proposes an adaptation of speculative decoding which uses discrete diffusion models to generate draft sequences. This allows parallelization of both the drafting and verification steps, providing significant speed-ups to the inference process. Our proposed approach, \textit{Speculative Diffusion Decoding (SpecDiff)}, is validated on standard language generation benchmarks and empirically demonstrated to provide a \textbf{up to 8.7x speed-up over standard generation processes and up to 2.5x speed-up over existing speculative decoding approaches.}

[Arxiv](https://arxiv.org/abs/2408.05636)