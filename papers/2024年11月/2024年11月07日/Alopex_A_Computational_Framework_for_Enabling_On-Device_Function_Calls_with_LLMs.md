# Alopex：一个能在设备上实现带有 LLMs 的函数调用的计算框架

发布时间：2024年11月07日

`LLM应用` `移动设备` `函数调用`

> Alopex: A Computational Framework for Enabling On-Device Function Calls with LLMs

# 摘要

> 大型语言模型（LLMs）发展迅猛，其在移动设备中的融合日益增多，用于提供个性化协助，使得 LLMs 能够调用外部 API 函数来增强自身性能。但数据稀缺、问题格式不佳以及灾难性遗忘等难题，阻碍了设备端 LLM 代理的发展。为应对这些状况，我们推出了 Alopex 框架，借助 Fox LLM 实现精准的设备端函数调用。Alopex 引入了基于逻辑的高质量训练数据生成方法，以及新颖的“描述 - 问题 - 输出”格式用于微调，降低了函数信息泄露的风险。另外，采用数据混合策略来缓解灾难性遗忘，将函数调用数据与教科书数据集相融合，提升在各类任务中的表现。实验结果显示，Alopex 提高了函数调用的精准度，大幅减少了灾难性遗忘，为在 LLMs 中集成函数调用能力提供了无需人工干预的有力解决方案。

> The rapid advancement of Large Language Models (LLMs) has led to their increased integration into mobile devices for personalized assistance, which enables LLMs to call external API functions to enhance their performance. However, challenges such as data scarcity, ineffective question formatting, and catastrophic forgetting hinder the development of on-device LLM agents. To tackle these issues, we propose Alopex, a framework that enables precise on-device function calls using the Fox LLM. Alopex introduces a logic-based method for generating high-quality training data and a novel ``description-question-output'' format for fine-tuning, reducing risks of function information leakage. Additionally, a data mixing strategy is used to mitigate catastrophic forgetting, combining function call data with textbook datasets to enhance performance in various tasks. Experimental results show that Alopex improves function call accuracy and significantly reduces catastrophic forgetting, providing a robust solution for integrating function call capabilities into LLMs without manual intervention.

[Arxiv](https://arxiv.org/abs/2411.05209)