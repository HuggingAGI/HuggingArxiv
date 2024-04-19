# 利用概念激活向量技术，深入挖掘开源大型语言模型（LLM）中潜藏的安全风险。

发布时间：2024年04月18日

`LLM应用` `人工智能安全`

> Uncovering Safety Risks in Open-source LLMs through Concept Activation Vector

# 摘要

> 目前，开源的大型语言模型（LLMs）在发布前都会经过严格的安全校准。尽管如此，为了确保安全校准的坚固性，也提出了一些检测 LLMs 安全漏洞的攻击方法。但这些方法的攻击成功率通常只是一般。即便攻击成功，其输出的潜在危害性也难以确保。这引发了对这些方法是否真正识别出 LLMs 安全漏洞的疑问。本文提出了一种新颖的 LLM 攻击手段，通过基于概念的模型解释，从 LLMs 的激活空间提取出安全概念激活向量（SCAVs），有效攻击了即使是经过良好校准的 LLMs，如 LLaMA-2，实现了接近 100% 的攻击成功率，这暗示了即使经过了全面的安全校准，LLMs 在公开发布后仍可能带来社会风险。为了全面评估不同攻击手段产生的输出的危害性，我们设计了一种评估方法，旨在减少现有评估方法的不准确之处，并证实了我们的方法能够引发更多有害内容的产生。此外，我们还发现这些 SCAVs 在多个不同的开源 LLMs 之间具有一定的迁移性。

> Current open-source large language models (LLMs) are often undergone careful safety alignment before public release. Some attack methods have also been proposed that help check for safety vulnerabilities in LLMs to ensure alignment robustness. However, many of these methods have moderate attack success rates. Even when successful, the harmfulness of their outputs cannot be guaranteed, leading to suspicions that these methods have not accurately identified the safety vulnerabilities of LLMs. In this paper, we introduce a LLM attack method utilizing concept-based model explanation, where we extract safety concept activation vectors (SCAVs) from LLMs' activation space, enabling efficient attacks on well-aligned LLMs like LLaMA-2, achieving near 100% attack success rate as if LLMs are completely unaligned. This suggests that LLMs, even after thorough safety alignment, could still pose potential risks to society upon public release. To evaluate the harmfulness of outputs resulting with various attack methods, we propose a comprehensive evaluation method that reduces the potential inaccuracies of existing evaluations, and further validate that our method causes more harmful content. Additionally, we discover that the SCAVs show some transferability across different open-source LLMs.

![利用概念激活向量技术，深入挖掘开源大型语言模型（LLM）中潜藏的安全风险。](../../../paper_images/2404.12038/x1.png)

![利用概念激活向量技术，深入挖掘开源大型语言模型（LLM）中潜藏的安全风险。](../../../paper_images/2404.12038/x2.png)

![利用概念激活向量技术，深入挖掘开源大型语言模型（LLM）中潜藏的安全风险。](../../../paper_images/2404.12038/x3.png)

[Arxiv](https://arxiv.org/abs/2404.12038)