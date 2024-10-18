# 大型语言模型包容性生成的主动学习框架

发布时间：2024年10月17日

`LLM应用` `人工智能` `数据科学`

> An Active Learning Framework for Inclusive Generation by Large Language Models

# 摘要

> 确保 LLM 生成的文本能够代表多样化群体至关重要，尤其是在训练数据中缺乏代表性不足群体的关键概念时。我们提出了一种基于聚类的主动学习框架，结合知识蒸馏，首次实现了生成任务的有效主动学习。通过聚类和知识蒸馏，我们构建了更具代表性的模型，无需预知数据分布或大量人力。实践中的案例研究（如反叙事和风格迁移）验证了我们的方法，新构建的数据集性能提升了2%-10%。结果显示，模型在各子群体中表现更一致，词汇多样性增加，展现了其对数据偏斜的韧性。此外，我们的方法还提升了未参与学习循环的次级模型性能，凸显了其实际应用价值。

> Ensuring that Large Language Models (LLMs) generate text representative of diverse sub-populations is essential, particularly when key concepts related to under-represented groups are scarce in the training data. We address this challenge with a novel clustering-based active learning framework, enhanced with knowledge distillation. The proposed framework transforms the intermediate outputs of the learner model, enabling effective active learning for generative tasks for the first time. Integration of clustering and knowledge distillation yields more representative models without prior knowledge of underlying data distribution and overbearing human efforts. We validate our approach in practice through case studies in counter-narration and style transfer. We construct two new datasets in tandem with model training, showing a performance improvement of 2%-10% over baseline models. Our results also show more consistent performance across various data subgroups and increased lexical diversity, underscoring our model's resilience to skewness in available data. Further, our results show that the data acquired via our approach improves the performance of secondary models not involved in the learning loop, showcasing practical utility of the framework.

[Arxiv](https://arxiv.org/abs/2410.13641)