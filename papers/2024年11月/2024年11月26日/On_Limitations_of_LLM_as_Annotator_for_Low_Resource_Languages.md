# 论大型语言模型作为低资源语言标注工具的局限

发布时间：2024年11月26日

`LLM应用` `低资源语言`

> On Limitations of LLM as Annotator for Low Resource Languages

# 摘要

> 低资源语言因缺乏充足的语言数据、资源及工具（像用于监督学习、标注和分类等任务的），面临着严峻挑战。这种匮乏阻碍了精准模型和数据集的开发，致使像情感分析或仇恨言论检测这类关键的自然语言处理任务难以开展。为填补这一缺口，大型语言模型（LLMs）为潜在标注者带来了契机，能够为这些资源匮乏的语言生成数据集和资源。在本文中，我们聚焦于马拉地语这一低资源语言，评估了闭源和开源的大型语言模型作为标注者的表现。我们在包括情感分析、新闻分类和仇恨言论检测等分类任务上，对 GPT-4o、Gemini 1.0 Pro、Gemma 2（2B 和 9B）以及 Llama 3.1（8B）等模型进行了评估。我们的发现显示，尽管大型语言模型在英语等高资源语言的标注任务中表现卓越，但用于马拉地语时却力有不逮。甚至像 Gemini 和 GPT 这类先进的闭源模型，与基于 BERT 的基线相比也表现欠佳，凸显了大型语言模型作为低资源语言标注者的局限性。

> Low-resource languages face significant challenges due to the lack of sufficient linguistic data, resources, and tools for tasks such as supervised learning, annotation, and classification. This shortage hinders the development of accurate models and datasets, making it difficult to perform critical NLP tasks like sentiment analysis or hate speech detection. To bridge this gap, Large Language Models (LLMs) present an opportunity for potential annotators, capable of generating datasets and resources for these underrepresented languages. In this paper, we focus on Marathi, a low-resource language, and evaluate the performance of both closed-source and open-source LLMs as annotators. We assess models such as GPT-4o and Gemini 1.0 Pro, Gemma 2 (2B and 9B), and Llama 3.1 (8B) on classification tasks including sentiment analysis, news classification, and hate speech detection. Our findings reveal that while LLMs excel in annotation tasks for high-resource languages like English, they still fall short when applied to Marathi. Even advanced closed models like Gemini and GPT underperform in comparison to BERT-based baselines, highlighting the limitations of LLMs as annotators for low-resource languages.

[Arxiv](https://arxiv.org/abs/2411.17637)