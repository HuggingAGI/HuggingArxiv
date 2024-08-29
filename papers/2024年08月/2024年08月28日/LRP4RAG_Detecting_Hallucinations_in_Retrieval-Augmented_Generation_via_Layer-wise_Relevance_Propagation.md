# LRP4RAG：利用层级相关性传播技术，精准检测检索增强生成模型中的幻觉现象。

发布时间：2024年08月28日

`RAG` `人工智能`

> LRP4RAG: Detecting Hallucinations in Retrieval-Augmented Generation via Layer-wise Relevance Propagation

# 摘要

> RAG 技术虽能减轻 LLM 中的幻觉问题，但知识提取的不完整和理解不足仍可能导致生成无关或矛盾的回应。为此，我们提出 LRP4RAG 方法，利用 LRP 算法检测 RAG 中的幻觉。通过计算输入与输出的相关性，并对其进行精细处理和分类，LRP4RAG 能有效识别幻觉。实验结果显示，该方法性能优于现有技术，为 RAG 幻觉检测开辟了新途径。

> Retrieval-Augmented Generation (RAG) has become a primary technique for mitigating hallucinations in large language models (LLMs). However, incomplete knowledge extraction and insufficient understanding can still mislead LLMs to produce irrelevant or even contradictory responses, which means hallucinations persist in RAG. In this paper, we propose LRP4RAG, a method based on the Layer-wise Relevance Propagation (LRP) algorithm for detecting hallucinations in RAG. Specifically, we first utilize LRP to compute the relevance between the input and output of the RAG generator. We then apply further extraction and resampling to the relevance matrix. The processed relevance data are input into multiple classifiers to determine whether the output contains hallucinations. To the best of our knowledge, this is the first time that LRP has been used for detecting RAG hallucinations, and extensive experiments demonstrate that LRP4RAG outperforms existing baselines.

[Arxiv](https://arxiv.org/abs/2408.15533)