# STORE：以单一 LLM 实现语义分词与生成推荐的流畅整合

发布时间：2024年09月11日

`LLM应用` `电子商务` `推荐系统`

> STORE: Streamlining Semantic Tokenization and Generative Recommendation with A Single LLM

# 摘要

> 传统推荐模型依赖于物品的唯一标识符（IDs），这限制了它们利用物品内容信息和处理长尾或冷启动物品的能力。最近提出的语义分词技术，通过将物品的语义表示转化为一系列离散标记，保留了物品的语义特征，并确保语义相似的物品由相似的标记表示。然而，现有生成推荐方法涉及多个复杂子模型。本文提出一个名为STORE的统一框架，利用单一大型语言模型（LLM）同时处理语义分词和生成推荐任务。我们通过文本到标记、标记到标记的任务，以及辅助的标记到文本和文本到标记任务，以生成方式训练模型。实验证明STORE在多种推荐任务中的有效性，并将公开源码和配置，促进可重复研究。

> Traditional recommendation models often rely on unique item identifiers (IDs) to distinguish between items, which can hinder their ability to effectively leverage item content information and generalize to long-tail or cold-start items. Recently, semantic tokenization has been proposed as a promising solution that aims to tokenize each item's semantic representation into a sequence of discrete tokens. In this way, it preserves the item's semantics within these tokens and ensures that semantically similar items are represented by similar tokens. These semantic tokens have become fundamental in training generative recommendation models. However, existing generative recommendation methods typically involve multiple sub-models for embedding, quantization, and recommendation, leading to an overly complex system. In this paper, we propose to streamline the semantic tokenization and generative recommendation process with a unified framework, dubbed STORE, which leverages a single large language model (LLM) for both tasks. Specifically, we formulate semantic tokenization as a text-to-token task and generative recommendation as a token-to-token task, supplemented by a token-to-text reconstruction task and a text-to-token auxiliary task. All these tasks are framed in a generative manner and trained using a single LLM backbone. Extensive experiments have been conducted to validate the effectiveness of our STORE framework across various recommendation tasks and datasets. We will release the source code and configurations for reproducible research.

[Arxiv](https://arxiv.org/abs/2409.07276)