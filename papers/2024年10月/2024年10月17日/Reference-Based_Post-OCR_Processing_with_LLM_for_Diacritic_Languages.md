# 基于参考的 OCR 后处理与 LLM 应用于变音符号语言

发布时间：2024年10月17日

`LLM应用` `文化遗产`

> Reference-Based Post-OCR Processing with LLM for Diacritic Languages

# 摘要

> 从带有变音符号的旧文档中提取细粒度 OCR 文本依然困难重重，主要因为意外的伪影、时间引起的退化以及数据集的匮乏。尽管已有独立的拼写校正方法，但面对历史文档中繁多的 OCR 错误组合和现代与古典语料库的差异，其表现不尽如人意。我们提出了一种新方法，利用现有内容丰富的电子书作为参考，结合大型语言模型，来修正 OCR 生成的文本。此技术为变音符号语言生成了高精度的伪页对页标签，有效应对了历史条件下小笔画带来的挑战。我们的流程不仅能消除旧文档中的各类噪声，还能解决字符、单词缺失及序列混乱等问题。通过后处理，我们生成了一个大型古典越南语书籍 OCR 数据集，平均评分高达 8.72（满分 10 分），超越了最先进的基于变压器的越南语拼写校正模型（7.03 分）。此外，我们还训练了一个基线 OCR 模型，与知名引擎相比，其表现更为出色。最终，我们将公开发布这一数据集，助力未来研究。

> Extracting fine-grained OCR text from aged documents in diacritic languages remains challenging due to unexpected artifacts, time-induced degradation, and lack of datasets. While standalone spell correction approaches have been proposed, they show limited performance for historical documents due to numerous possible OCR error combinations and differences between modern and classical corpus distributions. We propose a method utilizing available content-focused ebooks as a reference base to correct imperfect OCR-generated text, supported by large language models. This technique generates high-precision pseudo-page-to-page labels for diacritic languages, where small strokes pose significant challenges in historical conditions. The pipeline eliminates various types of noise from aged documents and addresses issues such as missing characters, words, and disordered sequences. Our post-processing method, which generated a large OCR dataset of classical Vietnamese books, achieved a mean grading score of 8.72 on a 10-point scale. This outperformed the state-of-the-art transformer-based Vietnamese spell correction model, which scored 7.03 when evaluated on a sampled subset of the dataset. We also trained a baseline OCR model to assess and compare it with well-known engines. Experimental results demonstrate the strength of our baseline model compared to widely used open-source solutions. The resulting dataset will be released publicly to support future studies.

[Arxiv](https://arxiv.org/abs/2410.13305)