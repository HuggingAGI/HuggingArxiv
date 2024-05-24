# MoGU：提升开源LLM安全性的同时确保其易用性的框架

发布时间：2024年05月23日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在处理恶意指令时的安全性问题，并提出了一种名为MoGU的框架来提高LLMs的安全性同时保持其响应的可用性。该框架通过动态路由机制来平衡LLMs的安全性和可用性，确保在面对不同类型的指令时能够提供合适的响应。这种研究直接应用于LLMs的实际使用场景中，旨在解决实际问题，因此属于LLM应用分类。` `人工智能安全`

> MoGU: A Framework for Enhancing Safety of Open-Sourced LLMs While Preserving Their Usability

# 摘要

> 随着大型语言模型（LLMs）在多个领域的应用日益广泛，其安全性问题也日益受到关注，尤其是在处理恶意指令时如何确保响应无害。尽管已有多种防御策略被提出以增强LLMs的安全性，但我们的研究表明，这些策略往往使LLMs倾向于拒绝响应，从而降低了其对良性指令的可用性。为此，我们提出了MoGU框架，旨在提升LLMs的安全性的同时保持其响应的可用性。该框架通过将基础LLM分为可用和安全两种变体，并利用动态路由机制来平衡两者在响应中的作用。面对恶意指令时，路由器会增强安全LLM的权重以确保无害响应；而对于良性指令，则优先使用可用LLM以提供有用且可用的响应。我们在多个开源LLMs上进行了比较研究，证明了MoGU框架的优越性，并展示了我们设计的路由机制能够有效平衡两种变体的贡献。此外，我们还发布了更安全的Llama2、Vicuna、Falcon、Dolphin和Baichuan2。

> Large Language Models (LLMs) are increasingly deployed in various applications. As their usage grows, concerns regarding their safety are rising, especially in maintaining harmless responses when faced with malicious instructions. Many defense strategies have been developed to enhance the safety of LLMs. However, our research finds that existing defense strategies lead LLMs to predominantly adopt a rejection-oriented stance, thereby diminishing the usability of their responses to benign instructions. To solve this problem, we introduce the MoGU framework, designed to enhance LLMs' safety while preserving their usability. Our MoGU framework transforms the base LLM into two variants: the usable LLM and the safe LLM, and further employs dynamic routing to balance their contribution. When encountering malicious instructions, the router will assign a higher weight to the safe LLM to ensure that responses are harmless. Conversely, for benign instructions, the router prioritizes the usable LLM, facilitating usable and helpful responses. On various open-sourced LLMs, we compare multiple defense strategies to verify the superiority of our MoGU framework. Besides, our analysis provides key insights into the effectiveness of MoGU and verifies that our designed routing mechanism can effectively balance the contribution of each variant by assigning weights. Our work released the safer Llama2, Vicuna, Falcon, Dolphin, and Baichuan2.

[Arxiv](https://arxiv.org/abs/2405.14488)