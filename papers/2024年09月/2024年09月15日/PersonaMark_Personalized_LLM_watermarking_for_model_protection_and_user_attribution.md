# PersonaMark：一种个性化 LLM 水印技术，旨在保护模型并识别用户归属。

发布时间：2024年09月15日

`LLM应用` `版权保护` `人工智能`

> PersonaMark: Personalized LLM watermarking for model protection and user attribution

# 摘要

> LLM的迅猛发展既带来了便利，也潜藏着威胁。随着定制和私有LLM的普及，模型版权保护变得尤为重要。文本水印作为一种有前景的解决方案，正逐渐被用于AI生成文本的检测和模型保护。然而，现有水印技术大多忽略了为不同用户注入独特水印的需求，这限制了水印的归因能力。本文探讨了LLM版权保护中的个性化文本水印方案，旨在确保内容生成的责任和可追溯性。我们提出了一种名为PersonaMark的新方法，利用句子结构作为水印信息的隐藏载体，并通过优化句子级生成算法，最小化对模型自然生成过程的干扰。通过个性化哈希函数，我们为不同用户注入独特的水印信号，从而实现个性化水印文本。由于我们的方法在句子级别操作，而非令牌概率，因此文本质量得以高度保留。此外，多用户哈希函数的设计使得大规模用户的水印注入过程极为高效。据我们所知，这是首次实现个性化文本水印。我们对四种不同的LLM进行了全面评估，结果显示，我们的方法在保持性能的同时，对模型行为的干扰最小，且水印插入无偏，识别能力强大。

> The rapid development of LLMs brings both convenience and potential threats. As costumed and private LLMs are widely applied, model copyright protection has become important. Text watermarking is emerging as a promising solution to AI-generated text detection and model protection issues. However, current text watermarks have largely ignored the critical need for injecting different watermarks for different users, which could help attribute the watermark to a specific individual. In this paper, we explore the personalized text watermarking scheme for LLM copyright protection and other scenarios, ensuring accountability and traceability in content generation. Specifically, we propose a novel text watermarking method PersonaMark that utilizes sentence structure as the hidden medium for the watermark information and optimizes the sentence-level generation algorithm to minimize disruption to the model's natural generation process. By employing a personalized hashing function to inject unique watermark signals for different users, personalized watermarked text can be obtained. Since our approach performs on sentence level instead of token probability, the text quality is highly preserved. The injection process of unique watermark signals for different users is time-efficient for a large number of users with the designed multi-user hashing function. As far as we know, we achieved personalized text watermarking for the first time through this. We conduct an extensive evaluation of four different LLMs in terms of perplexity, sentiment polarity, alignment, readability, etc. The results demonstrate that our method maintains performance with minimal perturbation to the model's behavior, allows for unbiased insertion of watermark information, and exhibits strong watermark recognition capabilities.

[Arxiv](https://arxiv.org/abs/2409.09739)