# 在数据稀缺的情况下，借助大型语言模型和检索增强生成技术，提升紧凑型模型的性能。

发布时间：2024年10月01日

`RAG` `语言学`

> Boosting the Capabilities of Compact Models in Low-Data Contexts with Large Language Models and Retrieval-Augmented Generation

# 摘要

> 当前语言建模技术对数据和计算的高需求，给低资源语言的处理带来了难题。声明性语言学知识通过提供特定语言规则，有望部分缓解这一数据短缺问题。本文提出了一种由大型语言模型（LLM）支持的检索增强生成（RAG）框架，用于改进小模型在形态学注释任务中的表现。我们利用语言信息弥补数据和参数的不足，同时引入LLM解析的描述语法。实验表明，结合语法输入、LLM的解析能力及小模型的可训练性，可大幅提升性能与效率。我们发现，RAG支持的紧凑模型在数据稀缺环境下表现卓越，刷新了该任务及目标语言的记录。此外，我们的方法为语言学家提供了更可靠的形态学注释工具，每个输出都附有详尽解释和置信度评分。

> The data and compute requirements of current language modeling technology pose challenges for the processing and analysis of low-resource languages. Declarative linguistic knowledge has the potential to partially bridge this data scarcity gap by providing models with useful inductive bias in the form of language-specific rules. In this paper, we propose a retrieval augmented generation (RAG) framework backed by a large language model (LLM) to correct the output of a smaller model for the linguistic task of morphological glossing. We leverage linguistic information to make up for the lack of data and trainable parameters, while allowing for inputs from written descriptive grammars interpreted and distilled through an LLM.
  The results demonstrate that significant leaps in performance and efficiency are possible with the right combination of: a) linguistic inputs in the form of grammars, b) the interpretive power of LLMs, and c) the trainability of smaller token classification networks. We show that a compact, RAG-supported model is highly effective in data-scarce settings, achieving a new state-of-the-art for this task and our target languages. Our work also offers documentary linguists a more reliable and more usable tool for morphological glossing by providing well-reasoned explanations and confidence scores for each output.

[Arxiv](https://arxiv.org/abs/2410.00387)