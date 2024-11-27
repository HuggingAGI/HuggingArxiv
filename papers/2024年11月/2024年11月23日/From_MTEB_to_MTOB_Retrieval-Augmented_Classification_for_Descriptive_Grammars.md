# 从 MTEB 迈向 MTOB：描述性语法的检索增强分类

发布时间：2024年11月23日

`RAG` `语言模型` `机器翻译`

> From MTEB to MTOB: Retrieval-Augmented Classification for Descriptive Grammars

# 摘要

> 近期语言建模领域的进步已展现出零样本能力的显著提升，涵盖了上下文学习、指令遵循以及针对极度资源稀缺语言的机器翻译（Tanzer 等，2024）。然而，众多书面资源匮乏的语言主要依靠语法和词汇的正式阐述。
    本文引入了一组基准，用以评估模型从语言语法的复杂描述里提取和分类信息的水平。我们给出了一种基于检索增强生成（RAG）的办法，借助这些描述来处理诸如机器翻译之类的下游任务。我们的基准包含了 142 个语系中 248 种语言的语言描述，重点聚焦于来自 WALS 和 Grambank 的类型特征。
    这组基准首次对语言模型在上下文中准确解读和提取语言特征的能力进行了全面评估，为将 NLP 拓展至低资源语言提供了重要资源。代码和数据在 url{https://github.com/al-the-eigenvalue/RAG-on-grammars} 可公开获取。

> Recent advances in language modeling have demonstrated significant improvements in zero-shot capabilities, including in-context learning, instruction following, and machine translation for extremely under-resourced languages (Tanzer et al., 2024). However, many languages with limited written resources rely primarily on formal descriptions of grammar and vocabulary.
  In this paper, we introduce a set of benchmarks to evaluate how well models can extract and classify information from the complex descriptions found in linguistic grammars. We present a Retrieval-Augmented Generation (RAG)-based approach that leverages these descriptions for downstream tasks such as machine translation. Our benchmarks encompass linguistic descriptions for 248 languages across 142 language families, focusing on typological features from WALS and Grambank.
  This set of benchmarks offers the first comprehensive evaluation of language models' in-context ability to accurately interpret and extract linguistic features, providing a critical resource for scaling NLP to low-resource languages. The code and data are publicly available at \url{https://github.com/al-the-eigenvalue/RAG-on-grammars}.

[Arxiv](https://arxiv.org/abs/2411.15577)