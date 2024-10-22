# 探索通过主动遗忘进行预训练，以提升解码器语言模型的跨语言迁移能力。

发布时间：2024年10月21日

`LLM理论` `跨语言学习`

> Exploring Pretraining via Active Forgetting for Improving Cross Lingual Transfer for Decoder Language Models

# 摘要

> LLM 在 NLP 任务中表现出色，但在非英语语言中的效果有限。以往研究表明，BERT 和 XLM-RoBERTa 等仅编码器模型能有效实现从英语到其他语言的能力转移。我们提出了一种利用主动遗忘的预训练策略，使仅解码器的 LLM 也能实现跨语言转移。实验证明，这种预训练的 LLM 在新语言适应中表现优异，能够学习更优的多语言表示，从而提升下游任务的性能。

> Large Language Models (LLMs) demonstrate exceptional capabilities in a multitude of NLP tasks. However, the efficacy of such models to languages other than English is often limited. Prior works have shown that encoder-only models such as BERT or XLM-RoBERTa show impressive cross lingual transfer of their capabilities from English to other languages. In this work, we propose a pretraining strategy that uses active forgetting to achieve similar cross lingual transfer in decoder-only LLMs. We show that LLMs pretrained with active forgetting are highly effective when adapting to new and unseen languages. Through extensive experimentation, we find that LLMs pretrained with active forgetting are able to learn better multilingual representations which translates to better performance in many downstream tasks.

[Arxiv](https://arxiv.org/abs/2410.16168)