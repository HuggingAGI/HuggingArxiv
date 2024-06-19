# CVPR2024基础少量样本目标检测挑战解决方案

发布时间：2024年06月17日

`Agent

理由：这篇论文介绍了一种改进的少样本目标检测方法，该方法利用视觉-语言模型（VLM）和多模态大型语言模型（MM-LLM）来提高检测精度。这种方法涉及创建和优化一个框架（VLM+），该框架通过生成和选择最佳的参考表达来改进目标检测。这个过程涉及到模型的自主决策和优化，因此可以被视为一个Agent的行为，即模型作为一个智能体在执行任务和优化性能。这与Agent分类下的研究内容相符，即关注模型如何作为智能体在特定任务中进行决策和优化。` `目标检测` `机器视觉`

> The Solution for CVPR2024 Foundational Few-Shot Object Detection Challenge

# 摘要

> 本报告提出了一种改进的少样本目标检测方法，利用视觉-语言模型（VLM）进行精准检测。但在某些数据集上，VLM可能出现检测目标与目标概念不匹配的问题，影响其零样本性能和基于伪标签的微调效果。为此，我们开发了VLM+框架，整合了多模态大型语言模型（MM-LLM），通过MM-LLM为每个类别生成参考表达，并基于VLM预测和标注数据，选择最佳匹配的表达作为伪标签，用于训练集图像，结合原始数据微调VLM。我们还引入了迭代优化过程，显著提升了VLM性能，最终测试中取得了32.56 mAP的优异成绩。

> This report introduces an enhanced method for the Foundational Few-Shot Object Detection (FSOD) task, leveraging the vision-language model (VLM) for object detection. However, on specific datasets, VLM may encounter the problem where the detected targets are misaligned with the target concepts of interest. This misalignment hinders the zero-shot performance of VLM and the application of fine-tuning methods based on pseudo-labels. To address this issue, we propose the VLM+ framework, which integrates the multimodal large language model (MM-LLM). Specifically, we use MM-LLM to generate a series of referential expressions for each category. Based on the VLM predictions and the given annotations, we select the best referential expression for each category by matching the maximum IoU. Subsequently, we use these referential expressions to generate pseudo-labels for all images in the training set and then combine them with the original labeled data to fine-tune the VLM. Additionally, we employ iterative pseudo-label generation and optimization to further enhance the performance of the VLM. Our approach achieve 32.56 mAP in the final test.

![CVPR2024基础少量样本目标检测挑战解决方案](../../../paper_images/2406.12225/x1.png)

![CVPR2024基础少量样本目标检测挑战解决方案](../../../paper_images/2406.12225/x2.png)

![CVPR2024基础少量样本目标检测挑战解决方案](../../../paper_images/2406.12225/x3.png)

![CVPR2024基础少量样本目标检测挑战解决方案](../../../paper_images/2406.12225/case1_1.png)

![CVPR2024基础少量样本目标检测挑战解决方案](../../../paper_images/2406.12225/case1_2.png)

![CVPR2024基础少量样本目标检测挑战解决方案](../../../paper_images/2406.12225/case2_1.png)

![CVPR2024基础少量样本目标检测挑战解决方案](../../../paper_images/2406.12225/case2_2.png)

![CVPR2024基础少量样本目标检测挑战解决方案](../../../paper_images/2406.12225/case3_1.png)

![CVPR2024基础少量样本目标检测挑战解决方案](../../../paper_images/2406.12225/case3_2.png)

![CVPR2024基础少量样本目标检测挑战解决方案](../../../paper_images/2406.12225/case4_1.png)

![CVPR2024基础少量样本目标检测挑战解决方案](../../../paper_images/2406.12225/case4_2.png)

![CVPR2024基础少量样本目标检测挑战解决方案](../../../paper_images/2406.12225/case5_1.png)

![CVPR2024基础少量样本目标检测挑战解决方案](../../../paper_images/2406.12225/case5_2.png)

![CVPR2024基础少量样本目标检测挑战解决方案](../../../paper_images/2406.12225/case6_1.png)

![CVPR2024基础少量样本目标检测挑战解决方案](../../../paper_images/2406.12225/case6_2.png)

[Arxiv](https://arxiv.org/abs/2406.12225)