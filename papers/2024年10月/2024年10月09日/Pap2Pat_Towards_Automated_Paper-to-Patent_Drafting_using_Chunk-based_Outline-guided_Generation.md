# Pap2Pat：基于块的大纲引导生成，实现论文到专利草稿的自动化。

发布时间：2024年10月09日

`LLM应用`

> Pap2Pat: Towards Automated Paper-to-Patent Drafting using Chunk-based Outline-guided Generation

# 摘要

> 专利领域在 NLP 研究中备受瞩目，不仅简化了专利流程，还为 LLM 提供了挑战性基准。然而，专利文件中占比超90%的描述部分生成尚未被研究。为此，我们引入了大纲引导的论文到专利生成任务，其中学术论文提供技术规格，大纲定义专利结构。我们创建了 PAP2PAT 基准，包含1.8k专利-论文对及其大纲，反映典型研究实践。实验显示，当前 LLM 能有效利用论文信息，但受专利语言重复性影响，处理重复内容时仍有困难。我们公开了数据和代码。

> The patent domain is gaining attention in natural language processing research, offering practical applications in streamlining the patenting process and providing challenging benchmarks for large language models (LLMs). However, the generation of the description sections of patents, which constitute more than 90% of the patent document, has not been studied to date. We address this gap by introducing the task of outline-guided paper-to-patent generation, where an academic paper provides the technical specification of the invention and an outline conveys the desired patent structure. We present PAP2PAT, a new challenging benchmark of 1.8k patent-paper pairs with document outlines, collected using heuristics that reflect typical research lab practices. Our experiments with current open-weight LLMs and outline-guided chunk-based generation show that they can effectively use information from the paper but struggle with repetitions, likely due to the inherent repetitiveness of patent language. We release our data and code.

[Arxiv](https://arxiv.org/abs/2410.07009)