# 利用 LLM 生成的标签，学习预测产品评论的使用场景

发布时间：2024年10月16日

`LLM应用` `数据标注`

> Learning to Predict Usage Options of Product Reviews with LLM-Generated Labels

# 摘要

> 标注大型数据集颇具挑战，众包虽常见，但成本高且质量参差不齐，尤其在复杂任务中。我们提出利用 LLM 作为少样本学习者，通过训练独立模型，从客户评论中预测产品使用选项，以简化数据标注。同时，我们引入新评估指标 HAMS4，用于多参考集的字符串比较。相较直接使用 LLM 进行序列任务，自定义模型更灵活，能更好地平衡能效与隐私。通过对比传统方法，我们展示了 LLM 在成本节约上的显著优势。实验表明，GPT-4 生成的标签质量甚至可媲美领域专家，且我们已公开相关代码与标签，供大家参考。

> Annotating large datasets can be challenging. However, crowd-sourcing is often expensive and can lack quality, especially for non-trivial tasks. We propose a method of using LLMs as few-shot learners for annotating data in a complex natural language task where we learn a standalone model to predict usage options for products from customer reviews. We also propose a new evaluation metric for this scenario, HAMS4, that can be used to compare a set of strings with multiple reference sets. Learning a custom model offers individual control over energy efficiency and privacy measures compared to using the LLM directly for the sequence-to-sequence task. We compare this data annotation approach with other traditional methods and demonstrate how LLMs can enable considerable cost savings. We find that the quality of the resulting data exceeds the level attained by third-party vendor services and that GPT-4-generated labels even reach the level of domain experts. We make the code and generated labels publicly available.

[Arxiv](https://arxiv.org/abs/2410.12470)