# DRiVE：基于扩散的绑定助力生成多才多艺且富有表现力的角色

发布时间：2024年11月26日

`其他` `3D 动画` `角色重建`

> DRiVE: Diffusion-based Rigging Empowers Generation of Versatile and Expressive Characters

# 摘要

> 近期生成模型的进步已能从多模态实现高品质的 3D 角色重建。然而，给这些生成的角色制作动画仍是个难题，尤其是像服装和头发这类复杂元素，因为缺少大规模数据集和有效的装配手段。为填补这一空缺，我们精心整理了 AnimeRig，这是一个带有详细骨骼和蒙皮注释的大规模数据集。基于此，我们提出 DRiVE，这是用于生成和装配具有复杂结构的 3D 人物角色的新颖框架。和现有方法不同，DRiVE 运用 3D 高斯表示，利于高效动画和高质量渲染。我们还引入 GSDiff，这是一个基于 3D 高斯的扩散模块，能将关节位置预测为空间分布，克服了基于回归方法的局限。大量实验表明，DRiVE 达成了精准的装配效果，能让服装和头发呈现逼真的动态，在质量和通用性上都超越了以往方法。代码和数据集一经接受，将公开供学术使用。

> Recent advances in generative models have enabled high-quality 3D character reconstruction from multi-modal. However, animating these generated characters remains a challenging task, especially for complex elements like garments and hair, due to the lack of large-scale datasets and effective rigging methods. To address this gap, we curate AnimeRig, a large-scale dataset with detailed skeleton and skinning annotations. Building upon this, we propose DRiVE, a novel framework for generating and rigging 3D human characters with intricate structures. Unlike existing methods, DRiVE utilizes a 3D Gaussian representation, facilitating efficient animation and high-quality rendering. We further introduce GSDiff, a 3D Gaussian-based diffusion module that predicts joint positions as spatial distributions, overcoming the limitations of regression-based approaches. Extensive experiments demonstrate that DRiVE achieves precise rigging results, enabling realistic dynamics for clothing and hair, and surpassing previous methods in both quality and versatility. The code and dataset will be made public for academic use upon acceptance.

[Arxiv](https://arxiv.org/abs/2411.17423)