# Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量

发布时间：2024年04月24日

`LLM应用` `文本服务` `用户体验`

> Andes: Defining and Enhancing Quality-of-Experience in LLM-Based Text Streaming Services

# 摘要

> 大型语言模型（LLM）的问世，彻底革新了文本服务领域，从即时翻译到AI聊天机器人，开启了多种可能性。但现有服务系统多集中于提升服务器端的总体性能指标，如令牌生成速率，而忽视了用户在接收流式文本时的个性化体验。这导致在高流量或流量高峰时段，许多用户可能会遭遇服务质量不佳或体验质量（QoE）下降的问题。本文首先明确了文本流式服务的QoE定义，该服务以递增和互动的方式向用户传递文本，全面考虑了与用户互动的整个过程中端到端的令牌传递。接着，我们提出了Andes，这是一个注重QoE的服务系统，旨在提升LLM支持的文本流式服务的用户体验。Andes的核心在于，它巧妙地在多个请求之间分配有限的GPU资源，以时间为基础优化用户体验。我们的评估结果证明，与现有的顶尖LLM服务系统相比，Andes在高请求率下平均QoE提升了最多3.2倍，或者在保持高QoE的前提下，实现了最多1.6倍的请求处理能力提升。

> The advent of large language models (LLMs) has transformed text-based services, enabling capabilities ranging from real-time translation to AI-driven chatbots. However, existing serving systems primarily focus on optimizing server-side aggregate metrics like token generation throughput, ignoring individual user experience with streamed text. As a result, under high and/or bursty load, a significant number of users can receive unfavorable service quality or poor Quality-of-Experience (QoE). In this paper, we first formally define QoE of text streaming services, where text is delivered incrementally and interactively to users, by considering the end-to-end token delivery process throughout the entire interaction with the user. Thereafter, we propose Andes, a QoE-aware serving system that enhances user experience for LLM-enabled text streaming services. At its core, Andes strategically allocates contended GPU resources among multiple requests over time to optimize their QoE. Our evaluations demonstrate that, compared to the state-of-the-art LLM serving systems like vLLM, Andes improves the average QoE by up to 3.2$\times$ under high request rate, or alternatively, it attains up to 1.6$\times$ higher request rate while preserving high QoE.

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x1.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x2.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x3.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x4.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x5.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x6.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x7.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x8.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x9.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x10.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x11.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x12.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x13.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x14.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x15.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x16.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x17.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x18.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x19.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x20.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x21.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x22.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x23.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x24.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x25.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x26.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x27.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x28.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x29.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x30.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x31.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x32.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x33.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x34.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x35.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x36.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x37.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x38.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x39.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x40.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x41.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x42.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x43.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x44.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x45.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x46.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x47.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x48.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x49.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x50.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x51.png)

![Andes：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x52.png)

[Arxiv](https://arxiv.org/abs/2404.16283)