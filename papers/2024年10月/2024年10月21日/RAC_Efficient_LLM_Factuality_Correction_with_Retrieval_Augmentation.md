# RAC：通过检索增强实现高效 LLM 事实校正

发布时间：2024年10月21日

`RAG` `人工智能`

> RAC: Efficient LLM Factuality Correction with Retrieval Augmentation

# 摘要

> 大型语言模型 (LLM) 在众多 NLP 任务中表现出色，但常出现事实错误。本文提出了一种高效低延迟的后校正方法——\textbf{Retrieval Augmented Correction (RAC)}，无需额外微调即可提升 LLM 的事实准确性。RAC 通用性强，适用于任何指令微调的 LLM，且延迟显著降低。它将 LLM 输出分解为原子事实，通过细粒度验证和校正过程，结合检索内容进行校正。实验显示，RAC 在两个真实性评估数据集上比最先进基线提升高达 30\%，无论是否集成 Retrieval-Augmented Generation (RAG)，均表现出色。\footnote{代码详见 \url{https://github.com/jlab-nlp/Retrieval-Augmented-Correction}}

> Large Language Models (LLMs) exhibit impressive results across a wide range of natural language processing (NLP) tasks, yet they can often produce factually incorrect outputs. This paper introduces a simple but effective low-latency post-correction method, \textbf{Retrieval Augmented Correction (RAC)}, aimed at enhancing the factual performance of LLMs without requiring additional fine-tuning. Our method is general and can be used with any instruction-tuned LLM, and has greatly reduced latency compared to prior approaches. RAC decomposes the LLM's output into atomic facts and applies a fine-grained verification and correction process with retrieved content to verify and correct the LLM-generated output. Our extensive experiments show that RAC yields up to 30\% improvements over state-of-the-art baselines across two popular factuality evaluation datasets, validating its efficacy and robustness in both with and without the integration of Retrieval-Augmented Generation (RAG) across different LLMs.\footnote{Our code is at \url{https://github.com/jlab-nlp/Retrieval-Augmented-Correction}}

[Arxiv](https://arxiv.org/abs/2410.15667)