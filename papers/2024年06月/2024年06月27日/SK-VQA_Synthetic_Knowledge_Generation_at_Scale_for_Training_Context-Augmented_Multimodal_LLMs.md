# SK-VQA：大规模合成知识生成，助力上下文增强型多模态LLM训练

发布时间：2024年06月27日

`RAG` `人工智能` `数据集`

> SK-VQA: Synthetic Knowledge Generation at Scale for Training Context-Augmented Multimodal LLMs

# 摘要

> 合成数据生成近期备受瞩目，因其在大规模视觉与语言模型训练中的实用价值。然而，其在多模态上下文增强生成系统训练中的应用尚待深入探索。现有视觉与语言模型（VLMs）并非专为上下文增强生成设计，故适应这些模型的资源对检索增强生成（RAG）场景至关重要。为此，我们创建了SK-VQA，一个包含超200万问题-答案对的大型合成多模态数据集，需外部知识解答。该数据集规模更大、多样性显著提升，问题数量超以往11倍，图像来源更广泛。实验表明，SK-VQA不仅可作为挑战性基准，还能高效适应现有生成多模态模型，助力上下文增强生成。

> Synthetic data generation has gained significant attention recently for its utility in training large vision and language models. However, the application of synthetic data to the training of multimodal context-augmented generation systems has been relatively unexplored. This gap in existing work is important because existing vision and language models (VLMs) are not trained specifically for context-augmented generation. Resources for adapting such models are therefore crucial for enabling their use in retrieval-augmented generation (RAG) settings, where a retriever is used to gather relevant information that is then subsequently provided to a generative model via context augmentation. To address this challenging problem, we generate SK-VQA: a large synthetic multimodal dataset containing over 2 million question-answer pairs which require external knowledge to determine the final answer. Our dataset is both larger and significantly more diverse than existing resources of its kind, possessing over 11x more unique questions and containing images from a greater variety of sources than previously-proposed datasets. Through extensive experiments, we demonstrate that our synthetic dataset can not only serve as a challenging benchmark, but is also highly effective for adapting existing generative multimodal models for context-augmented generation.

[Arxiv](https://arxiv.org/abs/2406.19593)