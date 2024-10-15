# KBLaM：知识库赋能的语言模型

发布时间：2024年10月14日

`RAG` `人工智能` `知识库`

> KBLaM: Knowledge Base augmented Language Model

# 摘要

> 本文介绍了一种名为 KBLaM 的新方法，通过外部知识库增强大型语言模型。KBLaM 利用预训练的句子编码器将知识库中的信息转换为连续的键值向量，并通过矩形注意力机制将其融入 LLM。与依赖外部检索模块的方法不同，KBLaM 的计算复杂度与知识库大小成线性关系，而非二次关系。这使得 KBLaM 能够高效地将大规模知识库集成到 LLM 中，并在单个 GPU 上实现动态更新，无需重新训练模型。实验结果显示，KBLaM 在问答和开放式推理等任务中表现出色，同时提供了对其知识使用方式的清晰解释。

> In this paper, we propose Knowledge Base augmented Language Model (KBLaM), a new method for augmenting Large Language Models (LLMs) with external knowledge. KBLaM works with a knowledge base (KB) constructed from a corpus of documents, transforming each piece of knowledge in the KB into continuous key-value vector pairs via pre-trained sentence encoders with linear adapters and integrating them into pre-trained LLMs via a specialized rectangular attention mechanism. Unlike Retrieval-Augmented Generation, KBLaM eliminates external retrieval modules, and unlike in-context learning, its computational overhead scales linearly with KB size rather than quadratically. Our approach enables integrating a large KB of more than 10K triples into an 8B pre-trained LLM of only 8K context window on one single A100 80GB GPU and allows for dynamic updates without model fine-tuning or retraining. Experiments demonstrate KBLaM's effectiveness in various tasks, including question-answering and open-ended reasoning, while providing interpretable insights into its use of the augmented knowledge.

[Arxiv](https://arxiv.org/abs/2410.10450)