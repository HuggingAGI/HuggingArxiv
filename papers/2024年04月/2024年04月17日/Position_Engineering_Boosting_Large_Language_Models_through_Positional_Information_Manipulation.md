# 位置工程：通过巧妙操纵位置信息，增强大型语言模型的性能

发布时间：2024年04月17日

`LLM应用` `人工智能`

> Position Engineering: Boosting Large Language Models through Positional Information Manipulation

# 摘要

> 大型语言模型的表现深受所提供提示的品质所左右。为此，研究者们设计了众多精心的提示工程策略，目的是通过调整提示文本来优化任务执行效果。本文提出了一种创新技术——位置工程，它以一种更为高效的方式引导大型语言模型。与传统的提示工程相比，后者需要大量工作来修改提供给LLM的文本，位置工程则仅仅是调整提示中的定位信息，而无需更改文本本身。我们在两个广泛应用的LLM场景——检索增强生成（RAG）和上下文学习（ICL）中对位置工程进行了评估。评估结果显示，位置工程在这两种场景下均显著提升了性能基线。因此，位置工程成为了一种充满希望的新策略，用于充分发挥大型语言模型的潜力。

> The performance of large language models (LLMs) is significantly influenced by the quality of the prompts provided. In response, researchers have developed enormous prompt engineering strategies aimed at modifying the prompt text to enhance task performance. In this paper, we introduce a novel technique termed position engineering, which offers a more efficient way to guide large language models. Unlike prompt engineering, which requires substantial effort to modify the text provided to LLMs, position engineering merely involves altering the positional information in the prompt without modifying the text itself. We have evaluated position engineering in two widely-used LLM scenarios: retrieval-augmented generation (RAG) and in-context learning (ICL). Our findings show that position engineering substantially improves upon the baseline in both cases. Position engineering thus represents a promising new strategy for exploiting the capabilities of large language models.

[Arxiv](https://arxiv.org/abs/2404.11216)