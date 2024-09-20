# 基于熟悉度的证据压缩技术，助力检索增强生成

发布时间：2024年09月19日

`RAG` `问答系统`

> Familiarity-aware Evidence Compression for Retrieval Augmented Generation

# 摘要

> RAG 通过从外部源检索证据来增强大型语言模型 (LMs)，但常难以过滤掉不一致和无关的信息。虽然压缩模型旨在解决这一问题，但压缩后的证据可能对目标模型仍不熟悉，影响其有效利用。我们提出 FaviComp，一种无需训练的证据压缩技术，使检索到的证据对目标模型更加熟悉，同时无缝集成参数知识。FaviComp 通过结合压缩模型和目标模型的标记概率，生成对目标模型更熟悉的内容，从而降低困惑度。这种方法在复杂任务中特别有用，实验结果显示，FaviComp 在多个开放域 QA 数据集上持续优于现有基线，实现了高压缩率，并有效整合了参数和非参数知识。

> Retrieval Augmented Generation (RAG) improves large language models (LMs) by incorporating non-parametric knowledge through evidence retrieval from external sources. However, it often struggles to filter out inconsistent and irrelevant information that can distract the LM from its tasks. While compressing the retrieved evidence with a compression model aims to address this issue, the compressed evidence may still be unfamiliar to the target model used for downstream task, potentially failing to utilize the evidence effectively. We propose FaviComp (Familiarity-aware Evidence Compression), a novel training-free evidence compression technique that makes retrieved evidence more familiar to the target model, while seamlessly integrating parametric knowledge from the model. Specifically, FaviComp proactively lowers the perplexity of the compressed evidence with regard to the target model by combining token probabilities from both the compression model and the target model to generate context that is more familiar to the target model. This approach balances the integration of parametric and non-parametric knowledge, which is especially helpful in complex tasks where the retrieved evidence set may not contain all the necessary information. Experimental results demonstrate that FaviComp consistently outperforms existing baselines in multiple open-domain QA datasets, achieving high compression rates and showcasing the effective integration of both parametric and non-parametric knowledge.

[Arxiv](https://arxiv.org/abs/2409.12468)