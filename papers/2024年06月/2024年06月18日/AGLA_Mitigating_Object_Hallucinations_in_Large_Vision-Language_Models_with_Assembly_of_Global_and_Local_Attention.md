# AGLA：结合全局与局部注意力，有效缓解大型视觉-语言模型中的物体幻觉现象

发布时间：2024年06月18日

`LLM应用

这篇论文主要讨论了大型视觉-语言模型（LVLMs）中的对象幻觉问题，并提出了一种名为“全球和局部注意力组合（AGLA）”的方法来解决这一问题。该方法通过同时利用全局和局部特征来减少对象幻觉，并提升了模型的整体感知能力。由于论文的重点在于应用层面的改进和优化，即如何通过技术手段改善现有大型模型的性能，因此将其归类为LLM应用。` `计算机视觉`

> AGLA: Mitigating Object Hallucinations in Large Vision-Language Models with Assembly of Global and Local Attention

# 摘要

> 尽管大型视觉-语言模型（LVLMs）在多模态任务中表现出色，但它们普遍存在一个难题：对象幻觉，即生成的文本描述与图像中的真实对象不符。本文深入分析了多种LVLMs，并发现对关键局部图像特征的关注不足是导致这一问题的主要原因。LVLMs往往忽视与提示相关的局部特征，而过度关注全局特征，这削弱了其视觉基础能力，导致幻觉现象。为此，我们提出了一种名为“全球和局部注意力组合（AGLA）”的创新方法，它无需额外训练，即可通过同时利用全局和局部特征来有效减少对象幻觉。AGLA通过一种图像-提示匹配机制，从图像中提取与提示相关的局部特征，同时屏蔽无关干扰，从而提供了一个增强的图像视图。在此基础上，我们整合了原始图像的生成性全局特征和增强图像的区分性局部特征，以推导出更准确的解码分布。实验结果显示，AGLA在多个基准测试中显著减少了对象幻觉，并提升了LVLMs的整体感知能力。相关代码将在https://github.com/Lackel/AGLA公开。

> Despite their great success across various multimodal tasks, Large Vision-Language Models (LVLMs) are facing a prevalent problem with object hallucinations, where the generated textual responses are inconsistent with ground-truth objects in the given image. This paper investigates various LVLMs and pinpoints attention deficiency toward discriminative local image features as one root cause of object hallucinations. Specifically, LVLMs predominantly attend to prompt-independent global image features, while failing to capture prompt-relevant local features, consequently undermining the visual grounding capacity of LVLMs and leading to hallucinations. To this end, we propose Assembly of Global and Local Attention (AGLA), a training-free and plug-and-play approach that mitigates object hallucinations by exploring an ensemble of global features for response generation and local features for visual discrimination simultaneously. Our approach exhibits an image-prompt matching scheme that captures prompt-relevant local features from images, leading to an augmented view of the input image where prompt-relevant content is reserved while irrelevant distractions are masked. With the augmented view, a calibrated decoding distribution can be derived by integrating generative global features from the original image and discriminative local features from the augmented image. Extensive experiments show that AGLA consistently mitigates object hallucinations and enhances general perception capability for LVLMs across various discriminative and generative benchmarks. Our code will be released at https://github.com/Lackel/AGLA.

![AGLA：结合全局与局部注意力，有效缓解大型视觉-语言模型中的物体幻觉现象](../../../paper_images/2406.12718/x1.png)

![AGLA：结合全局与局部注意力，有效缓解大型视觉-语言模型中的物体幻觉现象](../../../paper_images/2406.12718/x2.png)

![AGLA：结合全局与局部注意力，有效缓解大型视觉-语言模型中的物体幻觉现象](../../../paper_images/2406.12718/x3.png)

![AGLA：结合全局与局部注意力，有效缓解大型视觉-语言模型中的物体幻觉现象](../../../paper_images/2406.12718/x8.png)

![AGLA：结合全局与局部注意力，有效缓解大型视觉-语言模型中的物体幻觉现象](../../../paper_images/2406.12718/x9.png)

![AGLA：结合全局与局部注意力，有效缓解大型视觉-语言模型中的物体幻觉现象](../../../paper_images/2406.12718/x10.png)

![AGLA：结合全局与局部注意力，有效缓解大型视觉-语言模型中的物体幻觉现象](../../../paper_images/2406.12718/x11.png)

[Arxiv](https://arxiv.org/abs/2406.12718)