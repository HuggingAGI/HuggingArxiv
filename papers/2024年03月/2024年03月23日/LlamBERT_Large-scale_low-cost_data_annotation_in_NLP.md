# LlamBERT：自然语言处理领域的大规模低成本数据标注解决方案

发布时间：2024年03月23日

`LLM应用`

> LlamBERT: Large-scale low-cost data annotation in NLP

# 摘要

> 诸如 GPT-4 和 Llama 2 这样的大型语言模型在多样的自然语言处理任务上展现了卓越的能力。然而，它们的高效能也伴随着高昂的经济成本，这无疑是一个难题。我们介绍了 LlamBERT，这是一种创新的混合策略，它通过利用大型语言模型对大量未标记数据库的一小部分进行注释，并以此为基础对 BERT 和 RoBERTa 等变换器编码器进行精细调整。该方法在 IMDb 影评数据集和 UMLS 元词库两大迥异的数据集上进行了测试。测试结果显示，尽管 LlamBERT 在精确度上略有牺牲，但其性价比却显著提升。

> Large Language Models (LLMs), such as GPT-4 and Llama 2, show remarkable proficiency in a wide range of natural language processing (NLP) tasks. Despite their effectiveness, the high costs associated with their use pose a challenge. We present LlamBERT, a hybrid approach that leverages LLMs to annotate a small subset of large, unlabeled databases and uses the results for fine-tuning transformer encoders like BERT and RoBERTa. This strategy is evaluated on two diverse datasets: the IMDb review dataset and the UMLS Meta-Thesaurus. Our results indicate that the LlamBERT approach slightly compromises on accuracy while offering much greater cost-effectiveness.

![LlamBERT：自然语言处理领域的大规模低成本数据标注解决方案](../../../paper_images/2403.15938/x1.png)

![LlamBERT：自然语言处理领域的大规模低成本数据标注解决方案](../../../paper_images/2403.15938/x2.png)

[Arxiv](https://arxiv.org/abs/2403.15938)