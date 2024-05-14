# 融合多重后训练技艺，铸就量化大型语言模型的极致效能

发布时间：2024年05月11日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）在计算和存储方面的挑战，并研究了量化技术如何解决这些问题。它专注于量化技术的理论分析和应用，特别是SmoothQuant和GPTQ这两种后训练技术的协同应用，以及它们在微尺度（MX）格式下的扩展。这些内容更偏向于LLM的理论研究，而不是Agent、RAG或LLM应用的范畴。因此，将其归类为LLM理论是合适的。` `模型压缩`

> Combining multiple post-training techniques to achieve most efficient quantized LLMs

# 摘要

> 大型语言模型（LLMs）在语言建模任务中表现卓越，但伴随而来的是计算和存储上的重大挑战。本文深入探讨了量化技术如何成为解决这些难题的钥匙。我们系统性地研究了SmoothQuant和GPTQ这两种后训练技术的协同应用，并对其如何促进LLM量化进行了详尽的分析。通过将量化技术扩展至微尺度（MX）格式，我们不仅提升了这两种技术的适应性，还拓宽了它们的应用领域。实验证明，结合GPTQ和SmoothQuant，并采用MX格式进行模型量化，我们能够将OPT模型的体积压缩至原来的四分之一，LLaMA模型至原来的三分之一，而困惑度的增长，几乎可以忽略不计，仅在1-3%之间。

> Large Language Models (LLMs) have distinguished themselves with outstanding performance in complex language modeling tasks, yet they come with significant computational and storage challenges. This paper explores the potential of quantization to mitigate these challenges. We systematically study the combined application of two well-known post-training techniques, SmoothQuant and GPTQ, and provide a comprehensive analysis of their interactions and implications for advancing LLM quantization. We enhance the versatility of both techniques by enabling quantization to microscaling (MX) formats, expanding their applicability beyond their initial fixed-point format targets. We show that by applying GPTQ and SmoothQuant, and employing MX formats for quantizing models, we can achieve a significant reduction in the size of OPT models by up to 4x and LLaMA models by up to 3x with a negligible perplexity increase of 1-3%.

[Arxiv](https://arxiv.org/abs/2405.07135)