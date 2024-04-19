# 在针对性情感分析领域，大型语言模型发挥着重要作用。

发布时间：2024年04月18日

`分类：LLM应用

这篇论文主要探讨了如何利用大型语言模型（LLMs）进行情感分析，特别是针对俄罗斯新闻报道中对特定实体的情感倾向。研究中使用了经过指令调整的LLMs，并以RuSentNE-2023数据集作为研究对象。论文还对Flan-T5模型进行了微调，并采用了“思维链”（CoT）三跳推理框架（THoR）。这些方法和实验都是LLM在情感分析领域的应用，因此将这篇论文归类为LLM应用。` `新闻分析` `情感分析`

> Large Language Models in Targeted Sentiment Analysis

# 摘要

> 本文探讨了利用解码器驱动的生成变换器来分析俄罗斯新闻报道中对特定实体的情感倾向。我们考察了经过指令调整的大型语言模型（LLMs）在情感分析方面的性能，并以RuSentNE-2023数据集作为研究对象。实验分为两组：首先，我们评估了LLMs在封闭和开放透明度下的零样本学习能力；其次，我们对Flan-T5模型进行了微调，采用了“思维链”（CoT）三跳推理框架（THoR）。研究发现，零样本方法的效果与经过微调的基线编码器变换器（BERT-base）相当。而采用THoR微调的Flan-T5模型在推理能力上至少提升了5%，与零样本实验相比。在RuSentNE-2023数据集上，经过微调的Flan-T5-xl模型实现了情感分析的最佳性能，超越了以往基于变换器的最先进分类器。我们的CoT应用框架已在GitHub上公开：https://github.com/nicolay-r/Reasoning-for-Sentiment-Analysis-Framework

> In this paper we investigate the use of decoder-based generative transformers for extracting sentiment towards the named entities in Russian news articles. We study sentiment analysis capabilities of instruction-tuned large language models (LLMs). We consider the dataset of RuSentNE-2023 in our study. The first group of experiments was aimed at the evaluation of zero-shot capabilities of LLMs with closed and open transparencies. The second covers the fine-tuning of Flan-T5 using the "chain-of-thought" (CoT) three-hop reasoning framework (THoR). We found that the results of the zero-shot approaches are similar to the results achieved by baseline fine-tuned encoder-based transformers (BERT-base). Reasoning capabilities of the fine-tuned Flan-T5 models with THoR achieve at least 5% increment with the base-size model compared to the results of the zero-shot experiment. The best results of sentiment analysis on RuSentNE-2023 were achieved by fine-tuned Flan-T5-xl, which surpassed the results of previous state-of-the-art transformer-based classifiers. Our CoT application framework is publicly available: https://github.com/nicolay-r/Reasoning-for-Sentiment-Analysis-Framework

[Arxiv](https://arxiv.org/abs/2404.12342)