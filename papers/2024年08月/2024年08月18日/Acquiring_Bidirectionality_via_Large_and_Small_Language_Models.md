# 利用大型与小型语言模型实现双向能力

发布时间：2024年08月18日

`LLM应用` `人工智能`

> Acquiring Bidirectionality via Large and Small Language Models

# 摘要

> 尽管有更大的单向语言模型如Llama-2，但双向语言模型（如BERT）的token表示在分类任务中仍占主导地位。我们推测，单向模型的不足在于其缺乏双向性。因此，我们提出训练一个小的反向语言模型，并将其与现有模型的表示结合，以提升下游任务的表现。实验结果显示，在命名实体识别中，这一方法显著提升了基准性能，尤其在稀有领域和少样本学习场景中表现突出。

> Using token representation from bidirectional language models (LMs) such as BERT is still a widely used approach for token-classification tasks. Even though there exist much larger unidirectional LMs such as Llama-2, they are rarely used to replace the token representation of bidirectional LMs. In this work, we hypothesize that their lack of bidirectionality is keeping them behind. To that end, we propose to newly train a small backward LM and concatenate its representations to those of existing LM for downstream tasks. Through experiments in named entity recognition, we demonstrate that introducing backward model improves the benchmark performance more than 10 points. Furthermore, we show that the proposed method is especially effective for rare domains and in few-shot learning settings.

[Arxiv](https://arxiv.org/abs/2408.09640)