# 安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量

发布时间：2024年04月24日

`LLM应用` `文本服务` `用户体验`

> Andes: Defining and Enhancing Quality-of-Experience in LLM-Based Text Streaming Services

# 摘要

> 大型语言模型（LLMs）的兴起彻底改变了文本服务领域，开启了从即时翻译到AI聊天机器人的多样化功能。不过，现行的服务系统多集中于提升服务器端的综合指标，如令牌生成速率，而忽视了用户在实时文本流中的体验。这导致在高流量或流量高峰时段，许多用户可能会遭遇服务品质下降或体验质量（QoE）不佳的问题。本文首先明确界定了文本流服务的QoE，即文本以增量和互动方式传递给用户，考虑了与用户互动的整个过程中端到端的令牌传递。接着，我们提出了Andes，这是一个注重QoE的服务系统，旨在提升LLM支持的文本流服务的用户体验。Andes核心在于智能分配多个请求之间的GPU资源，以时间为基础优化用户体验。我们的评估显示，与现有的顶尖LLM服务系统vLLM相比，Andes在高请求率下平均QoE提升了高达3.2倍，或者在保持高QoE的同时，实现了最多1.6倍的请求率提升。

> The advent of large language models (LLMs) has transformed text-based services, enabling capabilities ranging from real-time translation to AI-driven chatbots. However, existing serving systems primarily focus on optimizing server-side aggregate metrics like token generation throughput, ignoring individual user experience with streamed text. As a result, under high and/or bursty load, a significant number of users can receive unfavorable service quality or poor Quality-of-Experience (QoE). In this paper, we first formally define QoE of text streaming services, where text is delivered incrementally and interactively to users, by considering the end-to-end token delivery process throughout the entire interaction with the user. Thereafter, we propose Andes, a QoE-aware serving system that enhances user experience for LLM-enabled text streaming services. At its core, Andes strategically allocates contended GPU resources among multiple requests over time to optimize their QoE. Our evaluations demonstrate that, compared to the state-of-the-art LLM serving systems like vLLM, Andes improves the average QoE by up to 3.2$\times$ under high request rate, or alternatively, it attains up to 1.6$\times$ higher request rate while preserving high QoE.

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x1.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x2.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x3.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x4.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x5.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x6.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x7.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x8.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x9.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x10.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x11.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x12.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x13.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x14.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x15.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x16.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x17.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x18.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x19.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x20.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x21.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x22.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x23.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x24.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x25.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x26.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x27.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x28.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x29.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x30.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x31.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x32.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x33.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x34.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x35.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x36.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x37.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x38.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x39.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x40.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x41.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x42.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x43.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x44.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x45.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x46.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x47.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x48.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x49.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x50.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x51.png)

![安第斯：为基于大型语言模型的文本流服务定义并提升用户体验质量](../../../paper_images/2404.16283/x52.png)

[Arxiv](https://arxiv.org/abs/2404.16283)