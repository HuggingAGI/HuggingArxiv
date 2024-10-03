# 大型语言模型中的零-shot 跨语言迁移：层交换策略

发布时间：2024年10月02日

`LLM应用` `人工智能`

> Layer Swapping for Zero-Shot Cross-Lingual Transfer in Large Language Models

# 摘要

> 模型合并（如模型汤）是将相同架构的不同模型组合而不需额外训练的技术。本研究提出一种模型合并方法，解决非英语语言中目标任务微调大型语言模型（LLM）的难题，这些语言通常缺乏特定任务数据。我们聚焦数学推理，通过整合语言与数学能力，实现无数学数据的跨语言迁移。从同一预训练模型出发，分别在英语数学指令和目标语言通用指令数据上微调“专家”模型。随后，直接用语言专家的层替换数学专家的变换器层，显著提升目标语言的数学表现。在数学基准 MGSM 上，合并模型在数据稀缺的四种主要语言中，表现优于单个专家和其他合并方法 10%。此层交换基于对微调期间关键参数变化的解释性分析，简单、经济且直观。这种成功重组 LLM 进行跨语言迁移的方法，为未来结合模型专业知识、构建模块化解决方案及跨语言迁移推理能力提供了新可能。

> Model merging, such as model souping, is the practice of combining different models with the same architecture together without further training. In this work, we present a model merging methodology that addresses the difficulty of fine-tuning Large Language Models (LLMs) for target tasks in non-English languages, where task-specific data is often unavailable. We focus on mathematical reasoning and without in-language math data, facilitate cross-lingual transfer by composing language and math capabilities. Starting from the same pretrained model, we fine-tune separate "experts" on math instruction data in English and on generic instruction data in the target language. We then replace the top and bottom transformer layers of the math expert directly with layers from the language expert, which consequently enhances math performance in the target language. The resulting merged models outperform the individual experts and other merging methods on the math benchmark, MGSM, by 10% across four major languages where math instruction data is scarce. In addition, this layer swapping is simple, inexpensive, and intuitive, as it is based on an interpretative analysis of the most important parameter changes during the fine-tuning of each expert. The ability to successfully re-compose LLMs for cross-lingual transfer in this manner opens up future possibilities to combine model expertise, create modular solutions, and transfer reasoning capabilities across languages all post hoc.

[Arxiv](https://arxiv.org/abs/2410.01335)