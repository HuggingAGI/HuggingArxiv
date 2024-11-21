# E2E-AFG：一种用于检索增强生成且具备自适应过滤功能的端到端模型

发布时间：2024年11月01日

`RAG` `知识检索` `语言模型`

> E2E-AFG: An End-to-End Model with Adaptive Filtering for Retrieval-Augmented Generation

# 摘要

> 检索增强生成的方法往往忽视从外部知识库检索到的内容的质量，由此产生不相关的信息或潜在的错误信息，给大型语言模型的生成结果带来负面影响。在本文中，我们提出了用于检索增强生成的具有自适应过滤功能的端到端模型（E2E-AFG），它把答案存在判断和文本生成整合进一个单一的端到端框架。这让模型能更有效地聚焦于相关内容，同时降低不相关信息的影响并生成准确答案。我们在六个有代表性的知识密集型语言数据集上对 E2E-AFG 进行评估，结果显示它在所有任务中都一直优于基线模型，证明了所提方法的有效性和稳健性。

> Retrieval-augmented generation methods often neglect the quality of content retrieved from external knowledge bases, resulting in irrelevant information or potential misinformation that negatively affects the generation results of large language models. In this paper, we propose an end-to-end model with adaptive filtering for retrieval-augmented generation (E2E-AFG), which integrates answer existence judgment and text generation into a single end-to-end framework. This enables the model to focus more effectively on relevant content while reducing the influence of irrelevant information and generating accurate answers. We evaluate E2E-AFG on six representative knowledge-intensive language datasets, and the results show that it consistently outperforms baseline models across all tasks, demonstrating the effectiveness and robustness of the proposed approach.

[Arxiv](https://arxiv.org/abs/2411.00437)