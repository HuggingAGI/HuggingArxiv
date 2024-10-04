# EmbedLLM：探索大型语言模型的精简表达

发布时间：2024年10月03日

`LLM应用` `人工智能` `软件工程`

> EmbedLLM: Learning Compact Representations of Large Language Models

# 摘要

> 在 Huggingface 上，数十万个语言模型等待着被高效评估和利用，尤其是在各种下游任务中。现有方法往往重复学习 LLM 的任务特定表示，导致时间和计算资源的浪费。为此，我们推出了 EmbedLLM，一个专注于学习紧凑向量表示的框架，旨在优化多模型参与的下游应用，如模型路由。我们采用编码器-解码器架构来生成这些嵌入，并构建了系统化的评估体系。实验数据显示，EmbedLLM 在模型路由的准确性和速度上均超越了以往方法。更值得一提的是，我们的方法能在不增加推理负担的前提下，精准预测模型在多基准测试中的表现。通过深入的探测实验，我们发现 EmbedLLM 所生成的嵌入能有效捕捉模型的核心特性，如是否擅长编码任务，即便未经过专门训练。为推动后续研究与应用，我们已将数据集、代码及嵌入器开源。

> With hundreds of thousands of language models available on Huggingface today, efficiently evaluating and utilizing these models across various downstream, tasks has become increasingly critical. Many existing methods repeatedly learn task-specific representations of Large Language Models (LLMs), which leads to inefficiencies in both time and computational resources. To address this, we propose EmbedLLM, a framework designed to learn compact vector representations, of LLMs that facilitate downstream applications involving many models, such as model routing. We introduce an encoder-decoder approach for learning such embeddings, along with a systematic framework to evaluate their effectiveness. Empirical results show that EmbedLLM outperforms prior methods in model routing both in accuracy and latency. Additionally, we demonstrate that our method can forecast a model's performance on multiple benchmarks, without incurring additional inference cost. Extensive probing experiments validate that the learned embeddings capture key model characteristics, e.g. whether the model is specialized for coding tasks, even without being explicitly trained on them. We open source our dataset, code and embedder to facilitate further research and application.

[Arxiv](https://arxiv.org/abs/2410.02223)