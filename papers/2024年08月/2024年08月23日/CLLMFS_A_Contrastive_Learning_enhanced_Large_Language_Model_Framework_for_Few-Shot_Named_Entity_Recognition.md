# CLLMFS：一款结合对比学习技术，专为少样本命名实体识别设计的大型语言模型框架。

发布时间：2024年08月23日

`LLM应用` `机器学习`

> CLLMFS: A Contrastive Learning enhanced Large Language Model Framework for Few-Shot Named Entity Recognition

# 摘要

> Few-shot NER，即利用有限标注数据识别命名实体，在NLP领域日益重要。尽管现有方法通过丰富标签语义或度量学习技术取得了一定成效，但由于预训练模型知识匮乏，跨领域性能仍显不足。为此，我们提出CLLMFS框架，结合对比学习与LLM，显著提升了Few-Shot NER效果。CLLMFS还融合了LoRA与定制对比学习，优化了LLM的内部表示，从而强化了实体边界感知与识别准确性。实验表明，我们的方法在多个基准测试中，F1-score提升显著，从2.58%至97.74%。跨领域实验进一步证实了其强大的泛化能力。代码即将公开。

> Few-shot Named Entity Recognition (NER), the task of identifying named entities with only a limited amount of labeled data, has gained increasing significance in natural language processing. While existing methodologies have shown some effectiveness, such as enriching label semantics through various prompting modes or employing metric learning techniques, their performance exhibits limited robustness across diverse domains due to the lack of rich knowledge in their pre-trained models. To address this issue, we propose CLLMFS, a Contrastive Learning enhanced Large Language Model (LLM) Framework for Few-Shot Named Entity Recognition, achieving promising results with limited training data. Considering the impact of LLM's internal representations on downstream tasks, CLLMFS integrates Low-Rank Adaptation (LoRA) and contrastive learning mechanisms specifically tailored for few-shot NER. By enhancing the model's internal representations, CLLMFS effectively improves both entity boundary awareness ability and entity recognition accuracy. Our method has achieved state-of-the-art performance improvements on F1-score ranging from 2.58\% to 97.74\% over existing best-performing methods across several recognized benchmarks. Furthermore, through cross-domain NER experiments conducted on multiple datasets, we have further validated the robust generalization capability of our method. Our code will be released in the near future.

[Arxiv](https://arxiv.org/abs/2408.12834)