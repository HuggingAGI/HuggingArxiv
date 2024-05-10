# 《捕捉未熟之鳞：自动识别大型语言模型中的欠训练标记》

发布时间：2024年05月08日

`LLM理论

这篇论文关注的是大型语言模型（LLM）中分词器与模型训练之间的脱节问题，特别是“故障令牌”的识别和检测。这些问题令牌的存在和影响揭示了模型训练和分词处理过程中的潜在缺陷，这属于对LLM内部机制的理论研究。因此，这篇论文更符合LLM理论分类，因为它探讨了语言模型构建和训练过程中的一个基础性问题，而不是直接应用于某个特定的Agent或RAG系统，也不是关于LLM的具体应用案例。` `模型安全性`

> Fishing for Magikarp: Automatically Detecting Under-trained Tokens in Large Language Models

# 摘要

> 语言模型中分词器与模型训练之间的脱节，使得某些输入如SolidGoldMagikarp令牌能够引发不希望的行为。尽管这些“故障令牌”在分词器词汇中存在，但在训练中却鲜有踪迹，且在多种模型中均有发现，但一直缺乏一致的识别方法。我们对大型语言模型（LLM）的分词器进行了深入分析，专注于检测未训练和训练不足的令牌。通过综合运用分词器分析、模型权重指标和提示技术，我们开发了自动检测这些问题令牌的有效方法。我们的研究揭示了这些令牌在不同模型中的普遍性，并为提升语言模型的效率和安全性提供了新的视角。

> The disconnect between tokenizer creation and model training in language models has been known to allow for certain inputs, such as the infamous SolidGoldMagikarp token, to induce unwanted behaviour. Although such `glitch tokens' that are present in the tokenizer vocabulary, but are nearly or fully absent in training, have been observed across a variety of different models, a consistent way of identifying them has been missing. We present a comprehensive analysis of Large Language Model (LLM) tokenizers, specifically targeting this issue of detecting untrained and under-trained tokens. Through a combination of tokenizer analysis, model weight-based indicators, and prompting techniques, we develop effective methods for automatically detecting these problematic tokens. Our findings demonstrate the prevalence of such tokens across various models and provide insights into improving the efficiency and safety of language models.

[Arxiv](https://arxiv.org/abs/2405.05417)