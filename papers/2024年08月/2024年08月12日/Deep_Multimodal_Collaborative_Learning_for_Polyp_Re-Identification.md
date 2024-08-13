# 深度多模态协同学习助力息肉再识别

发布时间：2024年08月12日

`LLM应用` `计算机视觉`

> Deep Multimodal Collaborative Learning for Polyp Re-Identification

# 摘要

> 结肠镜下息肉再识别任务，旨在从大量不同视角的图像中匹配同一息肉，对结直肠癌的防治至关重要。传统方法因领域差异，在结肠镜数据集上的表现不佳，且未能充分利用多模态信息。为此，我们创新性地提出了DMCL框架，通过深度多模态协同学习，有效提升模态间的协作与泛化能力。此外，我们引入了一种动态多模态特征融合策略，进一步优化了多模态表示的融合效果。实验证明，结合这一策略的多模态设置，在性能上显著超越了单模态再识别模型。

> Colonoscopic Polyp Re-Identification aims to match the same polyp from a large gallery with images from different views taken using different cameras and plays an important role in the prevention and treatment of colorectal cancer in computer-aided diagnosis. However, traditional methods for object ReID directly adopting CNN models trained on the ImageNet dataset usually produce unsatisfactory retrieval performance on colonoscopic datasets due to the large domain gap. Worsely, these solutions typically learn unimodal modal representations on the basis of visual samples, which fails to explore complementary information from different modalities. To address this challenge, we propose a novel Deep Multimodal Collaborative Learning framework named DMCL for polyp re-identification, which can effectively encourage modality collaboration and reinforce generalization capability in medical scenarios. On the basis of it, a dynamic multimodal feature fusion strategy is introduced to leverage the optimized multimodal representations for multimodal fusion via end-to-end training. Experiments on the standard benchmarks show the benefits of the multimodal setting over state-of-the-art unimodal ReID models, especially when combined with the specialized multimodal fusion strategy.

[Arxiv](https://arxiv.org/abs/2408.05914)