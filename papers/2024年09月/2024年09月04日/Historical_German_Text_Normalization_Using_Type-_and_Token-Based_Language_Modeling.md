# 利用类型与标记为基础的语言模型进行历史德语文本规范化

发布时间：2024年09月04日

`LLM应用` `历史研究`

> Historical German Text Normalization Using Type- and Token-Based Language Modeling

# 摘要

> 历史拼写的变化给历史数字化文本的全文搜索和自然语言处理带来了难题。为了弥合历史正字法与现代拼写之间的鸿沟，通常需要对历史文献进行自动正字法规范化。本报告提出了一种针对1700至1900年间德语文学文本的规范化系统，该系统基于平行语料库训练而成。该系统采用基于Transformer语言模型的机器学习方法，结合编码器-解码器模型对单个词类进行规范化，并利用预训练的因果语言模型在上下文中进行微调。经过广泛评估，该系统展现了顶尖的准确性，与一个更大规模的端到端句子级规范化系统不相上下，后者对预训练的Transformer大型语言模型进行了微调。尽管如此，由于模型泛化能力的局限和高质量平行数据的稀缺，历史文本的规范化依然充满挑战。

> Historic variations of spelling poses a challenge for full-text search or natural language processing on historical digitized texts. To minimize the gap between the historic orthography and contemporary spelling, usually an automatic orthographic normalization of the historical source material is pursued. This report proposes a normalization system for German literary texts from c. 1700-1900, trained on a parallel corpus. The proposed system makes use of a machine learning approach using Transformer language models, combining an encoder-decoder model to normalize individual word types, and a pre-trained causal language model to adjust these normalizations within their context. An extensive evaluation shows that the proposed system provides state-of-the-art accuracy, comparable with a much larger fully end-to-end sentence-based normalization system, fine-tuning a pre-trained Transformer large language model. However, the normalization of historical text remains a challenge due to difficulties for models to generalize, and the lack of extensive high-quality parallel data.

[Arxiv](https://arxiv.org/abs/2409.02841)