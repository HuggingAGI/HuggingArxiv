# CRAT：一个针对大型语言模型的、用于实现因果增强型反思和检索增强型翻译的多智能体框架

发布时间：2024年10月28日

`Agent` `机器翻译` `知识图谱`

> CRAT: A Multi-Agent Framework for Causality-Enhanced Reflective and Retrieval-Augmented Translation with Large Language Models

# 摘要

> 大型语言模型（LLMs）于机器翻译领域颇具潜力，然而在应对上下文相关的术语（像新的或特定领域的词汇）时，仍力有不逮，由此引发难以处理的不一致和错误。现有的解决办法往往依赖人工识别此类术语，但鉴于语言的复杂性和不断变化的特性，这并不可行。虽说检索增强生成（RAG）能提供一定助力，但其在翻译中的应用受限于信息过载导致的幻觉等问题。在本文中，我们提出了 CRAT 这一全新的多智能体翻译框架，借助 RAG 和因果增强的自我反思来应对上述挑战。此框架包含若干专门的智能体：未知术语识别智能体可探测上下文中的未知术语，知识图谱（KG）构建智能体能提取这些术语的相关内部知识，并从外部来源获取双语信息，因果增强判断智能体负责验证信息的准确性，翻译智能体将优化后的信息融入最终输出。这一自动化流程能让翻译过程中对关键术语的处理更精准、更一致。我们的成果显示，CRAT 大幅提升了翻译的准确度，尤其在处理上下文敏感术语和新兴词汇时表现出色。

> Large language models (LLMs) have shown great promise in machine translation, but they still struggle with contextually dependent terms, such as new or domain-specific words. This leads to inconsistencies and errors that are difficult to address. Existing solutions often depend on manual identification of such terms, which is impractical given the complexity and evolving nature of language. While Retrieval-Augmented Generation (RAG) could provide some assistance, its application to translation is limited by issues such as hallucinations from information overload. In this paper, we propose CRAT, a novel multi-agent translation framework that leverages RAG and causality-enhanced self-reflection to address these challenges. This framework consists of several specialized agents: the Unknown Terms Identification agent detects unknown terms within the context, the Knowledge Graph (KG) Constructor agent extracts relevant internal knowledge about these terms and retrieves bilingual information from external sources, the Causality-enhanced Judge agent validates the accuracy of the information, and the Translator agent incorporates the refined information into the final output. This automated process allows for more precise and consistent handling of key terms during translation. Our results show that CRAT significantly improves translation accuracy, particularly in handling context-sensitive terms and emerging vocabulary.

[Arxiv](https://arxiv.org/abs/2410.21067)