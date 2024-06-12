# LLM-dCache：利用GPT驱动本地数据缓存优化工具增强的大型语言模型

发布时间：2024年06月10日

`Agent

这篇论文介绍了一种名为LLM-dCache的新技术，它通过将缓存操作转化为可调用的API函数来优化数据访问，并允许大型语言模型（LLMs）通过提示自主管理缓存决策。这种方法与现有的函数调用机制无缝集成，并在工业级并行平台上进行了测试，显著提升了运行速度。这种技术涉及LLMs的自主决策和操作，因此属于Agent分类。` `云计算` `人工智能`

> LLM-dCache: Improving Tool-Augmented LLMs with GPT-Driven Localized Data Caching

# 摘要

> 随着大型语言模型（LLMs）能力的扩展，它们在处理大量API调用时面临跨大数据集的复杂数据操作，给系统带来沉重负担。为此，我们开发了LLM-dCache，通过将缓存操作转化为可调用的API函数，优化数据访问，并允许LLMs通过提示自主管理缓存决策，与现有函数调用机制无缝集成。在覆盖数百个GPT端点和数TB图像数据的工业级并行平台上测试，我们的方法在不同LLMs和提示技术中平均提升了Copilot运行速度1.24倍。

> As Large Language Models (LLMs) broaden their capabilities to manage thousands of API calls, they are confronted with complex data operations across vast datasets with significant overhead to the underlying system. In this work, we introduce LLM-dCache to optimize data accesses by treating cache operations as callable API functions exposed to the tool-augmented agent. We grant LLMs the autonomy to manage cache decisions via prompting, seamlessly integrating with existing function-calling mechanisms. Tested on an industry-scale massively parallel platform that spans hundreds of GPT endpoints and terabytes of imagery, our method improves Copilot times by an average of 1.24x across various LLMs and prompting techniques.

[Arxiv](https://arxiv.org/abs/2406.06799)