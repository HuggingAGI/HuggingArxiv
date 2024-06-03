# 幻影攻击：针对增强检索的语言生成的一般触发策略

发布时间：2024年05月30日

`RAG

这篇论文主要讨论了Retrieval Augmented Generation (RAG) 技术在大型语言模型中的应用及其带来的安全威胁。论文提出了一种针对RAG系统的攻击方法，即通过在知识库中植入恶意文档来破坏系统。这种攻击策略特别针对RAG增强的LLMs，并已在多种LLM架构上进行了验证。因此，这篇论文的内容与RAG技术的应用和相关安全问题紧密相关，应归类于RAG。` `聊天机器人` `网络安全`

> Phantom: General Trigger Attacks on Retrieval Augmented Language Generation

# 摘要

> Retrieval Augmented Generation (RAG) 技术增强了现代大型语言模型 (LLMs) 在聊天机器人领域的应用，使开发者能够轻松调整和个性化模型输出，无需昂贵的训练或微调。RAG 通过外部知识库检索与查询最相关的文档，为 LLM 提供上下文。尽管 RAG 在多个应用中表现出色，但其用于个性化生成模型也带来了新的安全威胁。我们提出了一种新的攻击方法，即通过在知识库中植入恶意文档来破坏 RAG 系统。我们设计的 Phantom 框架是一种针对 RAG 增强 LLMs 的两步攻击策略。首先，制作一个仅在查询中包含特定对抗触发器时被检索的毒化文档。其次，该文档中的特制字符串触发 LLM 生成器执行多种攻击，如拒绝服务、声誉损害、隐私泄露和有害行为。我们在 Gemma、Vicuna 和 Llama 等多种 LLM 架构上验证了这些攻击。

> Retrieval Augmented Generation (RAG) expands the capabilities of modern large language models (LLMs) in chatbot applications, enabling developers to adapt and personalize the LLM output without expensive training or fine-tuning. RAG systems use an external knowledge database to retrieve the most relevant documents for a given query, providing this context to the LLM generator. While RAG achieves impressive utility in many applications, its adoption to enable personalized generative models introduces new security risks. In this work, we propose new attack surfaces for an adversary to compromise a victim's RAG system, by injecting a single malicious document in its knowledge database. We design Phantom, general two-step attack framework against RAG augmented LLMs. The first step involves crafting a poisoned document designed to be retrieved by the RAG system within the top-k results only when an adversarial trigger, a specific sequence of words acting as backdoor, is present in the victim's queries. In the second step, a specially crafted adversarial string within the poisoned document triggers various adversarial attacks in the LLM generator, including denial of service, reputation damage, privacy violations, and harmful behaviors. We demonstrate our attacks on multiple LLM architectures, including Gemma, Vicuna, and Llama.

![幻影攻击：针对增强检索的语言生成的一般触发策略](../../../paper_images/2405.20485/atk_examples.png)

![幻影攻击：针对增强检索的语言生成的一般触发策略](../../../paper_images/2405.20485/x1.png)

![幻影攻击：针对增强检索的语言生成的一般触发策略](../../../paper_images/2405.20485/privacy_atk.png)

![幻影攻击：针对增强检索的语言生成的一般触发策略](../../../paper_images/2405.20485/x2.png)

[Arxiv](https://arxiv.org/abs/2405.20485)