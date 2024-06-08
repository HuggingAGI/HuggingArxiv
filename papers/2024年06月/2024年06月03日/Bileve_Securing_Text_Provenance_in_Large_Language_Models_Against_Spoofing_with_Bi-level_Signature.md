# Bileve：双层签名技术，为大型语言模型中的文本来源安全筑起防线，有效抵御欺骗行为。

发布时间：2024年06月03日

`LLM应用

这篇论文讨论了大型语言模型（LLMs）中的文本水印技术，特别是针对机器生成内容的来源追踪问题。论文提出了一种名为Bileve的双层签名方案，旨在提高水印技术的抗欺骗攻击能力，并增强对文本来源的追踪和检测能力。这与LLM的应用相关，特别是在内容验证和责任归属方面，因此应归类为LLM应用。` `网络安全` `内容安全`

> Bileve: Securing Text Provenance in Large Language Models Against Spoofing with Bi-level Signature

# 摘要

> 大型语言模型（LLMs）的文本水印常用于追踪机器生成内容的来源，这对于评估深度伪造或有害内容的责任至关重要。然而，现有水印技术虽强调抗移除攻击的鲁棒性，却易受欺骗攻击：恶意者能微调LLM的响应或伪造有害内容，错误地指向开发者。为此，我们提出了双层签名方案Bileve，它通过创新的基于排名的采样策略，嵌入细粒度签名以检查完整性（防欺骗），并在签名失效时提供粗粒度信号以追踪文本来源（提升检测能力）。与传统水印检测器不同，Bileve能在检测中区分五种情况，确保文本来源的追踪和LLMs的规范。在OPT-1.3B和LLaMA-7B上的实验显示，Bileve在增强检测能力的同时，有效抵御了欺骗攻击。

> Text watermarks for large language models (LLMs) have been commonly used to identify the origins of machine-generated content, which is promising for assessing liability when combating deepfake or harmful content. While existing watermarking techniques typically prioritize robustness against removal attacks, unfortunately, they are vulnerable to spoofing attacks: malicious actors can subtly alter the meanings of LLM-generated responses or even forge harmful content, potentially misattributing blame to the LLM developer. To overcome this, we introduce a bi-level signature scheme, Bileve, which embeds fine-grained signature bits for integrity checks (mitigating spoofing attacks) as well as a coarse-grained signal to trace text sources when the signature is invalid (enhancing detectability) via a novel rank-based sampling strategy. Compared to conventional watermark detectors that only output binary results, Bileve can differentiate 5 scenarios during detection, reliably tracing text provenance and regulating LLMs. The experiments conducted on OPT-1.3B and LLaMA-7B demonstrate the effectiveness of Bileve in defeating spoofing attacks with enhanced detectability.

![Bileve：双层签名技术，为大型语言模型中的文本来源安全筑起防线，有效抵御欺骗行为。](../../../paper_images/2406.01946/x1.png)

![Bileve：双层签名技术，为大型语言模型中的文本来源安全筑起防线，有效抵御欺骗行为。](../../../paper_images/2406.01946/x2.png)

![Bileve：双层签名技术，为大型语言模型中的文本来源安全筑起防线，有效抵御欺骗行为。](../../../paper_images/2406.01946/x3.png)

![Bileve：双层签名技术，为大型语言模型中的文本来源安全筑起防线，有效抵御欺骗行为。](../../../paper_images/2406.01946/x4.png)

![Bileve：双层签名技术，为大型语言模型中的文本来源安全筑起防线，有效抵御欺骗行为。](../../../paper_images/2406.01946/gpt.jpg)

![Bileve：双层签名技术，为大型语言模型中的文本来源安全筑起防线，有效抵御欺骗行为。](../../../paper_images/2406.01946/gpt_2.jpg)

![Bileve：双层签名技术，为大型语言模型中的文本来源安全筑起防线，有效抵御欺骗行为。](../../../paper_images/2406.01946/alg4.jpg)

![Bileve：双层签名技术，为大型语言模型中的文本来源安全筑起防线，有效抵御欺骗行为。](../../../paper_images/2406.01946/x5.png)

[Arxiv](https://arxiv.org/abs/2406.01946)