# GeckOpt：通过意图驱动的工具选择优化大型语言模型的系统效能。

发布时间：2024年04月24日

`LLM应用` `人工智能`

> GeckOpt: LLM System Efficiency via Intent-Based Tool Selection

# 摘要

> 本研究初步探讨了一种利用GPT进行意图驱动推理的方法，目的是为大型语言模型（LLMs）精简工具选择流程，以提升系统效率。该方法通过实时识别用户输入背后的意图，有效缩小了完成任务所需的API工具范围，从而将令牌使用量降低了最多24.6%。在一个真实世界的大规模并行Copilot平台上，超过100个GPT-4-Turbo节点的初步测试结果显示，成本有所降低，显示出提升基于LLM系统效率的潜力。

> In this preliminary study, we investigate a GPT-driven intent-based reasoning approach to streamline tool selection for large language models (LLMs) aimed at system efficiency. By identifying the intent behind user prompts at runtime, we narrow down the API toolset required for task execution, reducing token consumption by up to 24.6\%. Early results on a real-world, massively parallel Copilot platform with over 100 GPT-4-Turbo nodes show cost reductions and potential towards improving LLM-based system efficiency.

![GeckOpt：通过意图驱动的工具选择优化大型语言模型的系统效能。](../../../paper_images/2404.15804/geckopt-teaser.png)

[Arxiv](https://arxiv.org/abs/2404.15804)