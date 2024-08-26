# Sapiens：构筑人类视觉模型的基石

发布时间：2024年08月22日

`Agent` `计算机视觉` `人工智能`

> Sapiens: Foundation for Human Vision Models

# 摘要

> 摘要：我们推出 Sapiens 模型系列，专为四项核心人类视觉任务设计：2D 姿态估计、身体部位分割、深度预测及表面法线推断。这些模型支持 1K 高分辨率处理，并可通过微调在 3 亿张真实场景人类图像上预训练的模型，轻松适应特定任务。实验表明，在同等计算资源下，对精选人类图像进行自监督预训练能大幅提升多类人相关任务性能。Sapiens 模型在处理真实数据时展现出卓越泛化性，即便在标记数据稀少或全为合成数据的情况下亦是如此。此外，随着模型参数从 0.3 亿增至 20 亿，其跨任务表现同步提升。Sapiens 在多项人相关基准测试中均超越现有最佳水平，例如在 Humans-5K（姿态）上提升 7.6 mAP，在 Humans-2K（部位分割）上提升 17.1 mIoU，在 Hi4D（深度）上降低 22.4% 相对均方根误差，以及在 THuman2（法线）上减少 53.5% 相对角度误差。

> 
Abstract:We present Sapiens, a family of models for four fundamental human-centric vision tasks - 2D pose estimation, body-part segmentation, depth estimation, and surface normal prediction. Our models natively support 1K high-resolution inference and are extremely easy to adapt for individual tasks by simply fine-tuning models pretrained on over 300 million in-the-wild human images. We observe that, given the same computational budget, self-supervised pretraining on a curated dataset of human images significantly boosts the performance for a diverse set of human-centric tasks. The resulting models exhibit remarkable generalization to in-the-wild data, even when labeled data is scarce or entirely synthetic. Our simple model design also brings scalability - model performance across tasks improves as we scale the number of parameters from 0.3 to 2 billion. Sapiens consistently surpasses existing baselines across various human-centric benchmarks. We achieve significant improvements over the prior state-of-the-art on Humans-5K (pose) by 7.6 mAP, Humans-2K (part-seg) by 17.1 mIoU, Hi4D (depth) by 22.4% relative RMSE, and THuman2 (normal) by 53.5% relative angular error.
    

[Arxiv](https://arxiv.org/pdf/2408.12569)