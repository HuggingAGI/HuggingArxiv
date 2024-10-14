# 银行交易流程中的多模态自注意力机制

发布时间：2024年10月10日

`其他` `银行业` `金融科技`

> Self-Attention Mechanism in Multimodal Context for Banking Transaction Flow

# 摘要

> 银行业务流程 (BTF) 涉及多种银行业务活动，如营销、信用风险和欺诈检测，是一种包含日期、数值和文字的多模态数据。我们在此提出将自注意力机制应用于 BTF 处理。通过自监督方式，我们训练了两个模型：基于 RNN 和 Transformer。为处理 BTF，我们设计了特定标记化方法。在交易分类和信用风险评估两项任务中，微调后的预训练模型表现均超越了现有最先进方法。

> Banking Transaction Flow (BTF) is a sequential data found in a number of banking activities such as marketing, credit risk or banking fraud. It is a multimodal data composed of three modalities: a date, a numerical value and a wording. We propose in this work an application of self-attention mechanism to the processing of BTFs. We trained two general models on a large amount of BTFs in a self-supervised way: one RNN-based model and one Transformer-based model. We proposed a specific tokenization in order to be able to process BTFs. The performance of these two models was evaluated on two banking downstream tasks: a transaction categorization task and a credit risk task. The results show that fine-tuning these two pre-trained models allowed to perform better than the state-of-the-art approaches for both tasks.

[Arxiv](https://arxiv.org/abs/2410.08243)