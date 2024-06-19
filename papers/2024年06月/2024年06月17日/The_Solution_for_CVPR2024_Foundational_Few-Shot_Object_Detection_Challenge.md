# CVPR2024基础少量样本目标检测挑战解决方案

发布时间：2024年06月17日

`Agent

理由：这篇论文介绍了一种改进的目标检测方法（FSOD），并提出了一个名为VLM+的框架，该框架整合了MM-LLM来生成参考表达，并通过迭代优化过程提升性能。这个框架可以被视为一个智能Agent，因为它能够自主地进行目标检测和性能优化，符合Agent的定义，即一个能够感知环境并采取行动以达到目标的系统。虽然涉及到了LLM的应用，但主要焦点在于Agent的行为和性能优化，因此更适合归类为Agent。` `目标检测` `零样本学习`

> The Solution for CVPR2024 Foundational Few-Shot Object Detection Challenge

# 摘要

> 本报告提出了一种改进的FSOD方法，该方法利用VLM进行目标检测，但在特定数据集上可能出现检测目标与目标概念不匹配的问题，影响零样本性能和微调效果。为此，我们开发了VLM+框架，整合了MM-LLM，通过为每个类别生成参考表达，并基于最大IoU匹配选择最佳表达，进而生成伪标签，结合原始数据微调VLM。我们还引入了迭代优化过程，显著提升了VLM性能，最终测试中取得了32.56 mAP的成绩。

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