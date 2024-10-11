# MKGL：精通三字语言

发布时间：2024年10月09日

`LLM应用` `知识图谱`

> MKGL: Mastery of a Three-Word Language

# 摘要

> 大型语言模型 (LLM) 在自然语言处理 (NLP) 任务中表现出色，但在知识图谱 (KGs) 的应用上仍待探索。本文通过引入 KG 语言 (KGL)，探讨了 LLM 与 KGs 的结合。KGL 句子由实体名词、关系动词和另一实体名词组成。尽管 LLM 对 KGL 词汇不熟悉，我们通过定制词典和示例句子帮助其学习，并利用实时 KG 上下文检索和 KGL 标记嵌入增强来提升理解。实验结果显示，LLM 在 KGL 中表现流畅，错误率显著低于传统 KG 嵌入方法。此外，增强的 LLM 还能从初始实体生成准确的三词句子和解释 KGs 中的新术语。

> Large language models (LLMs) have significantly advanced performance across a spectrum of natural language processing (NLP) tasks. Yet, their application to knowledge graphs (KGs), which describe facts in the form of triplets and allow minimal hallucinations, remains an underexplored frontier. In this paper, we investigate the integration of LLMs with KGs by introducing a specialized KG Language (KGL), where a sentence precisely consists of an entity noun, a relation verb, and ends with another entity noun. Despite KGL's unfamiliar vocabulary to the LLM, we facilitate its learning through a tailored dictionary and illustrative sentences, and enhance context understanding via real-time KG context retrieval and KGL token embedding augmentation. Our results reveal that LLMs can achieve fluency in KGL, drastically reducing errors compared to conventional KG embedding methods on KG completion. Furthermore, our enhanced LLM shows exceptional competence in generating accurate three-word sentences from an initial entity and interpreting new unseen terms out of KGs.

[Arxiv](https://arxiv.org/abs/2410.07526)