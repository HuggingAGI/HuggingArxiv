# 在朦胧条件下，用于可见光和红外图像联合恢复及融合的红外辅助单阶段框架

发布时间：2024年11月15日

`其他` `图像融合`

> Infrared-Assisted Single-Stage Framework for Joint Restoration and Fusion of Visible and Infrared Images under Hazy Conditions

# 摘要

> 红外和可见光（IR-VIS）图像融合因其广泛的应用价值而备受瞩目。然而，现有的方法往往忽视了在朦胧状态下红外图像对恢复可见光图像特征的互补作用。为此，我们提出了一个联合学习框架，借助红外图像来恢复和融合朦胧的 IR-VIS 图像。为降低 IR-VIS 图像间特征多样性的不良影响，我们引入了一种提示生成机制，用以调节特定模态的特征不兼容情况。这从非共享图像信息创建了一个提示选择矩阵，接着从提示池中生成提示嵌入。这些嵌入有助于生成去雾的候选特征。我们还进一步设计了一个红外辅助特征恢复机制，依据雾度密度选择候选特征，在单阶段框架内实现同步恢复与融合。为提升融合质量，我们构建了一个多阶段提示嵌入融合模块，利用提示生成模块的特征补充。我们的方法能有效融合 IR-VIS 图像并去除雾气，得到清晰、无雾的融合结果。与先去雾再融合的两阶段方法不同，我们的方法能在单阶段框架中进行协同训练，使模型相对轻便，适合实际应用。实验结果证实了其有效性，并展现出相较于现有方法的优势。

> Infrared and visible (IR-VIS) image fusion has gained significant attention for its broad application value. However, existing methods often neglect the complementary role of infrared image in restoring visible image features under hazy conditions. To address this, we propose a joint learning framework that utilizes infrared image for the restoration and fusion of hazy IR-VIS images. To mitigate the adverse effects of feature diversity between IR-VIS images, we introduce a prompt generation mechanism that regulates modality-specific feature incompatibility. This creates a prompt selection matrix from non-shared image information, followed by prompt embeddings generated from a prompt pool. These embeddings help generate candidate features for dehazing. We further design an infrared-assisted feature restoration mechanism that selects candidate features based on haze density, enabling simultaneous restoration and fusion within a single-stage framework. To enhance fusion quality, we construct a multi-stage prompt embedding fusion module that leverages feature supplementation from the prompt generation module. Our method effectively fuses IR-VIS images while removing haze, yielding clear, haze-free fusion results. In contrast to two-stage methods that dehaze and then fuse, our approach enables collaborative training in a single-stage framework, making the model relatively lightweight and suitable for practical deployment. Experimental results validate its effectiveness and demonstrate advantages over existing methods.

[Arxiv](https://arxiv.org/abs/2411.12586)