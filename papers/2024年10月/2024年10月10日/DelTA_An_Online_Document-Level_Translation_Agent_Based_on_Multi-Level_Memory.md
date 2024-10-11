# DelTA：一款基于多级记忆的在线文档翻译助手

发布时间：2024年10月10日

`Agent` `机器翻译` `文档处理`

> DelTA: An Online Document-Level Translation Agent Based on Multi-Level Memory

# 摘要

> 大型语言模型（LLM）在机器翻译（MT）中取得了显著进步，但处理整个文档时仍面临翻译一致性和准确性的挑战。为此，我们推出了 DelTA，一个专为文档级翻译设计的智能代理。DelTA 采用多级记忆结构，涵盖专有名词、双语摘要、长期和短期记忆，并通过辅助 LLM 组件持续更新。实验显示，DelTA 在四个 LLM 和两个数据集上，翻译一致性和质量显著提升，一致性得分提高 4.58%，COMET 得分提高 3.16 分。其逐句翻译策略确保无遗漏，且内存效率更高。此外，DelTA 还提升了代词翻译准确性，其摘要功能在查询式摘要任务中也表现出色。代码和数据已公开，详见 https://github.com/YutongWang1216/DocMTAgent。

> Large language models (LLMs) have achieved reasonable quality improvements in machine translation (MT). However, most current research on MT-LLMs still faces significant challenges in maintaining translation consistency and accuracy when processing entire documents. In this paper, we introduce DelTA, a Document-levEL Translation Agent designed to overcome these limitations. DelTA features a multi-level memory structure that stores information across various granularities and spans, including Proper Noun Records, Bilingual Summary, Long-Term Memory, and Short-Term Memory, which are continuously retrieved and updated by auxiliary LLM-based components. Experimental results indicate that DelTA significantly outperforms strong baselines in terms of translation consistency and quality across four open/closed-source LLMs and two representative document translation datasets, achieving an increase in consistency scores by up to 4.58 percentage points and in COMET scores by up to 3.16 points on average. DelTA employs a sentence-by-sentence translation strategy, ensuring no sentence omissions and offering a memory-efficient solution compared to the mainstream method. Furthermore, DelTA improves pronoun translation accuracy, and the summary component of the agent also shows promise as a tool for query-based summarization tasks. We release our code and data at https://github.com/YutongWang1216/DocMTAgent.

[Arxiv](https://arxiv.org/abs/2410.08143)