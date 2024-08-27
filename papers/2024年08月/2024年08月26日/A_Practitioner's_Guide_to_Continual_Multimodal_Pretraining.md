# 持续多模态预训练实践指南

发布时间：2024年08月26日

`LLM应用` `人工智能` `计算机视觉`

> A Practitioner's Guide to Continual Multimodal Pretraining

# 摘要

> 多模态基础模型在视觉与语言的交汇处发挥着重要作用，但即便经过大量数据预训练，它们也会随时间变得陈旧。为了确保模型持续更新，研究者们探索了两种持续预训练策略：一是对新数据进行不频繁的全面更新，二是进行频繁的样本级微调。然而，实际部署往往介于这两者之间，因为现实应用需要模型适应特定子领域、任务或概念，这些需求贯穿模型的整个生命周期。为此，我们通过一个研究平台，为持续预训练提供了新的视角，并给出了在复杂场景下有效更新模型的全面指南。我们创建了FoMo-in-Flux基准，这是一个考虑了实际计算限制和部署需求的多模态预训练框架，基于63个多样化的数据集构建。通过FoMo-in-Flux，我们从数据混合、方法选择、元学习策略到模型规模等多个维度，深入探讨了持续预训练的实际挑战。我们的研究成果为实际部署提供了宝贵的实践指南，相关基准和代码已公开在GitHub上。

> Multimodal foundation models serve numerous applications at the intersection of vision and language. Still, despite being pretrained on extensive data, they become outdated over time. To keep models updated, research into continual pretraining mainly explores scenarios with either (1) infrequent, indiscriminate updates on large-scale new data, or (2) frequent, sample-level updates. However, practical model deployment often operates in the gap between these two limit cases, as real-world applications often demand adaptation to specific subdomains, tasks or concepts -- spread over the entire, varying life cycle of a model. In this work, we complement current perspectives on continual pretraining through a research test bed as well as provide comprehensive guidance for effective continual model updates in such scenarios. We first introduce FoMo-in-Flux, a continual multimodal pretraining benchmark with realistic compute constraints and practical deployment requirements, constructed over 63 datasets with diverse visual and semantic coverage. Using FoMo-in-Flux, we explore the complex landscape of practical continual pretraining through multiple perspectives: (1) A data-centric investigation of data mixtures and stream orderings that emulate real-world deployment situations, (2) a method-centric investigation ranging from simple fine-tuning and traditional continual learning strategies to parameter-efficient updates and model merging, (3) meta learning rate schedules and mechanistic design choices, and (4) the influence of model and compute scaling. Together, our insights provide a practitioner's guide to continual multimodal pretraining for real-world deployment. Our benchmark and code is here: https://github.com/ExplainableML/fomo_in_flux.

[Arxiv](https://arxiv.org/abs/2408.14471)