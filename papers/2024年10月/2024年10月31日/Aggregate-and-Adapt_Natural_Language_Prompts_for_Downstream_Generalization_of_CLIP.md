# 通过聚合和适应自然语言提示来实现 CLIP 的下游泛化

发布时间：2024年10月31日

`LLM应用` `视觉语言` `提示学习`

> Aggregate-and-Adapt Natural Language Prompts for Downstream Generalization of CLIP

# 摘要

> 像 CLIP 这样的大型预训练视觉语言模型展现出了良好的泛化能力，然而在一些特定领域（如卫星图像）或细粒度分类（如汽车型号）中可能会遭遇困境，因为在预训练时这些领域的视觉概念未曾出现或代表性不足。提示学习提供了一种参数高效的微调框架，即便注释数据有限，也能让 CLIP 适应下游任务。在本文中，我们从自然语言提示（不管是人工生成还是 LLM 生成）中提炼文本知识来优化提示学习，为那些代表性欠佳的概念赋予丰富的先验信息。我们先是通过一个学习型的提示聚合器获取与每个输入图像相匹配的提示“摘要”。接着共同训练一个提示生成器，使其生成的提示嵌入既接近聚合摘要，又能同时将任务损失最小化。我们把这种提示嵌入称作聚合与适应提示嵌入（AAPE）。AAPE 能够推广到不同的下游数据分布和任务中，在视觉语言理解任务（如少样本分类、VQA）和生成任务（图像字幕）里都有出色表现。同时，AAPE 尤其有助于处理非规范和 OOD 示例。此外，AAPE 学习消除了基线所要求的基于 LLM 的推理成本，并且随着数据和 LLM 模型规模的增大，扩展性更优。

> Large pretrained vision-language models like CLIP have shown promising generalization capability, but may struggle in specialized domains (e.g., satellite imagery) or fine-grained classification (e.g., car models) where the visual concepts are unseen or under-represented during pretraining. Prompt learning offers a parameter-efficient finetuning framework that can adapt CLIP to downstream tasks even when limited annotation data are available. In this paper, we improve prompt learning by distilling the textual knowledge from natural language prompts (either human- or LLM-generated) to provide rich priors for those under-represented concepts. We first obtain a prompt ``summary'' aligned to each input image via a learned prompt aggregator. Then we jointly train a prompt generator, optimized to produce a prompt embedding that stays close to the aggregated summary while minimizing task loss at the same time. We dub such prompt embedding as Aggregate-and-Adapted Prompt Embedding (AAPE). AAPE is shown to be able to generalize to different downstream data distributions and tasks, including vision-language understanding tasks (e.g., few-shot classification, VQA) and generation tasks (image captioning) where AAPE achieves competitive performance. We also show AAPE is particularly helpful to handle non-canonical and OOD examples. Furthermore, AAPE learning eliminates LLM-based inference cost as required by baselines, and scales better with data and LLM model size.

[Arxiv](https://arxiv.org/abs/2410.23698)