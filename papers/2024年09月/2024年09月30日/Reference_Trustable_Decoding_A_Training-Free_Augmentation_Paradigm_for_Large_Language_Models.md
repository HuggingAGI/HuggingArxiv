# 可信参考解码：一种无需训练的增强策略，专为大型语言模型设计

发布时间：2024年09月30日

`LLM应用` `人工智能`

> Reference Trustable Decoding: A Training-Free Augmentation Paradigm for Large Language Models

# 摘要

> 大型语言模型 (LLM) 发展迅猛，展示了卓越的能力。目前，In-Context Learning (ICL) 和 Parameter-Efficient Fine-Tuning (PEFT) 是增强 LLM 以适应下游任务的两大主流方法。ICL 通过构建少样本学习场景，帮助模型快速掌握领域知识或问答模式，无需改变模型参数，但存在推理速度慢和空间占用大的问题。PEFT 通过最小参数修改使模型适应任务，但仍需高硬件支持。为此，我们提出了 Reference Trustable Decoding (RTD)，一种无需微调即可快速适应新任务的范式，同时保持低推理成本。RTD 通过构建参考数据存储并优化词汇分布，生成更可信的响应，使模型以低成本适应下游任务。实验证明，RTD 为增强模型提供了新路径，并与传统方法兼容，可同时使用。

> Large language models (LLMs) have rapidly advanced and demonstrated impressive capabilities. In-Context Learning (ICL) and Parameter-Efficient Fine-Tuning (PEFT) are currently two mainstream methods for augmenting LLMs to downstream tasks. ICL typically constructs a few-shot learning scenario, either manually or by setting up a Retrieval-Augmented Generation (RAG) system, helping models quickly grasp domain knowledge or question-answering patterns without changing model parameters. However, this approach involves trade-offs, such as slower inference speed and increased space occupancy. PEFT assists the model in adapting to tasks through minimal parameter modifications, but the training process still demands high hardware requirements, even with a small number of parameters involved. To address these challenges, we propose Reference Trustable Decoding (RTD), a paradigm that allows models to quickly adapt to new tasks without fine-tuning, maintaining low inference costs. RTD constructs a reference datastore from the provided training examples and optimizes the LLM's final vocabulary distribution by flexibly selecting suitable references based on the input, resulting in more trustable responses and enabling the model to adapt to downstream tasks at a low cost. Experimental evaluations on various LLMs using different benchmarks demonstrate that RTD establishes a new paradigm for augmenting models to downstream tasks. Furthermore, our method exhibits strong orthogonality with traditional methods, allowing for concurrent usage.

[Arxiv](https://arxiv.org/abs/2409.20181)