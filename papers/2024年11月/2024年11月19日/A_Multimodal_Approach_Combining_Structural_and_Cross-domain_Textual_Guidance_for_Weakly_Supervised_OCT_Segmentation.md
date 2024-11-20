# 一种将结构与跨领域文本指导相结合的多模态方法，用于弱监督 OCT 分割

发布时间：2024年11月19日

`其他` `医学成像`

> A Multimodal Approach Combining Structural and Cross-domain Textual Guidance for Weakly Supervised OCT Segmentation

# 摘要

> 准确分割光学相干断层扫描（OCT）图像对于诊断和监测视网膜疾病意义重大。但像素级标注颇为费力，限制了基于大型数据集的监督学习的可扩展性。弱监督语义分割（WSSS）凭借图像级标签，成为颇具前景的替代之选。本研究提出一种全新的 WSSS 方法，将结构引导与文本驱动策略相融合，生成高质量伪标签，大幅提升分割性能。就视觉信息而言，我们的方法运用两个处理模块，交换 OCT 图像的原始图像特征与结构特征，引导模型判别病变可能出现的位置。就文本信息来说，我们借助来自跨领域的大规模预训练模型，实现标签提示的文本引导以及合成描述集成，其中两个文本处理模块将局部语义特征与一致的合成描述相结合。通过在多模态框架中融合这些视觉和文本元素，我们的方法提高了病变定位的精准度。在三个 OCT 数据集上的实验结果显示，我们的方法达到了前沿水平，凸显了其在提升医学成像诊断准确性和效率方面的潜力。

> Accurate segmentation of Optical Coherence Tomography (OCT) images is crucial for diagnosing and monitoring retinal diseases. However, the labor-intensive nature of pixel-level annotation limits the scalability of supervised learning with large datasets. Weakly Supervised Semantic Segmentation (WSSS) provides a promising alternative by leveraging image-level labels. In this study, we propose a novel WSSS approach that integrates structural guidance with text-driven strategies to generate high-quality pseudo labels, significantly improving segmentation performance. In terms of visual information, our method employs two processing modules that exchange raw image features and structural features from OCT images, guiding the model to identify where lesions are likely to occur. In terms of textual information, we utilize large-scale pretrained models from cross-domain sources to implement label-informed textual guidance and synthetic descriptive integration with two textual processing modules that combine local semantic features with consistent synthetic descriptions. By fusing these visual and textual components within a multimodal framework, our approach enhances lesion localization accuracy. Experimental results on three OCT datasets demonstrate that our method achieves state-of-the-art performance, highlighting its potential to improve diagnostic accuracy and efficiency in medical imaging.

[Arxiv](https://arxiv.org/abs/2411.12615)