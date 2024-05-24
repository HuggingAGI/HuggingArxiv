# 借助语言-视觉提示，实现低数据场景下的实例分割无监督预训练

发布时间：2024年05月22日

`Agent

理由：这篇论文主要介绍了一种新的无监督预训练策略，即语言视觉提示驱动的无监督预训练（UPLVP），用于提升基于DETR范式的查询基端到端实例分割方法（QEIS模型）在数据稀缺环境下的性能。这种方法通过引入语言视觉提示来改进查询/核的训练，从而增强模型的实例分割能力。虽然涉及到了语言视觉模型和预训练技术，但核心在于提出并应用了一种新的策略来优化特定的实例分割模型，这更符合Agent类别的定义，即关注于特定任务或应用的模型优化和策略开发。` `计算机视觉` `自动驾驶`

> Unsupervised Pre-training with Language-Vision Prompts for Low-Data Instance Segmentation

# 摘要

> 近期，基于DETR范式的查询基端到端实例分割方法在大型数据集上展现出优于传统CNN模型的性能。但当训练数据稀缺时，这些方法的效果大打折扣，原因在于它们需依赖大量数据来训练关键的查询/核，以获取精准的定位和形状信息。为此，我们提出了一种创新的无监督预训练策略，特别适用于数据有限的环境。借鉴近期流行的提示技术，我们开发了语言视觉提示驱动的无监督预训练（UPLVP），通过将语言视觉提示融入查询/核，显著提升了QEIS模型的实例分割能力。该方法分为三步：首先，利用语言视觉模型从未标记图像中生成伪掩码；其次，将这些掩码转化为提示，并将匹配度最高的定位与形状特征注入相应核中；最后，在核级别实施监督，确保预训练过程中的稳健学习。实验证明，采用我们的预训练方法，QEIS模型在数据稀缺条件下不仅收敛更快，性能也超越了CNN模型。MS COCO、Cityscapes和CTW1500数据集的测试结果均显示了显著的性能提升。相关代码将在GitHub上发布：https://github.com/lifuguan/UPLVP。

> In recent times, following the paradigm of DETR (DEtection TRansformer), query-based end-to-end instance segmentation (QEIS) methods have exhibited superior performance compared to CNN-based models, particularly when trained on large-scale datasets. Nevertheless, the effectiveness of these QEIS methods diminishes significantly when confronted with limited training data. This limitation arises from their reliance on substantial data volumes to effectively train the pivotal queries/kernels that are essential for acquiring localization and shape priors. To address this problem, we propose a novel method for unsupervised pre-training in low-data regimes. Inspired by the recently successful prompting technique, we introduce a new method, Unsupervised Pre-training with Language-Vision Prompts (UPLVP), which improves QEIS models' instance segmentation by bringing language-vision prompts to queries/kernels. Our method consists of three parts: (1) Masks Proposal: Utilizes language-vision models to generate pseudo masks based on unlabeled images. (2) Prompt-Kernel Matching: Converts pseudo masks into prompts and injects the best-matched localization and shape features to their corresponding kernels. (3) Kernel Supervision: Formulates supervision for pre-training at the kernel level to ensure robust learning. With the help of our pre-training method, QEIS models can converge faster and perform better than CNN-based models in low-data regimes. Experimental evaluations conducted on MS COCO, Cityscapes, and CTW1500 datasets indicate that the QEIS models' performance can be significantly improved when pre-trained with our method. Code will be available at: https://github.com/lifuguan/UPLVP.

[Arxiv](https://arxiv.org/abs/2405.13388)