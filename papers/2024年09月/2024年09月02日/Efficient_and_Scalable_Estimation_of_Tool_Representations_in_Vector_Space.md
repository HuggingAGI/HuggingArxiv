# 向量空间中工具表示的高效与可扩展估计

发布时间：2024年09月02日

`LLM应用` `软件开发` `人工智能`

> Efficient and Scalable Estimation of Tool Representations in Vector Space

# 摘要

> 近期，函数调用与工具使用的进步大幅提升了大型语言模型（LLMs）的交互与任务执行能力。但LLMs的上下文窗口限制，在工具丰富环境下，要求高效管理提示长度并确保准确性。传统方法如模型微调或依赖推理，或需频繁再训练，或带来高延迟。我们提出更高效方案：训练小型模型精准检索相关工具，虽需优质领域数据。为此，我们创新合成数据框架及数据驱动检索策略，借助LLMs打造ToolBank数据集，真实映射用户需求。我们引入Tool2Vec、ToolRefiner及MLC等创新方法，显著提升工具检索性能，ToolBench与ToolBank数据集上Recall@K分别提升27.28与30.5。实验结果充分验证了方法的有效性。代码已公开于\url{https://github.com/SqueezeAILab/Tool2Vec}。

> Recent advancements in function calling and tool use have significantly enhanced the capabilities of large language models (LLMs) by enabling them to interact with external information sources and execute complex tasks. However, the limited context window of LLMs presents challenges when a large number of tools are available, necessitating efficient methods to manage prompt length and maintain accuracy. Existing approaches, such as fine-tuning LLMs or leveraging their reasoning capabilities, either require frequent retraining or incur significant latency overhead. A more efficient solution involves training smaller models to retrieve the most relevant tools for a given query, although this requires high quality, domain-specific data. To address those challenges, we present a novel framework for generating synthetic data for tool retrieval applications and an efficient data-driven tool retrieval strategy using small encoder models. Empowered by LLMs, we create ToolBank, a new tool retrieval dataset that reflects real human user usages. For tool retrieval methodologies, we propose novel approaches: (1) Tool2Vec: usage-driven tool embedding generation for tool retrieval, (2) ToolRefiner: a staged retrieval method that iteratively improves the quality of retrieved tools, and (3) MLC: framing tool retrieval as a multi-label classification problem. With these new methods, we achieve improvements of up to 27.28 in Recall@K on the ToolBench dataset and 30.5 in Recall@K on ToolBank. Additionally, we present further experimental results to rigorously validate our methods. Our code is available at \url{https://github.com/SqueezeAILab/Tool2Vec}

[Arxiv](https://arxiv.org/abs/2409.02141)