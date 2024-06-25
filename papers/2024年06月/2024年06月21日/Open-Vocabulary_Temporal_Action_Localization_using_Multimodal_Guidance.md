# 多模态引导下的开放词汇时间动作定位研究

发布时间：2024年06月21日

`LLM应用

这篇论文介绍了一种名为OVFormer的新型框架，它扩展了ActionFormer以适应开放词汇时间动作定位（OVTAL）的需求。OVFormer利用大语言模型（LLM）来获取丰富的类别描述，并通过交叉注意力机制增强多模态特征的引导。此外，它采用了两阶段训练策略，以适应新类别的识别。这些特性表明，该论文主要关注于如何应用LLM技术来解决视频分析中的特定问题，即开放词汇时间动作定位，因此属于LLM应用类别。` `视频分析` `动作识别`

> Open-Vocabulary Temporal Action Localization using Multimodal Guidance

# 摘要

> 开放词汇时间动作定位（OVTAL）技术使模型能够识别视频中的任何动作类别，无需为所有类别准备特定的训练数据。然而，这种灵活性也带来了挑战：模型不仅要识别训练中见过的动作，还要识别推理时出现的新类别。与传统的时间动作定位不同，OVTAL需要理解揭示新类别语义的上下文线索。为此，我们开发了OVFormer，这是一种扩展了ActionFormer的新型框架，具有三大创新：首先，利用任务特定提示从大语言模型中获取丰富的类别描述；其次，通过交叉注意力机制学习类别与视频帧特征的对齐，增强多模态特征的引导；最后，采用两阶段训练策略，先在大词汇数据集上训练，再针对下游数据进行微调，以适应新类别。OVFormer将现有方法扩展至开放词汇环境，并在THUMOS14和ActivityNet-1.3基准测试中展示了其有效性。相关代码和预训练模型将公开发布。

> Open-Vocabulary Temporal Action Localization (OVTAL) enables a model to recognize any desired action category in videos without the need to explicitly curate training data for all categories. However, this flexibility poses significant challenges, as the model must recognize not only the action categories seen during training but also novel categories specified at inference. Unlike standard temporal action localization, where training and test categories are predetermined, OVTAL requires understanding contextual cues that reveal the semantics of novel categories. To address these challenges, we introduce OVFormer, a novel open-vocabulary framework extending ActionFormer with three key contributions. First, we employ task-specific prompts as input to a large language model to obtain rich class-specific descriptions for action categories. Second, we introduce a cross-attention mechanism to learn the alignment between class representations and frame-level video features, facilitating the multimodal guided features. Third, we propose a two-stage training strategy which includes training with a larger vocabulary dataset and finetuning to downstream data to generalize to novel categories. OVFormer extends existing TAL methods to open-vocabulary settings. Comprehensive evaluations on the THUMOS14 and ActivityNet-1.3 benchmarks demonstrate the effectiveness of our method. Code and pretrained models will be publicly released.

![多模态引导下的开放词汇时间动作定位研究](../../../paper_images/2406.15556/x1.png)

![多模态引导下的开放词汇时间动作定位研究](../../../paper_images/2406.15556/x2.png)

![多模态引导下的开放词汇时间动作定位研究](../../../paper_images/2406.15556/x3.png)

![多模态引导下的开放词汇时间动作定位研究](../../../paper_images/2406.15556/x4.png)

![多模态引导下的开放词汇时间动作定位研究](../../../paper_images/2406.15556/x5.png)

![多模态引导下的开放词汇时间动作定位研究](../../../paper_images/2406.15556/x6.png)

![多模态引导下的开放词汇时间动作定位研究](../../../paper_images/2406.15556/x7.png)

![多模态引导下的开放词汇时间动作定位研究](../../../paper_images/2406.15556/x8.png)

![多模态引导下的开放词汇时间动作定位研究](../../../paper_images/2406.15556/x9.png)

![多模态引导下的开放词汇时间动作定位研究](../../../paper_images/2406.15556/x10.png)

![多模态引导下的开放词汇时间动作定位研究](../../../paper_images/2406.15556/x11.png)

[Arxiv](https://arxiv.org/abs/2406.15556)