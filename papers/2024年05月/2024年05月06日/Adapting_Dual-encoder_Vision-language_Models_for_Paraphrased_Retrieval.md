# 适配双编码视觉-语言模型，优化释义检索性能。

发布时间：2024年05月06日

`LLM应用` `图像检索`

> Adapting Dual-encoder Vision-language Models for Paraphrased Retrieval

# 摘要

> 近期，诸如 CLIP 的双编码器视觉-语言模型在文本到图像检索任务上表现卓越。但我们观察到，这些模型面对释义查询时，往往会给出截然不同的检索结果，这可能降低系统的可预测性，引发用户不满。本研究聚焦于释义文本到图像的检索问题，即模型在接收到释义查询对时，应返回相似的检索结果。为此，我们首先构建了一个包含释义图像描述的数据集，以便对此任务进行量化评估。接着，我们推测现有双编码器模型之所以表现不佳，可能是因为它们的文本模块仅在图像-句子对上训练，未能充分捕捉释义查询间的语义相似性。为了解决这一问题，我们探索了多种基于大型文本语料库预训练的语言模型的双编码器训练策略。与 CLIP 和 OpenCLIP 等现有模型相比，采用我们最优策略训练的模型在释义查询的排名相似性上有显著提升，同时保持了相当的零样本分类和检索精度。

> In the recent years, the dual-encoder vision-language models (\eg CLIP) have achieved remarkable text-to-image retrieval performance. However, we discover that these models usually results in very different retrievals for a pair of paraphrased queries. Such behavior might render the retrieval system less predictable and lead to user frustration. In this work, we consider the task of paraphrased text-to-image retrieval where a model aims to return similar results given a pair of paraphrased queries. To start with, we collect a dataset of paraphrased image descriptions to facilitate quantitative evaluation for this task. We then hypothesize that the undesired behavior of existing dual-encoder model is due to their text towers which are trained on image-sentence pairs and lack the ability to capture the semantic similarity between paraphrased queries. To improve on this, we investigate multiple strategies for training a dual-encoder model starting from a language model pretrained on a large text corpus. Compared to public dual-encoder models such as CLIP and OpenCLIP, the model trained with our best adaptation strategy achieves a significantly higher ranking similarity for paraphrased queries while maintaining similar zero-shot classification and retrieval accuracy.

[Arxiv](https://arxiv.org/abs/2405.03190)