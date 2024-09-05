# LongCite 技术让 LLM 在长篇问答中也能精准生成引用，提升了引用的细致度和准确性。

发布时间：2024年09月04日

`LLM应用` `人工智能`

> LongCite: Enabling LLMs to Generate Fine-grained Citations in Long-context QA

# 摘要

> 尽管长上下文 LLM 在处理大量文本并回答问题方面表现出色，但其回答中缺乏引用导致用户难以验证，进而引发对其可信度的疑虑。为此，我们致力于让长上下文 LLM 生成包含细粒度句子级引用的回答，以提升其忠实度和可验证性。我们首先推出了 LongBench-Cite 基准，用于评估 LLM 在长上下文问答中的表现，并揭示了显著的改进空间。接着，我们设计了 CoF 流程，利用现有 LLM 自动生成精确引用，并构建了 LongCite-45k 数据集。基于此数据集，我们训练了 LongCite-8B 和 LongCite-9B 模型，使其能在单次输出中提供准确回答及详细引用。评估结果表明，我们的模型在引用质量上超越了包括 GPT-4o 在内的顶尖专有模型，达到了业界领先水平。

> Though current long-context large language models (LLMs) have demonstrated impressive capacities in answering user questions based on extensive text, the lack of citations in their responses makes user verification difficult, leading to concerns about their trustworthiness due to their potential hallucinations. In this work, we aim to enable long-context LLMs to generate responses with fine-grained sentence-level citations, improving their faithfulness and verifiability. We first introduce LongBench-Cite, an automated benchmark for assessing current LLMs' performance in Long-Context Question Answering with Citations (LQAC), revealing considerable room for improvement. To this end, we propose CoF (Coarse to Fine), a novel pipeline that utilizes off-the-shelf LLMs to automatically generate long-context QA instances with precise sentence-level citations, and leverage this pipeline to construct LongCite-45k, a large-scale SFT dataset for LQAC. Finally, we train LongCite-8B and LongCite-9B using the LongCite-45k dataset, successfully enabling their generation of accurate responses and fine-grained sentence-level citations in a single output. The evaluation results on LongBench-Cite show that our trained models achieve state-of-the-art citation quality, surpassing advanced proprietary models including GPT-4o.

[Arxiv](https://arxiv.org/abs/2409.02897)