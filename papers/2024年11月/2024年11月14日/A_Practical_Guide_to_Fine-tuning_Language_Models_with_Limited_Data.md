# 一份有关利用有限数据对语言模型进行微调的实用指南

发布时间：2024年11月14日

`LLM应用` `迁移学习`

> A Practical Guide to Fine-tuning Language Models with Limited Data

# 摘要

> 尽管预训练的大型语言模型（LLMs）对数据量需求大，但它已成为自然语言处理（NLP）的实际标准。受近期针对有限数据训练LLMs（尤其是在低资源领域和语言方面）的研究热潮的推动，本文探讨了近期的迁移学习方法，以优化数据稀缺的下游任务中的模型性能。首先，我们阐述了初始和持续的预训练策略，以更好地利用在陌生领域和语言中的先验知识。接着，研究了在微调及少样本学习过程中如何充分利用有限的数据。最后，从任务特定的视角审视了适用于不同数据稀缺程度的模型和方法。我们旨在为从业者提供应对数据受限挑战的实用指南，同时指明未来研究的有前景的方向。

> Employing pre-trained Large Language Models (LLMs) has become the de facto standard in Natural Language Processing (NLP) despite their extensive data requirements. Motivated by the recent surge in research focused on training LLMs with limited data, particularly in low-resource domains and languages, this paper surveys recent transfer learning approaches to optimize model performance in downstream tasks where data is scarce. We first address initial and continued pre-training strategies to better leverage prior knowledge in unseen domains and languages. We then examine how to maximize the utility of limited data during fine-tuning and few-shot learning. The final section takes a task-specific perspective, reviewing models and methods suited for different levels of data scarcity. Our goal is to provide practitioners with practical guidelines for overcoming the challenges posed by constrained data while also highlighting promising directions for future research.

[Arxiv](https://arxiv.org/abs/2411.09539)