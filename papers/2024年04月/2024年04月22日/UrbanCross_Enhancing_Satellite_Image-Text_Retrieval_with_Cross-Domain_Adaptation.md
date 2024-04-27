# UrbanCross：借助跨域适应技术，提升卫星图像与文本的检索能力

发布时间：2024年04月22日

`分类：Agent` `城市化`

> UrbanCross: Enhancing Satellite Image-Text Retrieval with Cross-Domain Adaptation

# 摘要

> 随着城市化进程的加速，对能够迅速检索富含地理语义信息的卫星图像-文本方法的需求日益迫切。然而，现有技术往往忽略了城市景观多样性之间的领域差异，过于集中于单一领域的检索性能提升。为应对这一挑战，我们推出了 UrbanCross，这是一个创新的跨领域卫星图像-文本检索框架。该框架依托于一个涵盖三国广泛地理标签的高质量跨领域数据集，以展现不同领域的丰富性。它结合了大型多模态模型（LMM）对文本进行精细化处理，以及分段任何模型（SAM）对视觉内容进行增强，实现了图像、分段与文本之间的精准匹配，提升了10%的检索效率。此外，UrbanCross 还融入了自适应课程源采样器和加权对抗性跨领域微调模块，逐步增强了对不同领域环境的适应能力。广泛的实验结果表明，UrbanCross 在检索效率和新城市环境适应性方面具有显著优势，相较于未采用领域适应机制的版本，平均性能提升了15%，有效缩小了不同领域之间的差距。

> Urbanization challenges underscore the necessity for effective satellite image-text retrieval methods to swiftly access specific information enriched with geographic semantics for urban applications. However, existing methods often overlook significant domain gaps across diverse urban landscapes, primarily focusing on enhancing retrieval performance within single domains. To tackle this issue, we present UrbanCross, a new framework for cross-domain satellite image-text retrieval. UrbanCross leverages a high-quality, cross-domain dataset enriched with extensive geo-tags from three countries to highlight domain diversity. It employs the Large Multimodal Model (LMM) for textual refinement and the Segment Anything Model (SAM) for visual augmentation, achieving a fine-grained alignment of images, segments and texts, yielding a 10% improvement in retrieval performance. Additionally, UrbanCross incorporates an adaptive curriculum-based source sampler and a weighted adversarial cross-domain fine-tuning module, progressively enhancing adaptability across various domains. Extensive experiments confirm UrbanCross's superior efficiency in retrieval and adaptation to new urban environments, demonstrating an average performance increase of 15% over its version without domain adaptation mechanisms, effectively bridging the domain gap.

[Arxiv](https://arxiv.org/abs/2404.14241)