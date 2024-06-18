# VeraCT扫描：利用可解释推理增强检索的假新闻检测技术

发布时间：2024年06月12日

`Agent

理由：这篇论文介绍了一个名为 VeraCT Scan 的系统，该系统通过提取新闻核心事实并全网搜索相关报道，利用来源可信度进行验证，以区分真假新闻。这个系统可以被视为一个Agent，因为它执行特定的任务（新闻验证）并作出决策（确定新闻的真实性）。此外，论文中提到的 GPT-4 Turbo 和 Llama-2 13B 的微调，虽然涉及大型语言模型（LLM），但这里的重点是这些模型作为Agent在特定应用（假新闻检测）中的使用，而不是对LLM理论的探讨或RAG（Retrieval-Augmented Generation）技术的应用。因此，将其归类为Agent更为合适。` `新闻媒体` `假新闻检测`

> VeraCT Scan: Retrieval-Augmented Fake News Detection with Justifiable Reasoning

# 摘要

> 假新闻的泛滥不仅误导公众，还威胁到民主的根基。随着生成式AI的进步，区分真假新闻变得更加困难。为此，我们开发了VeraCT Scan系统，它通过提取新闻核心事实并全网搜索相关报道，利用来源可信度进行验证。我们不仅确保新闻真实性，还提供透明证据和推理，增强结果的可信度。此外，GPT-4 Turbo和Llama-2 13B经过微调，专门用于新闻理解和验证，两者均在假新闻检测领域达到了顶尖水平。

> The proliferation of fake news poses a significant threat not only by disseminating misleading information but also by undermining the very foundations of democracy. The recent advance of generative artificial intelligence has further exacerbated the challenge of distinguishing genuine news from fabricated stories. In response to this challenge, we introduce VeraCT Scan, a novel retrieval-augmented system for fake news detection. This system operates by extracting the core facts from a given piece of news and subsequently conducting an internet-wide search to identify corroborating or conflicting reports. Then sources' credibility is leveraged for information verification. Besides determining the veracity of news, we also provide transparent evidence and reasoning to support its conclusions, resulting in the interpretability and trust in the results. In addition to GPT-4 Turbo, Llama-2 13B is also fine-tuned for news content understanding, information verification, and reasoning. Both implementations have demonstrated state-of-the-art accuracy in the realm of fake news detection.

![VeraCT扫描：利用可解释推理增强检索的假新闻检测技术](../../../paper_images/2406.10289/x1.png)

[Arxiv](https://arxiv.org/abs/2406.10289)