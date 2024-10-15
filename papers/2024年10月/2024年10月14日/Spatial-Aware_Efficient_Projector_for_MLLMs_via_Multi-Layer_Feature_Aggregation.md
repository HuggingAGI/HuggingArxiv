# 多层特征聚合助力多语言大型语言模型实现空间感知高效投影

发布时间：2024年10月14日

`LLM应用` `人工智能` `计算机视觉`

> Spatial-Aware Efficient Projector for MLLMs via Multi-Layer Feature Aggregation

# 摘要

> 在多模态语言模型中，投影仪的作用举足轻重。它输出的视觉标记数量关乎模型效率，质量则影响视觉理解能力。当前研究多聚焦于减少视觉标记以提升效率，却忽略了二维视觉标记序列与自然语言序列间的空间差异。为此，我们设计了空间感知高效投影仪 (SAEP)。SAEP 通过改进的可分离深度卷积模块，强化视觉标记的空间信息，不仅大幅减少标记数量（达 75\%），还显著提升模型的多模态空间理解力。在多模态评估基准上，SAEP 表现卓越，有效弥合了模态间的差距。

> The projector plays a crucial role in multi-modal language models (MLLMs). The number of visual tokens it outputs affects the efficiency of the MLLM, while the quality of the visual tokens influences the visual understanding capabilities of the MLLM. Current explorations on the projector focus on reducing the number of visual tokens to improve efficiency, often overlooking the inherent spatial discrepancy between the serialized 2-dimensional visual token sequences and natural language token sequences. A Spatial-Aware Efficient Projector (SAEP) is proposed to address this issue. In detail, our SAEP method employs an modified separable depthwise convolution module on multi-layer visual features to enhance the spatial information of visual tokens. As a result, our SAEP method can not only largely reduce the number of visual tokens by 75\%, but also significantly improve the multimodal spatial understanding capability of MLLMs. Moreover, compared to existing projectors, our SAEP gets best performances on massive multimodal evaluation benchmarks, which denotes its effectiveness on bridging the modality gap.

[Arxiv](https://arxiv.org/abs/2410.10319)