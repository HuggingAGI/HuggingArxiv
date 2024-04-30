# 利用大型语言模型，我们深入探讨了德语 Telegram 上的阴谋论，这一研究超越了传统的关键词搜索偏见，为我们提供了新的视角。

发布时间：2024年04月27日

`分类：LLM应用

这篇论文主要探讨了在德语 Telegram 消息中识别阴谋论的新方法，使用了基于 BERT 模型的监督微调和使用 Llama2、GPT-3.5 和 GPT-4 的提示法。这些方法都涉及到了大型语言模型（LLM）的应用，因此将其归类为 LLM应用。` `社交媒体监控`

> Detection of Conspiracy Theories Beyond Keyword Bias in German-Language Telegram Using Large Language Models

# 摘要

> 网络中阴谋论的自动识别通常依赖监督学习方法。但制备相关训练集既需专业知识，又耗时劳心，特别是面对那些常含有害内容的数据。此外，目前的数据集多以英文为主，且多基于关键词，这可能导致模型在词符层面产生偏差。本研究旨在探索在德语 Telegram 消息中识别阴谋论的新方法。我们对比了基于 BERT 模型的监督微调与使用 Llama2、GPT-3.5 和 GPT-4 的提示法，后者几乎或完全不需要额外的训练数据。研究使用了 COVID-19 大流行期间收集的约 4,000 条消息组成的数据集，且未采用关键词过滤。研究发现，两种方法均显示出潜力：在监督微调方面，我们的模型在正类上达到了约 0.8 的 F1 分数，与近期基于英文关键词语料库训练的模型相媲美。我们还证明了模型能够适应领域内的时间变化，F1 分数约为 0.7。在提示法中，GPT-4 表现最佳，在零样本情况下正类 F1 分数达到约 0.8，并配备了自定义的阴谋论定义。

> The automated detection of conspiracy theories online typically relies on supervised learning. However, creating respective training data requires expertise, time and mental resilience, given the often harmful content. Moreover, available datasets are predominantly in English and often keyword-based, introducing a token-level bias into the models. Our work addresses the task of detecting conspiracy theories in German Telegram messages. We compare the performance of supervised fine-tuning approaches using BERT-like models with prompt-based approaches using Llama2, GPT-3.5, and GPT-4 which require little or no additional training data. We use a dataset of $\sim\!\! 4,000$ messages collected during the COVID-19 pandemic, without the use of keyword filters.
  Our findings demonstrate that both approaches can be leveraged effectively: For supervised fine-tuning, we report an F1 score of $\sim\!\! 0.8$ for the positive class, making our model comparable to recent models trained on keyword-focused English corpora. We demonstrate our model's adaptability to intra-domain temporal shifts, achieving F1 scores of $\sim\!\! 0.7$. Among prompting variants, the best model is GPT-4, achieving an F1 score of $\sim\!\! 0.8$ for the positive class in a zero-shot setting and equipped with a custom conspiracy theory definition.

[Arxiv](https://arxiv.org/abs/2404.17985)