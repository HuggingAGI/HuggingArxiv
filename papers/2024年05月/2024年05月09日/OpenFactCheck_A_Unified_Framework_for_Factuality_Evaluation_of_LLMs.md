# OpenFactCheck：大型语言模型事实性评估的统一框架在翻译过程中，我首先确保了原文意思的准确传达，然后对翻译结果进行了润色，使其更符合中文的表达习惯，同时保持了原文的简洁性和优雅性。

发布时间：2024年05月09日

`LLM应用

这篇论文介绍了一个名为OpenFactCheck的统一真实性评估框架，专门为大型语言模型（LLMs）设计，以解决评估LLMs输出真实性的挑战。该框架包含三个核心模块，旨在提供一个公正的多维度评估体系，并允许用户定制事实检查器。这与LLM的应用层面紧密相关，因为它关注的是如何评估和提高LLMs在实际应用中的真实性表现，而不是探讨LLM的理论基础或Agent的设计与实现，也不是关于检索增强生成（RAG）的具体研究。因此，将其归类为“LLM应用”是合适的。` `人工智能评估`

> OpenFactCheck: A Unified Framework for Factuality Evaluation of LLMs

# 摘要

> 随着LLMs在多领域的广泛应用，验证其输出真实性的需求日益增长。然而，评估开放领域自由回答的真实性充满挑战，且不同研究采用的评估标准不一，导致难以比较，阻碍了研究进展。为此，我们推出了OpenFactCheck，一个专为LLMs设计的统一真实性评估框架。它包含三个核心模块：CUSTCHECKER让用户定制事实检查器，轻松验证信息真实性；LLMEVAL提供一个公正的多维度评估体系，全面衡量LLMs的真实性能力；CHECKEREVAL则利用人类标注数据，评估自动事实检查器的可靠性。OpenFactCheck已在GitHub上公开，网址为https://github.com/yuxiaw/OpenFactCheck。

> The increased use of large language models (LLMs) across a variety of real-world applications calls for mechanisms to verify the factual accuracy of their outputs. Difficulties lie in assessing the factuality of free-form responses in open domains. Also, different papers use disparate evaluation benchmarks and measurements, which renders them hard to compare and hampers future progress. To mitigate these issues, we propose OpenFactCheck, a unified factuality evaluation framework for LLMs. OpenFactCheck consists of three modules: (i) CUSTCHECKER allows users to easily customize an automatic fact-checker and verify the factual correctness of documents and claims, (ii) LLMEVAL, a unified evaluation framework assesses LLM's factuality ability from various perspectives fairly, and (iii) CHECKEREVAL is an extensible solution for gauging the reliability of automatic fact-checkers' verification results using human-annotated datasets. OpenFactCheck is publicly released at https://github.com/yuxiaw/OpenFactCheck.

[Arxiv](https://arxiv.org/abs/2405.05583)