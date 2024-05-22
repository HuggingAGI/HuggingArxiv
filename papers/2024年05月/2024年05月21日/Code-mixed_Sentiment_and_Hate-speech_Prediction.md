# 混合编码情感与仇恨言论识别

发布时间：2024年05月21日

`LLM应用

这篇论文主要探讨了大型语言模型（LLM）在代码混合环境下的应用表现，特别是在英语-印地语和英语-斯洛文尼亚语的代码混合文本处理中的性能。通过情感分析和攻击性语言检测等任务的评估，研究了不同类型的模型（单语、双语、少语及多语模型）在处理代码混合文本时的效果。因此，这篇论文更偏向于LLM在特定应用场景下的实际表现和优化，属于LLM应用分类。` `社交媒体`

> Code-mixed Sentiment and Hate-speech Prediction

# 摘要

> 代码混合话语将多种语言融合于单一文本，常见于多官方语言国家的非正式交流，亦广泛见于其他国家，与英语或邻近语言交织使用。随着大型语言模型在自然语言处理领域的主导地位日益显著，我们探究了它们在代码混合环境下的表现。首先，我们为英语-印地语和英语-斯洛文尼亚语定制了四个双语预训练掩码语言模型，专为非正式语言设计。接着，我们通过情感分析和社交媒体中的攻击性语言检测这两个常含代码混合文本的任务，评估了单语、双语、少语及多语模型的性能。结果表明，针对社交媒体文本微调的双语和多语模型表现最佳，紧随其后的是未专门化的多语和单语模型，而大型生成模型则表现不佳。在处理情感问题时，模型在代码混合数据上的表现略胜一筹。

> Code-mixed discourse combines multiple languages in a single text. It is commonly used in informal discourse in countries with several official languages, but also in many other countries in combination with English or neighboring languages. As recently large language models have dominated most natural language processing tasks, we investigated their performance in code-mixed settings for relevant tasks. We first created four new bilingual pre-trained masked language models for English-Hindi and English-Slovene languages, specifically aimed to support informal language. Then we performed an evaluation of monolingual, bilingual, few-lingual, and massively multilingual models on several languages, using two tasks that frequently contain code-mixed text, in particular, sentiment analysis and offensive language detection in social media texts. The results show that the most successful classifiers are fine-tuned bilingual models and multilingual models, specialized for social media texts, followed by non-specialized massively multilingual and monolingual models, while huge generative models are not competitive. For our affective problems, the models mostly perform slightly better on code-mixed data compared to non-code-mixed data.

[Arxiv](https://arxiv.org/abs/2405.12929)