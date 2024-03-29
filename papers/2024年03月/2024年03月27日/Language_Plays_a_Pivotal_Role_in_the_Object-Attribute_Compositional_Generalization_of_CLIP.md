# 语言对于CLIP进行对象属性组合泛化具有至关重要的影响。

发布时间：2024年03月27日

`LLM应用` `计算机视觉` `机器学习`

> Language Plays a Pivotal Role in the Object-Attribute Compositional Generalization of CLIP

# 摘要

> 像 CLIP 这样的视觉-语言模型在应对各种分布变化时，展现出了不凡的泛化潜力。本研究继续探索这一现象的根本原因，特别关注那些由罕见属性和对象组合构成的图像，考察模型是否能够准确识别这些新颖图像的组合类别。我们设计了一套真实的测试图像集 ImageNet-AO，其中包含的训练对象属性在 CLIP 的训练集中鲜有出现。研究结果显示，相较于小型数据集训练的 CLIP 和传统监督模型，使用 OpenAI CLIP、LAION-400M 和 LAION-2B 等大型数据集训练的 CLIP 在处理这类分布外新颖组合时，表现出显著的性能提升。这一发现强调了训练数据的广度与多样性，以及语言指导在提升模型泛化能力方面的重要性。

> Vision-language models, such as CLIP, have shown promising Out-of-Distribution (OoD) generalization under various types of distribution shifts. Recent studies attempted to investigate the leading cause of this capability. In this work, we follow the same path, but focus on a specific type of OoD data - images with novel compositions of attribute-object pairs - and study whether such models can successfully classify those images into composition classes. We carefully designed an authentic image test dataset called ImageNet-AO, consisting of attributes for objects that are unlikely encountered in the CLIP training sets. We found that CLIPs trained with large datasets such as OpenAI CLIP, LAION-400M, and LAION-2B show orders-of-magnitude improvement in effective compositional OoD generalization compared to both supervised models and CLIPs trained with smaller datasets, such as CC-12M and YFCC-15M. Our results provide evidence that the scale and diversity of training data and language supervision play a key role in unlocking the compositional generalization abilities of vision-language models.

![语言对于CLIP进行对象属性组合泛化具有至关重要的影响。](../../../paper_images/2403.18525/two_plot4.pdf)

![语言对于CLIP进行对象属性组合泛化具有至关重要的影响。](../../../paper_images/2403.18525/first_fig.drawio.pdf)

![语言对于CLIP进行对象属性组合泛化具有至关重要的影响。](../../../paper_images/2403.18525/NMI_plot2.pdf)

![语言对于CLIP进行对象属性组合泛化具有至关重要的影响。](../../../paper_images/2403.18525/all_in_vs_orginal.pdf)

![语言对于CLIP进行对象属性组合泛化具有至关重要的影响。](../../../paper_images/2403.18525/all_in_vs_ood_experiment3.pdf)

![语言对于CLIP进行对象属性组合泛化具有至关重要的影响。](../../../paper_images/2403.18525/few_shot.pdf)

![语言对于CLIP进行对象属性组合泛化具有至关重要的影响。](../../../paper_images/2403.18525/full_finetune.pdf)

[Arxiv](https://arxiv.org/abs/2403.18525)