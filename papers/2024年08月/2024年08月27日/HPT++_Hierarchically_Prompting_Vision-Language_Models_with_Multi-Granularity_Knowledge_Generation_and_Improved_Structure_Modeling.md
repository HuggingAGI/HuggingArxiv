# HPT++：结合多粒度知识生成与优化结构建模，提升视觉-语言模型的分层提示效果

发布时间：2024年08月27日

`LLM应用` `计算机视觉`

> HPT++: Hierarchically Prompting Vision-Language Models with Multi-Granularity Knowledge Generation and Improved Structure Modeling

# 摘要

> 提示学习已成为将视觉-语言模型（如CLIP）应用于下游任务的主流策略。随着大型语言模型（LLMs）的兴起，研究者们开始探索利用类别描述来提升提示效果。然而，传统描述往往缺乏必要的结构化信息，难以表达关键元素（如实体和属性）之间的关联。为此，我们提出利用LLMs构建描述图，以强化结构化知识。基于此，我们创新性地提出了分层提示调整（HPT）方法，该方法能够同时整合结构化与传统语言知识。具体来说，我们设计了一个关系引导的注意力模块，用于捕捉实体和属性间的关联，并结合高级和全局级别的提示，以增强模型对复杂关系的处理能力。此外，通过优化多粒度知识生成和关系驱动的注意力机制，以及对分层文本编码器的持续约束，我们进一步提升了HPT的性能，推出了HPT++。实验结果显示，我们的方法在多种评估场景下均表现优异，显著超越了现有最先进的方法。

> Prompt learning has become a prevalent strategy for adapting vision-language foundation models (VLMs) such as CLIP to downstream tasks. With the emergence of large language models (LLMs), recent studies have explored the potential of using category-related descriptions to enhance prompt effectiveness. However, conventional descriptions lack explicit structured information necessary to represent the interconnections among key elements like entities or attributes with relation to a particular category. Since existing prompt tuning methods give little consideration to managing structured knowledge, this paper advocates leveraging LLMs to construct a graph for each description to prioritize such structured knowledge. Consequently, we propose a novel approach called Hierarchical Prompt Tuning (HPT), enabling simultaneous modeling of both structured and conventional linguistic knowledge. Specifically, we introduce a relationship-guided attention module to capture pair-wise associations among entities and attributes for low-level prompt learning. In addition, by incorporating high-level and global-level prompts modeling overall semantics, the proposed hierarchical structure forges cross-level interlinks and empowers the model to handle more complex and long-term relationships. Finally, by enhancing multi-granularity knowledge generation, redesigning the relationship-driven attention re-weighting module, and incorporating consistent constraints on the hierarchical text encoder, we propose HPT++, which further improves the performance of HPT. Our experiments are conducted across a wide range of evaluation settings, including base-to-new generalization, cross-dataset evaluation, and domain generalization. Extensive results and ablation studies demonstrate the effectiveness of our methods, which consistently outperform existing SOTA methods.

[Arxiv](https://arxiv.org/abs/2408.14812)