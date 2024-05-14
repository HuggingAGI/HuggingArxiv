# 优化瑞士BERT模型，精炼句与文嵌入之艺

发布时间：2024年05月13日

`LLM应用

这篇论文介绍了一个名为SentenceSwissBERT的模型，它是专门为瑞士四种国家语言优化的BERT编码器模型，用于句子或短文档嵌入的微调。该模型在瑞士特定环境下的文档检索和文本分类任务中表现出色，并且已经公开供研究者使用。这表明该论文关注的是大型语言模型（LLM）在特定应用场景下的实际应用，因此属于LLM应用分类。` `文档检索`

> Fine-tuning the SwissBERT Encoder Model for Embedding Sentences and Documents

# 摘要

> 我们提出了一种专为句子或短文档嵌入微调的瑞士BERT编码器模型，名为SentenceSwissBERT。该模型针对瑞士四种国家语言进行了优化，并在大量新闻文章上进行了预训练。通过对比学习，我们进一步微调了模型，使其在瑞士特定环境下的文档检索和文本分类任务中表现出色，超越了原始模型和基准。SentenceSwissBERT现已公开，供研究者使用。

> Encoder models trained for the embedding of sentences or short documents have proven useful for tasks such as semantic search and topic modeling. In this paper, we present a version of the SwissBERT encoder model that we specifically fine-tuned for this purpose. SwissBERT contains language adapters for the four national languages of Switzerland -- German, French, Italian, and Romansh -- and has been pre-trained on a large number of news articles in those languages. Using contrastive learning based on a subset of these articles, we trained a fine-tuned version, which we call SentenceSwissBERT. Multilingual experiments on document retrieval and text classification in a Switzerland-specific setting show that SentenceSwissBERT surpasses the accuracy of the original SwissBERT model and of a comparable baseline. The model is openly available for research use.

[Arxiv](https://arxiv.org/abs/2405.07513)