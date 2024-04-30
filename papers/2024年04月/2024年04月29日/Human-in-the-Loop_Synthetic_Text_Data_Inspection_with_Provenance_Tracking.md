# 人工参与的合成文本数据审查，配备有追踪溯源功能

发布时间：2024年04月29日

`分类：LLM应用` `数据科学` `人工智能`

> Human-in-the-Loop Synthetic Text Data Inspection with Provenance Tracking

# 摘要

> 数据增强通过转换现有文本来扩充数据集，但可能导致文本质量下降，意义扭曲，甚至难以理解。为了高效筛选出标注错误的文本，我们设计了 INSPECTOR，一种结合了来源追踪和辅助标注的人工审核技术。INSPECTOR 使用户能够根据文本的转换来源或原始文本的语言特征，将相关文本进行归类。在辅助标注方面，INSPECTOR 计算数据质量指标，并允许用户将每条文本的标签与大型语言模型的预测相比较。用户研究发现，INSPECTOR 在情感分析和仇恨言论检测任务中，分别将正确标注的文本数量提升了三倍和四倍。参与者普遍认为，根据文本的共同转换特征进行归类最为有效，而按语言特征分组则效果不佳。与先前研究不同，我们的研究指出，没有单一技术可以完全取代人工审核的必要性，这证明了 INSPECTOR 的设计，它结合了数据来源分析和辅助标注，有效减轻了人工审核的工作量。

> Data augmentation techniques apply transformations to existing texts to generate additional data. The transformations may produce low-quality texts, where the meaning of the text is changed and the text may even be mangled beyond human comprehension. Analyzing the synthetically generated texts and their corresponding labels is slow and demanding. To winnow out texts with incorrect labels, we develop INSPECTOR, a human-in-the-loop data inspection technique. INSPECTOR combines the strengths of provenance tracking techniques with assistive labeling. INSPECTOR allows users to group related texts by their transformation provenance, i.e., the transformations applied to the original text, or feature provenance, the linguistic features of the original text. For assistive labeling, INSPECTOR computes metrics that approximate data quality, and allows users to compare the corresponding label of each text against the predictions of a large language model. In a user study, INSPECTOR increases the number of texts with correct labels identified by 3X on a sentiment analysis task and by 4X on a hate speech detection task. The participants found grouping the synthetically generated texts by their common transformation to be the most useful technique. Surprisingly, grouping texts by common linguistic features was perceived to be unhelpful. Contrary to prior work, our study finds that no single technique obviates the need for human inspection effort. This validates the design of INSPECTOR which combines both analysis of data provenance and assistive labeling to reduce human inspection effort.

[Arxiv](https://arxiv.org/abs/2404.18881)