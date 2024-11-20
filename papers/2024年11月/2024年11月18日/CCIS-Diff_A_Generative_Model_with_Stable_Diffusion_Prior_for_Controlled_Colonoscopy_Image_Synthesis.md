# CCIS-Diff：一种具备稳定扩散先验的生成式模型，用于实现结肠镜图像的可控合成

发布时间：2024年11月18日

`其他` `结肠镜检查`

> CCIS-Diff: A Generative Model with Stable Diffusion Prior for Controlled Colonoscopy Image Synthesis

# 摘要

> 结肠镜检查在识别腺瘤性息肉、预防结直肠癌方面极为关键。然而，鉴于现有结肠镜检查数据集规模小、获取难，开发强有力的息肉检测模型颇具挑战。此前虽有尝试合成结肠镜图像的努力，但当下的方法存在不稳定、数据多样性欠缺的问题。而且，这些方法对生成过程的把控不够精准，致使生成的图像达不到临床质量标准。为应对这些难题，我们提出了 CCIS-DIFF，这是一种基于扩散架构的高质量结肠镜图像合成的可控生成模型。我们的方法能精准掌控与临床描述相符的息肉的空间属性（息肉位置和形状）及临床特征。具体而言，我们引入了模糊掩码加权策略，将合成的息肉与结肠黏膜无缝融合，还引入了文本感知注意力机制，引导生成的图像体现临床特征。值得一提的是，为达此目的，我们构建了一个新的多模态结肠镜检查数据集，它整合了图像、掩码标注以及相应的临床文本描述。实验结果表明，我们的方法生成的结肠镜图像质量高、种类多，对空间限制和临床一致性的把控出色，为下游的分割和诊断任务提供了宝贵支持。

> Colonoscopy is crucial for identifying adenomatous polyps and preventing colorectal cancer. However, developing robust models for polyp detection is challenging by the limited size and accessibility of existing colonoscopy datasets. While previous efforts have attempted to synthesize colonoscopy images, current methods suffer from instability and insufficient data diversity. Moreover, these approaches lack precise control over the generation process, resulting in images that fail to meet clinical quality standards. To address these challenges, we propose CCIS-DIFF, a Controlled generative model for high-quality Colonoscopy Image Synthesis based on a Diffusion architecture. Our method offers precise control over both the spatial attributes (polyp location and shape) and clinical characteristics of polyps that align with clinical descriptions. Specifically, we introduce a blur mask weighting strategy to seamlessly blend synthesized polyps with the colonic mucosa, and a text-aware attention mechanism to guide the generated images to reflect clinical characteristics. Notably, to achieve this, we construct a new multi-modal colonoscopy dataset that integrates images, mask annotations, and corresponding clinical text descriptions. Experimental results demonstrate that our method generates high-quality, diverse colonoscopy images with fine control over both spatial constraints and clinical consistency, offering valuable support for downstream segmentation and diagnostic tasks.

[Arxiv](https://arxiv.org/abs/2411.12198)