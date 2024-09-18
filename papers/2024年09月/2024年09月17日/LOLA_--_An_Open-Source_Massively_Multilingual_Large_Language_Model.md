# LOLA，一款开源的大规模多语言大型语言模型，正引领着语言技术的新潮流。

发布时间：2024年09月17日

`LLM理论` `多语言技术`

> LOLA -- An Open-Source Massively Multilingual Large Language Model

# 摘要

> 本文介绍的 LOLA 是一个在 160 多种语言上训练的多语言大型语言模型，采用稀疏的专家混合 Transformer 架构。我们通过架构和实现选择，成功在保持效率的同时，充分利用了语言多样性，避免了多语言模型的常见问题。评估结果显示，LOLA 在自然语言生成和理解任务中表现优异。我们还展示了模型如何通过学习到的专家路由机制，利用隐含的语言进化模式，缓解多语言模型的挑战。此外，我们详细分析了训练过程、数据集，并全面探讨了模型的优势与局限。作为开源模型，LOLA 不仅提升了研究的可重复性，还为未来的多语言模型研究奠定了坚实基础。我们的研究成果推动了高效、高性能的多语言模型的发展。

> This paper presents LOLA, a massively multilingual large language model trained on more than 160 languages using a sparse Mixture-of-Experts Transformer architecture. Our architectural and implementation choices address the challenge of harnessing linguistic diversity while maintaining efficiency and avoiding the common pitfalls of multilinguality. Our analysis of the evaluation results shows competitive performance in natural language generation and understanding tasks. Additionally, we demonstrate how the learned expert-routing mechanism exploits implicit phylogenetic linguistic patterns to potentially alleviate the curse of multilinguality. We provide an in-depth look at the training process, an analysis of the datasets, and a balanced exploration of the model's strengths and limitations. As an open-source model, LOLA promotes reproducibility and serves as a robust foundation for future research. Our findings enable the development of compute-efficient multilingual models with strong, scalable performance across languages.

[Arxiv](https://arxiv.org/abs/2409.11272)