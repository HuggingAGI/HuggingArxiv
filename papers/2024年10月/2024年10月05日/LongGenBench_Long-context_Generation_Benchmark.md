# LongGenBench：长上下文生成基准

发布时间：2024年10月05日

`LLM应用` `人工智能`

> LongGenBench: Long-context Generation Benchmark

# 摘要

> 当前的长上下文基准主要侧重于检索测试，要求 LLM 在大量文本中找到特定信息，如“大海捞针”基准。长上下文生成能力是指模型生成跨越长篇文本的连贯且准确内容的能力。尽管近期研究在检索型长上下文基准上表现出色，但评估长上下文生成能力的基准却极为匮乏。为此，我们推出了 LongGenBench，一个允许灵活配置生成上下文长度的合成基准。LongGenBench 通过重新设计问题格式，要求 LLM 提供单一、连贯的长篇答案，超越了传统基准。评估结果显示：(1) API 访问和开源模型在长上下文生成中均出现性能下降，幅度从 1.2% 到 47.1%；(2) 不同系列的 LLM 性能下降趋势各异，Gemini-1.5-Flash 在 API 访问模型中下降最小，Qwen2 系列在 LongGenBench 中在开源模型中下降最小。

> Current long-context benchmarks primarily focus on retrieval-based tests, requiring Large Language Models (LLMs) to locate specific information within extensive input contexts, such as the needle-in-a-haystack (NIAH) benchmark. Long-context generation refers to the ability of a language model to generate coherent and contextually accurate text that spans across lengthy passages or documents. While recent studies show strong performance on NIAH and other retrieval-based long-context benchmarks, there is a significant lack of benchmarks for evaluating long-context generation capabilities. To bridge this gap and offer a comprehensive assessment, we introduce a synthetic benchmark, LongGenBench, which allows for flexible configurations of customized generation context lengths. LongGenBench advances beyond traditional benchmarks by redesigning the format of questions and necessitating that LLMs respond with a single, cohesive long-context answer. Upon extensive evaluation using LongGenBench, we observe that: (1) both API accessed and open source models exhibit performance degradation in long-context generation scenarios, ranging from 1.2% to 47.1%; (2) different series of LLMs exhibit varying trends of performance degradation, with the Gemini-1.5-Flash model showing the least degradation among API accessed models, and the Qwen2 series exhibiting the least degradation in LongGenBench among open source models.

[Arxiv](https://arxiv.org/abs/2410.04199)