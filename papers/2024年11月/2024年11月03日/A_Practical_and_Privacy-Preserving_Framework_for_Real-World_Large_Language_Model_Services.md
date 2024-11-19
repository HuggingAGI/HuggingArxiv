# 一个适用于现实世界中大型语言模型服务的实用且注重隐私保护的框架

发布时间：2024年11月03日

`LLM应用` `人工智能` `隐私保护`

> A Practical and Privacy-Preserving Framework for Real-World Large Language Model Services

# 摘要

> 大型语言模型（LLMs）在文本理解与生成领域表现出色，在众多领域中被广泛应用以提升生产力。然而，鉴于训练和维护这些模型的高昂成本，加之部分LLMs具有专有性，个人通常依赖LLM公司提供的在线人工智能即服务（AIaaS）。此商业模式存在显著的隐私风险，因为服务提供商可能会利用用户的跟踪模式和行为数据。本文中，我们提出了一个实用且注重隐私保护的框架，能防止服务提供商将请求与提交者关联，从而确保用户匿名。我们的框架基于部分盲签名，保障了用户请求的不可关联性。此外，我们针对基于订阅和基于API的服务模型推出了两种策略，既保护了用户隐私，又顾及了服务提供商的利益。该框架设计可与现有LLM系统无缝衔接，无需对底层架构进行改动。实验结果显示，我们的框架产生的计算和通信开销极低，是现实应用中的可行之选。

> Large language models (LLMs) have demonstrated exceptional capabilities in text understanding and generation, and they are increasingly being utilized across various domains to enhance productivity. However, due to the high costs of training and maintaining these models, coupled with the fact that some LLMs are proprietary, individuals often rely on online AI as a Service (AIaaS) provided by LLM companies. This business model poses significant privacy risks, as service providers may exploit users' trace patterns and behavioral data. In this paper, we propose a practical and privacy-preserving framework that ensures user anonymity by preventing service providers from linking requests to the individuals who submit them. Our framework is built on partially blind signatures, which guarantee the unlinkability of user requests. Furthermore, we introduce two strategies tailored to both subscription-based and API-based service models, ensuring the protection of both users' privacy and service providers' interests. The framework is designed to integrate seamlessly with existing LLM systems, as it does not require modifications to the underlying architectures. Experimental results demonstrate that our framework incurs minimal computation and communication overhead, making it a feasible solution for real-world applications.

[Arxiv](https://arxiv.org/abs/2411.01471)