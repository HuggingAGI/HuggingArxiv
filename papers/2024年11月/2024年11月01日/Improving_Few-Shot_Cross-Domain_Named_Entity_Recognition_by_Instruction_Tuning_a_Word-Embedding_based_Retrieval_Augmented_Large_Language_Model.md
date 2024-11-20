# 通过对基于词嵌入的检索增强大型语言模型进行指令调优，以改进少样本跨域命名实体识别

发布时间：2024年11月01日

`LLM应用` `企业服务`

> Improving Few-Shot Cross-Domain Named Entity Recognition by Instruction Tuning a Word-Embedding based Retrieval Augmented Large Language Model

# 摘要

> Few-Shot Cross-Domain NER 指的是借助数据丰富的源域知识，在数据稀缺的目标域进行实体识别的过程。此前的大多数最先进（SOTA）方法都采用预训练语言模型（PLMs）来实现跨域 NER。然而，这些模型往往具有领域特异性。要将其成功应用于新的目标域，要么得修改模型架构，要么得用新域的数据进行模型微调。这两种方式都会为每个目标域创建全新的 NER 模型，在实际场景中难以实现。近来，有一些工作尝试用 LLMs 来解决 Few-Shot Cross-Domain NER 问题。但其中多数要么在实际应用中成本过高，要么难以遵循 LLM 提示指令。本文中，我们提出了 IF-WRANER（用于命名实体识别的基于指令微调的词嵌入检索增强大型语言模型），这是一种经过微调的检索增强型 LLM。凭借 LLM 微调时使用的正则化技术，以及在检索提示示例时采用词级嵌入而非句子级嵌入，IF-WRANER 超越了此前的 SOTA Few-Shot Cross-Domain NER 方法。我们通过在开源的 CrossNER 数据集上对其性能进行基准测试，证明了模型的有效性，其 F1 分数比此前的 SOTA 模型提高了 2%以上。我们已将该模型部署到一家企业的多个客户关怀领域。通过 IF-WRANER 进行的精准实体预测，能够将客户引导至相关领域的自动化工作流程，使升级到人工代理的情况减少近 15%，为公司每年节省数百万美元。

> Few-Shot Cross-Domain NER is the process of leveraging knowledge from data-rich source domains to perform entity recognition on data scarce target domains. Most previous state-of-the-art (SOTA) approaches use pre-trained language models (PLMs) for cross-domain NER. However, these models are often domain specific. To successfully use these models for new target domains, we need to modify either the model architecture or perform model finetuning using data from the new domains. Both of these result in the creation of entirely new NER models for each target domain which is infeasible for practical scenarios. Recently,several works have attempted to use LLMs to solve Few-Shot Cross-Domain NER. However, most of these are either too expensive for practical purposes or struggle to follow LLM prompt instructions. In this paper, we propose IF-WRANER (Instruction Finetuned Word-embedding based Retrieval Augmented large language model for Named Entity Recognition), a retrieval augmented LLM, finetuned for the NER task. By virtue of the regularization techniques used during LLM finetuning and the adoption of word-level embedding over sentence-level embedding during the retrieval of in-prompt examples, IF-WRANER is able to outperform previous SOTA Few-Shot Cross-Domain NER approaches. We have demonstrated the effectiveness of our model by benchmarking its performance on the open source CrossNER dataset, on which it shows more than 2% F1 score improvement over the previous SOTA model. We have deployed the model for multiple customer care domains of an enterprise. Accurate entity prediction through IF-WRANER helps direct customers to automated workflows for the domains, thereby reducing escalations to human agents by almost 15% and leading to millions of dollars in yearly savings for the company.

[Arxiv](https://arxiv.org/abs/2411.00451)