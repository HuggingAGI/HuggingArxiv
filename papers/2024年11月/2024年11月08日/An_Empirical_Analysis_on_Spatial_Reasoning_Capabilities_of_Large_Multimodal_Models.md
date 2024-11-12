# 关于大型多模态模型的空间推理能力的实证分析

发布时间：2024年11月08日

`LLM应用` `计算机视觉` `多模态模型`

> An Empirical Analysis on Spatial Reasoning Capabilities of Large Multimodal Models

# 摘要

> 大型多模态模型（LMMs）在一系列视觉和语言任务中取得了强劲的性能。然而，它们的空间推理能力研究不足。在本文中，我们构建了一个新的 VQA 数据集，Spatial-MM，以全面研究 LMMs 的空间理解和推理能力。我们对对象关系和多跳推理的分析揭示了几个重要发现。首先，边界框和场景图，甚至是合成的，都可以显著增强 LMMs 的空间推理能力。其次，对于图像，LMMs 对于从人类视角提出的问题比从相机视角提出的问题更难回答。第三，思维链（CoT）提示并不能提高模型在涉及空间关系的复杂多跳问题上的性能。而且，在 MLLMs 中，空间推理步骤的准确性远低于非空间推理步骤。最后，我们对 GQA-spatial 的扰动分析表明，LMMs 在基本对象检测方面比复杂空间推理强得多。我们相信我们的基准数据集和深入分析可以激发对 LMMs 空间推理的进一步研究。Spatial-MM 基准可在以下网址获取：https://github.com/FatemehShiri/Spatial-MM

> Large Multimodal Models (LMMs) have achieved strong performance across a range of vision and language tasks. However, their spatial reasoning capabilities are under-investigated. In this paper, we construct a novel VQA dataset, Spatial-MM, to comprehensively study LMMs' spatial understanding and reasoning capabilities. Our analyses on object-relationship and multi-hop reasoning reveal several important findings. Firstly, bounding boxes and scene graphs, even synthetic ones, can significantly enhance LMMs' spatial reasoning. Secondly, LMMs struggle more with questions posed from the human perspective than the camera perspective about the image. Thirdly, chain of thought (CoT) prompting does not improve model performance on complex multi-hop questions involving spatial relations. % Moreover, spatial reasoning steps are much less accurate than non-spatial ones across MLLMs. Lastly, our perturbation analysis on GQA-spatial reveals that LMMs are much stronger at basic object detection than complex spatial reasoning. We believe our benchmark dataset and in-depth analyses can spark further research on LMMs spatial reasoning. Spatial-MM benchmark is available at: https://github.com/FatemehShiri/Spatial-MM

[Arxiv](https://arxiv.org/abs/2411.06048)