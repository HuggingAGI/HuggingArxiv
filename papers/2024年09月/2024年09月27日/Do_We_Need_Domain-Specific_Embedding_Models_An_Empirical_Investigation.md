# 特定领域嵌入模型，真的必要吗？让我们通过实证研究一探究竟。

发布时间：2024年09月27日

`LLM应用`

> Do We Need Domain-Specific Embedding Models? An Empirical Investigation

# 摘要

> 嵌入模型在 NLP 应用中至关重要，而 LLM 的进步使其性能更上一层楼。然而，当通用模型已涵盖广泛领域文本时，是否还需特定领域模型？我们以金融领域为例，通过引入 FinMTEB 数据集，发现最先进模型在金融领域的性能显著下降。为探究原因，我们量化了数据集复杂性，并得出结论：即使在大规模通用语料库上训练，模型仍难以捕捉特定领域细节。这强调了开发特定领域模型的必要性，为研究和实践提供了重要启示。

> Embedding models play a crucial role in representing and retrieving information across various NLP applications. Recent advancements in Large Language Models (LLMs) have further enhanced the performance of embedding models, which are trained on massive amounts of text covering almost every domain. These models are often benchmarked on general-purpose datasets like Massive Text Embedding Benchmark (MTEB), where they demonstrate superior performance. However, a critical question arises: Is the development of domain-specific embedding models necessary when general-purpose models are trained on vast corpora that already include specialized domain texts? In this paper, we empirically investigate this question, choosing the finance domain as an example. We introduce the Finance Massive Text Embedding Benchmark (FinMTEB), a counterpart to MTEB that consists of financial domain-specific text datasets. We evaluate the performance of seven state-of-the-art embedding models on FinMTEB and observe a significant performance drop compared to their performance on MTEB. To account for the possibility that this drop is driven by FinMTEB's higher complexity, we propose four measures to quantify dataset complexity and control for this factor in our analysis. Our analysis provides compelling evidence that state-of-the-art embedding models struggle to capture domain-specific linguistic and semantic patterns, even when trained on large general-purpose corpora. This study sheds light on the necessity of developing domain-specific embedding models in the LLM era, offering valuable insights for researchers and practitioners.

[Arxiv](https://arxiv.org/abs/2409.18511)