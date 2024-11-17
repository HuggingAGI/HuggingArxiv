# Audiobox TTA-RAG：借助检索增强生成来优化零样本和少样本的文本转音频

发布时间：2024年11月07日

`RAG` `模型生成`

> Audiobox TTA-RAG: Improving Zero-Shot and Few-Shot Text-To-Audio with Retrieval-Augmented Generation

# 摘要

> 当前领先的文本转音频（TTA）生成模型在零样本和少样本的设定下性能欠佳。要为训练集中未曾出现或不常见的音频事件生成高质量音频，往往困难重重。受大型语言模型（LLM）知识密集型任务中检索增强生成（RAG）成功的启发，我们为TTA流程增添了额外的条件上下文。我们提出了Audiobox TTA-RAG，这是基于条件流匹配音频生成模型Audiobox的一种新型检索增强TTA方法。与仅依据文本生成音频的普通Audiobox TTA方案不同，我们用检索到的音频样本增强了条件输入，这些样本提供了更多声学信息以生成目标音频。我们的检索方法不要求外部数据库有标注音频，具有更实用的应用场景。为评估我们提出的方法，我们在零样本和少样本设定下精心设计了测试集。我们的实验结果表明，所提模型能够有效利用检索到的音频样本，大幅提升零样本和少样本TTA性能，在多个评估指标上优势显著，同时具备为域内设定生成语义对齐音频的能力。此外，我们还探究了不同检索方法和数据源的效果。

> Current leading Text-To-Audio (TTA) generation models suffer from degraded performance on zero-shot and few-shot settings. It is often challenging to generate high-quality audio for audio events that are unseen or uncommon in the training set. Inspired by the success of Retrieval-Augmented Generation (RAG) in Large Language Model (LLM)-based knowledge-intensive tasks, we extend the TTA process with additional conditioning contexts. We propose Audiobox TTA-RAG, a novel retrieval-augmented TTA approach based on Audiobox, a conditional flow-matching audio generation model. Unlike the vanilla Audiobox TTA solution which generates audio conditioned on text, we augmented the conditioning input with retrieved audio samples that provide additional acoustic information to generate the target audio. Our retrieval method does not require the external database to have labeled audio, offering more practical use cases. To evaluate our proposed method, we curated test sets in zero-shot and few-shot settings. Our empirical results show that the proposed model can effectively leverage the retrieved audio samples and significantly improve zero-shot and few-shot TTA performance, with large margins on multiple evaluation metrics, while maintaining the ability to generate semantically aligned audio for the in-domain setting. In addition, we investigate the effect of different retrieval methods and data sources.

[Arxiv](https://arxiv.org/abs/2411.05141)