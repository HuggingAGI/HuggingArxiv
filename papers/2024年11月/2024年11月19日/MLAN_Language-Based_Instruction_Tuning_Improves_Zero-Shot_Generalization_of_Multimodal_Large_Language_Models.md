# mlan：基于语言的指令调优提升了多模态大型语言模型的零样本泛化性能

发布时间：2024年11月19日

`LLM应用` `多模态` `指令调优`

> MLAN: Language-Based Instruction Tuning Improves Zero-Shot Generalization of Multimodal Large Language Models

# 摘要

> 我们带来了一种全新的指令调优方案，旨在增强多模态大型语言模型的零样本任务泛化能力。和那些极度依赖视觉指令的现有指令调优机制不同，我们的办法聚焦于基于语言的指令调优，为多模态指令调优开辟了一条独特且训练效率更高的途径。我们在语言和视觉这两种模态的 9 个未曾见过的数据集上对所提方法的性能进行了评估。结果显示，我们仅依靠语言的指令调优能够大幅提升基于 Llama 2 和 Vicuna 的两个预训练多模态模型在这些未见过的数据集上的表现。有趣的是，遵循语言指令的能力还能帮助模型在未经明确训练的情况下遵循视觉指令。相较于主要基于视觉指令的先进多模态指令调优方法，我们基于语言的方法不但性能出色，还显著提升了训练效率。比如，仅基于语言的指令调优在评估的数据集中表现出有竞争力的平均性能（在语言数据集上表现更优），同时训练效率大幅提高（平均提升 4 倍），这得益于对视觉数据需求的显著降低。只需少量视觉指令，这种新兴的遵循语言指令的能力就能出色地迁移到未曾见过的视觉数据集中，以更高的训练效率超越先进水平。

> We present a novel instruction tuning recipe to improve the zero-shot task generalization of multimodal large language models. In contrast to existing instruction tuning mechanisms that heavily rely on visual instructions, our approach focuses on language-based instruction tuning, offering a distinct and more training efficient path for multimodal instruction tuning. We evaluate the performance of the proposed approach on 9 unseen datasets across both language and vision modalities. Our results show that our language-only instruction tuning is able to significantly improve the performance of two pretrained multimodal models based on Llama 2 and Vicuna on those unseen datasets. Interestingly, the language instruction following ability also helps unlock the models to follow vision instructions without explicit training. Compared to the state of the art multimodal instruction tuning approaches that are mainly based on visual instructions, our language-based method not only achieves superior performance but also significantly enhances training efficiency. For instance, the language-only instruction tuning produces competitive average performance across the evaluated datasets (with even better performance on language datasets) with significant training efficiency improvements (on average 4x), thanks to the striking reduction in the need for vision data. With a small number of visual instructions, this emerging language instruction following ability transfers well to the unseen vision datasets, outperforming the state of the art with greater training efficiency.

[Arxiv](https://arxiv.org/abs/2411.10557)