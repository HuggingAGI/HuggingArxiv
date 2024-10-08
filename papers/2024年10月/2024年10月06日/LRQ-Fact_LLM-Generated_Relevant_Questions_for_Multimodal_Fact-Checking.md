# LRQ-Fact：多模态事实核查中的 LLM 生成相关问题

发布时间：2024年10月06日

`LLM应用` `信息安全`

> LRQ-Fact: LLM-Generated Relevant Questions for Multimodal Fact-Checking

# 摘要

> 人类事实核查员凭借专业知识能提出精准问题，但这种专家驱动的方法既耗时又难以扩展，尤其在处理复杂的多模态错误信息时。为此，我们提出了全自动框架 LRQ-Fact，用于多模态事实核查。该框架首先利用视觉语言模型和大型语言模型生成详尽的问题与答案，以深入分析多模态内容。随后，基于规则的决策模块综合评估原始内容与生成内容，以判断其真实性。实验结果显示，LRQ-Fact 显著提升了多模态错误信息的检测精度。此外，我们还评估了其在不同模型架构上的适应性，为未来的优化提供了宝贵参考。

> Human fact-checkers have specialized domain knowledge that allows them to formulate precise questions to verify information accuracy. However, this expert-driven approach is labor-intensive and is not scalable, especially when dealing with complex multimodal misinformation. In this paper, we propose a fully-automated framework, LRQ-Fact, for multimodal fact-checking. Firstly, the framework leverages Vision-Language Models (VLMs) and Large Language Models (LLMs) to generate comprehensive questions and answers for probing multimodal content. Next, a rule-based decision-maker module evaluates both the original content and the generated questions and answers to assess the overall veracity. Extensive experiments on two benchmarks show that LRQ-Fact improves detection accuracy for multimodal misinformation. Moreover, we evaluate its generalizability across different model backbones, offering valuable insights for further refinement.

[Arxiv](https://arxiv.org/abs/2410.04616)