# 边缘创作：优化长篇上下文检索的推理策略

发布时间：2024年08月27日

`RAG` `人工智能` `信息检索`

> Writing in the Margins: Better Inference Pattern for Long Context Retrieval

# 摘要

> 本文引入 Writing in the Margins (WiM)，一种专为大型语言模型设计的新推理模式，旨在优化长输入序列在检索任务中的处理。WiM 通过键值缓存的块状预填充进行分段推理，不仅高效处理广泛上下文，还生成和分类指导模型向特定任务的中间信息（“边缘”）。这种方法在几乎不增加计算负担的情况下，大幅提升现成模型的性能，无需微调。具体来说，WiM 使推理技能（如 HotpotQA 和 MultiHop-RAG）的准确性平均提升 7.5%，聚合任务（如 CWE）的 F1 分数提升超过 30.0%。此外，WiM 融入交互式检索设计，实时向用户更新上下文处理进度，并精确整合相关信息至最终响应。WiM 的实现已通过 Hugging Face Transformers 库发布，详见 https://github.com/writer/writing-in-the-margins。

> In this paper, we introduce Writing in the Margins (WiM), a new inference pattern for Large Language Models designed to optimize the handling of long input sequences in retrieval-oriented tasks. This approach leverages the chunked prefill of the key-value cache to perform segment-wise inference, which enables efficient processing of extensive contexts along with the generation and classification of intermediate information ("margins") that guide the model towards specific tasks. This method increases computational overhead marginally while significantly enhancing the performance of off-the-shelf models without the need for fine-tuning. Specifically, we observe that WiM provides an average enhancement of 7.5% in accuracy for reasoning skills (HotpotQA, MultiHop-RAG) and more than a 30.0% increase in the F1-score for aggregation tasks (CWE). Additionally, we show how the proposed pattern fits into an interactive retrieval design that provides end-users with ongoing updates about the progress of context processing, and pinpoints the integration of relevant information into the final response. We release our implementation of WiM using Hugging Face Transformers library at https://github.com/writer/writing-in-the-margins.

[Arxiv](https://arxiv.org/abs/2408.14906)