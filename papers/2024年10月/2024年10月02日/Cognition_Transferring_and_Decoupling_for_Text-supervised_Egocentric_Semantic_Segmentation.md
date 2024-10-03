# 文本监督下的自我中心语义分割：认知转移与解耦

发布时间：2024年10月02日

`LLM应用` `计算机视觉` `人工智能`

> Cognition Transferring and Decoupling for Text-supervised Egocentric Semantic Segmentation

# 摘要

> 本文探讨了一项创新的文本监督自我中心语义分割（TESS）任务，旨在通过图像标签中的文本对自我中心图像进行弱监督，实现像素级分类。自我中心场景中密集的穿戴者-物体关系和物体间干扰是该任务的挑战。现有方法多依赖于第三方视角的预训练CLIP模型，因“关系不敏感”问题在自我中心视角中表现不佳。为此，我们提出了认知转移和解耦网络（CTDN），通过图像与文本的关联学习穿戴者-物体关系，并开发认知转移模块（CTM）从大规模预训练模型中提取认知知识，以识别自我中心物体的多样语义。前景-背景解耦模块（FDM）则解开视觉表示，明确区分前景和背景，减少干扰物引起的错误激活。实验证明，我们的方法在四个TESS基准上显著优于现有技术。代码即将在https://github.com/ZhaofengSHI/CTDN发布。

> In this paper, we explore a novel Text-supervised Egocentic Semantic Segmentation (TESS) task that aims to assign pixel-level categories to egocentric images weakly supervised by texts from image-level labels. In this task with prospective potential, the egocentric scenes contain dense wearer-object relations and inter-object interference. However, most recent third-view methods leverage the frozen Contrastive Language-Image Pre-training (CLIP) model, which is pre-trained on the semantic-oriented third-view data and lapses in the egocentric view due to the ``relation insensitive" problem. Hence, we propose a Cognition Transferring and Decoupling Network (CTDN) that first learns the egocentric wearer-object relations via correlating the image and text. Besides, a Cognition Transferring Module (CTM) is developed to distill the cognitive knowledge from the large-scale pre-trained model to our model for recognizing egocentric objects with various semantics. Based on the transferred cognition, the Foreground-background Decoupling Module (FDM) disentangles the visual representations to explicitly discriminate the foreground and background regions to mitigate false activation areas caused by foreground-background interferential objects during egocentric relation learning. Extensive experiments on four TESS benchmarks demonstrate the effectiveness of our approach, which outperforms many recent related methods by a large margin. Code will be available at https://github.com/ZhaofengSHI/CTDN.

[Arxiv](https://arxiv.org/abs/2410.01341)