# MUD：构建大规模且去噪的现代风格UI模型数据集在这项研究中，我们提出了MUD，一个旨在为现代风格UI模型提供大规模且经过噪声过滤的UI数据集。通过精心设计的去噪机制，MUD确保了数据的质量，为UI模型的训练和评估提供了坚实的基础。我们的目标是推动UI设计领域的进步，使得模型能够更好地理解和生成符合现代审美的用户界面。

发布时间：2024年05月11日

`LLM应用

这篇论文探讨了如何利用大型语言模型（LLMs）来自动挖掘Android应用中的UI数据，以创建高质量的移动UI数据集。这种方法涉及模拟人类探索行为和应用噪声过滤技术，以及人工验证，以确保数据集的质量。论文的结果展示了这种方法在生成用于现代UI研究的基石数据集方面的潜力。因此，这篇论文属于LLM应用类别，因为它展示了LLMs在实际应用中的使用，特别是在数据挖掘和UI研究领域。` `移动应用开发` `用户界面设计`

> MUD: Towards a Large-Scale and Noise-Filtered UI Dataset for Modern Style UI Modeling

# 摘要

> 移动UI的计算建模至关重要，但高质量的UI数据集是前提。现有数据集陈旧且噪声多，难以满足需求。本文提出一种新方法，利用LLMs自动挖掘Android应用中的UI数据，模拟人类探索行为。我们采用先进的噪声过滤技术，并辅以人工验证，确保数据集质量。实验证明，这种方法能有效挖掘出18,000个高质量UI，覆盖3,300个应用，形成MUD数据集。在元素检测和UI检索两项任务中，MUD展现了其作为现代UI研究基石的潜力。

> The importance of computational modeling of mobile user interfaces (UIs) is undeniable. However, these require a high-quality UI dataset. Existing datasets are often outdated, collected years ago, and are frequently noisy with mismatches in their visual representation. This presents challenges in modeling UI understanding in the wild. This paper introduces a novel approach to automatically mine UI data from Android apps, leveraging Large Language Models (LLMs) to mimic human-like exploration. To ensure dataset quality, we employ the best practices in UI noise filtering and incorporate human annotation as a final validation step. Our results demonstrate the effectiveness of LLMs-enhanced app exploration in mining more meaningful UIs, resulting in a large dataset MUD of 18k human-annotated UIs from 3.3k apps. We highlight the usefulness of MUD in two common UI modeling tasks: element detection and UI retrieval, showcasing its potential to establish a foundation for future research into high-quality, modern UIs.

[Arxiv](https://arxiv.org/abs/2405.07090)