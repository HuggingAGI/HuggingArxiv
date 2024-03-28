# RelationVLM 是一个旨在提升大型视觉-语言模型对视觉关系理解能力的模型。

发布时间：2024年03月19日

`Agent`

> RelationVLM: Making Large Vision-Language Models Understand Visual Relations

# 摘要

> 尽管LVLM紧随LLM的成功脚步快速发展，但面临的挑战更为艰巨。近期研究已让LVLM具备了定位图像中的物体级视觉内容并与文本建立联系的能力。不过，在缺乏相应数据的情况下，现有LVLM对于精准理解复杂的视觉关系仍显得力不从心。本研究引入RelationVLM这一强大视觉-语言模型，它能够在多个图像间或单个视频中解析多层次、多类型的关系。为此，我们创新性地设计了一套多阶段关系感知训练方案及配套的数据优化策略，赋能RelationVLM精准掌握语义关联、时序联系和几何变换等特性。广泛的案例分析和严谨的量化评估证明了RelationVLM在理解此类关系上的出色实力，且其在面对少量样本时展现出卓越的上下文推理能力。这项工作通过推动LVLM扩展对各类下游应用场景的支持，有力地促进了向人工通用智能方向的发展。

> The development of Large Vision-Language Models (LVLMs) is striving to catch up with the success of Large Language Models (LLMs), yet it faces more challenges to be resolved. Very recent works enable LVLMs to localize object-level visual contents and ground text to them. Nonetheless, current LVLMs still struggle to precisely understand visual relations due to the lack of relevant data. In this work, we present RelationVLM, a large vision-language model capable of comprehending various levels and types of relations whether across multiple images or within a video. Specifically, we devise a multi-stage relation-aware training scheme and a series of corresponding data configuration strategies to bestow RelationVLM with the capabilities of understanding semantic relations, temporal associations and geometric transforms. Extensive case studies and quantitative evaluations show RelationVLM has strong capability in understanding such relations and emerges impressive in-context capability of reasoning from few-shot examples by comparison. This work fosters the advancements of LVLMs by enabling them to support a wider range of downstream applications toward artificial general intelligence.

[Arxiv](https://arxiv.org/abs/2403.12801)