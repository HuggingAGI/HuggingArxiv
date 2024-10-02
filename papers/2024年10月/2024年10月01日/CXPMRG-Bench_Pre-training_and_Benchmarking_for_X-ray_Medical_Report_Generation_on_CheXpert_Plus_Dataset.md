# CXPMRG-Bench：基于 CheXpert Plus 数据集，为 X 射线医学报告生成提供预训练与基准测试

发布时间：2024年10月01日

`LLM应用` `人工智能`

> CXPMRG-Bench: Pre-training and Benchmarking for X-ray Medical Report Generation on CheXpert Plus Dataset

# 摘要

> 基于X射线图像的医学报告生成（MRG）在人工智能领域至关重要，能大幅减轻诊断负担并缩短患者等待时间。尽管已有显著进展，但受限于基准数据集的匮乏和现有大型模型在该领域的提升不足，该任务已遇瓶颈。特别是，新发布的CheXpert Plus数据集缺乏比较评估算法，使得后续算法的训练与评估变得复杂。为此，我们在CheXpert Plus数据集上对主流X射线报告生成模型和大型语言模型（LLMs）进行了全面基准测试。我们相信，这一基准将为后续算法提供坚实比较基础，并助力研究人员快速掌握该领域前沿模型。此外，我们提出了一种采用多阶段预训练策略的大型模型，包括自监督自回归生成和X射线报告对比学习，以及监督微调。实验结果显示，基于Mamba的自回归预训练有效编码了X射线图像，而图像-文本对比预训练进一步优化了特征空间，实验效果显著提升。源代码可在\url{https://github.com/Event-AHU/Medical_Image_Analysis}获取。

> X-ray image-based medical report generation (MRG) is a pivotal area in artificial intelligence which can significantly reduce diagnostic burdens and patient wait times. Despite significant progress, we believe that the task has reached a bottleneck due to the limited benchmark datasets and the existing large models' insufficient capability enhancements in this specialized domain. Specifically, the recently released CheXpert Plus dataset lacks comparative evaluation algorithms and their results, providing only the dataset itself. This situation makes the training, evaluation, and comparison of subsequent algorithms challenging. Thus, we conduct a comprehensive benchmarking of existing mainstream X-ray report generation models and large language models (LLMs), on the CheXpert Plus dataset. We believe that the proposed benchmark can provide a solid comparative basis for subsequent algorithms and serve as a guide for researchers to quickly grasp the state-of-the-art models in this field. More importantly, we propose a large model for the X-ray image report generation using a multi-stage pre-training strategy, including self-supervised autoregressive generation and Xray-report contrastive learning, and supervised fine-tuning. Extensive experimental results indicate that the autoregressive pre-training based on Mamba effectively encodes X-ray images, and the image-text contrastive pre-training further aligns the feature spaces, achieving better experimental results. Source code can be found on \url{https://github.com/Event-AHU/Medical_Image_Analysis}.

[Arxiv](https://arxiv.org/abs/2410.00379)