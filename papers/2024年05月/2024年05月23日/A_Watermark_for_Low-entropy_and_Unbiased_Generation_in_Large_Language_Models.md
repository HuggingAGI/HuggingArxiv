# 大型语言模型中低熵无偏生成的水印标识

发布时间：2024年05月23日

`LLM应用

理由：这篇论文主要探讨了在大型语言模型（LLMs）中嵌入水印的技术，以准确识别LLM生成的内容，并提出了新的方法（STA-1）来解决现有水印技术的局限性。这种方法不需要模型内部访问或特定提示，并确保了误判率的统计可靠性。此外，论文还讨论了水印强度与文本质量之间的平衡，并在实验中验证了其方法的有效性。这些内容主要关注于LLM的实际应用层面，特别是在安全性和内容识别方面的应用，因此归类为LLM应用。` `信息安全` `人工智能`

> A Watermark for Low-entropy and Unbiased Generation in Large Language Models

# 摘要

> 随着大型语言模型（LLMs）技术的进步，误用风险日益凸显，准确识别LLM生成内容成为焦点。一种有效策略是在模型中嵌入微妙的水印。以往研究证实，无偏水印既能保证不可伪造，又能维持文本质量，因为它遵循了LLM输出概率的自然分布。但这些方法在实际应用中受限，因为它们需要检测时对模型的内部访问和特定输入提示。此外，它们未能为水印检测的误判率提供统计保障。本研究创新性地提出了“采样一然后接受”（STA-1）方法，一种无需模型内部访问或特定提示的无偏水印，并确保了误判率的统计可靠性。我们还揭示了无偏水印中水印强度与文本质量之间的微妙平衡，特别是在低熵环境下，这种平衡尤为关键。实验在不同熵值的数据集上验证了STA-1在保持文本质量与水印强度方面的优越性，同时降低了不满意输出的风险。相关实现代码已公开发布。

> Recent advancements in large language models (LLMs) have highlighted the risk of misuse, raising concerns about accurately detecting LLM-generated content. A viable solution for the detection problem is to inject imperceptible identifiers into LLMs, known as watermarks. Previous work demonstrates that unbiased watermarks ensure unforgeability and preserve text quality by maintaining the expectation of the LLM output probability distribution. However, previous unbiased watermarking methods are impractical for local deployment because they rely on accesses to white-box LLMs and input prompts during detection. Moreover, these methods fail to provide statistical guarantees for the type II error of watermark detection. This study proposes the Sampling One Then Accepting (STA-1) method, an unbiased watermark that does not require access to LLMs nor prompts during detection and has statistical guarantees for the type II error. Moreover, we propose a novel tradeoff between watermark strength and text quality in unbiased watermarks. We show that in low-entropy scenarios, unbiased watermarks face a tradeoff between watermark strength and the risk of unsatisfactory outputs. Experimental results on low-entropy and high-entropy datasets demonstrate that STA-1 achieves text quality and watermark strength comparable to existing unbiased watermarks, with a low risk of unsatisfactory outputs. Implementation codes for this study are available online.

[Arxiv](https://arxiv.org/abs/2405.14604)