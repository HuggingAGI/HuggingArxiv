# CLIP-CID：借助集群与实例的区分，实现CLIP的高效蒸馏

发布时间：2024年08月18日

`LLM应用` `计算机视觉`

> CLIP-CID: Efficient CLIP Distillation via Cluster-Instance Discrimination

# 摘要

> CLIP 在多任务中表现卓越，但其效果依赖于大量预训练数据，消耗大量计算资源。尽管知识蒸馏在单一模态模型中应用广泛，但如何高效扩展至视觉-语言基础模型仍待探索。本文提出 CLIP-CID，一种新型蒸馏机制，能有效将大型视觉-语言模型知识转移至小型模型。我们首先采用简单高效的图像语义平衡法，减少迁移偏差，提高蒸馏效率，从 LAION400M 中剔除 43.7% 的图像-文本对，性能依旧卓越。随后，通过集群-实例区分，促进教师模型向学生模型的知识转移，使学生模型获得全面的预训练数据语义理解。实验显示，CLIP-CID 在多种下游任务中，包括线性探针和零-shot 分类，均达到顶尖性能。

> Contrastive Language-Image Pre-training (CLIP) has achieved excellent performance over a wide range of tasks. However, the effectiveness of CLIP heavily relies on a substantial corpus of pre-training data, resulting in notable consumption of computational resources. Although knowledge distillation has been widely applied in single modality models, how to efficiently expand knowledge distillation to vision-language foundation models with extensive data remains relatively unexplored. In this paper, we introduce CLIP-CID, a novel distillation mechanism that effectively transfers knowledge from a large vision-language foundation model to a smaller model. We initially propose a simple but efficient image semantic balance method to reduce transfer learning bias and improve distillation efficiency. This method filters out 43.7% of image-text pairs from the LAION400M while maintaining superior performance. After that, we leverage cluster-instance discrimination to facilitate knowledge transfer from the teacher model to the student model, thereby empowering the student model to acquire a holistic semantic comprehension of the pre-training data. Experimental results demonstrate that CLIP-CID achieves state-of-the-art performance on various downstream tasks including linear probe and zero-shot classification.

[Arxiv](https://arxiv.org/abs/2408.09441)