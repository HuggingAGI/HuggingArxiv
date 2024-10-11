# MoDEM：领域专家模型的融合

发布时间：2024年10月09日

`LLM应用` `人工智能`

> MoDEM: Mixture of Domain Expert Models

# 摘要

> 我们提出了一种创新方法，通过结合领域提示路由和领域专用模型，提升大型语言模型（LLM）的性能与效率。我们设计了一个系统，利用基于 BERT 的路由器，将提示精准引导至最适合的领域专家模型，这些模型专为健康、数学和科学等领域优化。研究显示，这种方法在性能上显著超越同等规模的全能模型，在多个基准测试中实现了更佳的性能成本比。这预示着 LLM 开发与部署的范式转变：未来 AI 的发展或将聚焦于构建小型、高度专业化的模型生态系统，辅以精密的路由系统，从而实现资源的高效利用、计算成本的降低及整体性能的提升。

> We propose a novel approach to enhancing the performance and efficiency of large language models (LLMs) by combining domain prompt routing with domain-specialized models. We introduce a system that utilizes a BERT-based router to direct incoming prompts to the most appropriate domain expert model. These expert models are specifically tuned for domains such as health, mathematics and science. Our research demonstrates that this approach can significantly outperform general-purpose models of comparable size, leading to a superior performance-to-cost ratio across various benchmarks. The implications of this study suggest a potential paradigm shift in LLM development and deployment. Rather than focusing solely on creating increasingly large, general-purpose models, the future of AI may lie in developing ecosystems of smaller, highly specialized models coupled with sophisticated routing systems. This approach could lead to more efficient resource utilization, reduced computational costs, and superior overall performance.

[Arxiv](https://arxiv.org/abs/2410.07490)