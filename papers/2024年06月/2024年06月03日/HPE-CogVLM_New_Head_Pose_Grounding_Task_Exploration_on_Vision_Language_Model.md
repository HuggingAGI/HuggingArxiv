# HPE-CogVLM：探索视觉语言模型上的头部姿态接地新任务

发布时间：2024年06月03日

`Agent

理由：这篇论文主要讨论了如何将头部姿态估计（HPE）任务与视觉语言模型（VLM）CogVLM结合，以提高HPE的性能。文中提到的CogVLM具有视觉定位能力，能够预测物体边界框，从而帮助HPE利用完整图像信息进行训练和预测。此外，论文还解决了大型语言模型中的灾难性遗忘问题，并提出了一种基于LoRA层的模型合并策略。这些内容主要涉及如何利用视觉语言模型作为智能体（Agent）来增强特定任务（如HPE）的性能，因此归类为Agent。` `计算机视觉` `人机交互`

> HPE-CogVLM: New Head Pose Grounding Task Exploration on Vision Language Model

# 摘要

> 头部姿态估计（HPE）任务要求对3D空间关系有精妙理解，并准确计算出偏航、俯仰和滚转的欧拉角。以往的研究多依赖非大型语言模型（Non-LLMs），这些模型以裁剪自完整图像的近距离人像为输入，难以应对现实世界的复杂场景。本文创新性地利用CogVLM的视觉定位能力，提出了一种增强HPE预测的新框架。CogVLM作为视觉语言模型（VLM），能预测物体边界框，使HPE得以利用完整图像信息进行训练和预测。为整合HPE至VLM，我们首先解决了大型语言模型中的灾难性遗忘问题，通过调整数据复现方法中的复现比率。随后，我们提出并验证了一种基于LoRA层的模型合并策略，确保参数完整性，显著提升了HPE性能。实验表明，我们的HPE-CogVLM在跨数据集评估中，相比基于Non-LLM的顶尖技术，将平均绝对误差降低了31.5%。与其他方法相比，我们的框架在所有HPE指标上均展现出更优的性能。

> Head pose estimation (HPE) task requires a sophisticated understanding of 3D spatial relationships and precise numerical output of yaw, pitch, and roll Euler angles. Previous HPE studies are mainly based on Non-large language models (Non-LLMs), which rely on close-up human heads cropped from the full image as inputs and lack robustness in real-world scenario. In this paper, we present a novel framework to enhance the HPE prediction task by leveraging the visual grounding capability of CogVLM. CogVLM is a vision language model (VLM) with grounding capability of predicting object bounding boxes (BBoxes), which enables HPE training and prediction using full image information input. To integrate the HPE task into the VLM, we first cop with the catastrophic forgetting problem in large language models (LLMs) by investigating the rehearsal ratio in the data rehearsal method. Then, we propose and validate a LoRA layer-based model merging method, which keeps the integrity of parameters, to enhance the HPE performance in the framework. The results show our HPE-CogVLM achieves a 31.5\% reduction in Mean Absolute Error for HPE prediction over the current Non-LLM based state-of-the-art in cross-dataset evaluation. Furthermore, we compare our LoRA layer-based model merging method with LoRA fine-tuning only and other merging methods in CogVLM. The results demonstrate our framework outperforms them in all HPE metrics.

![HPE-CogVLM：探索视觉语言模型上的头部姿态接地新任务](../../../paper_images/2406.01914/x1.png)

![HPE-CogVLM：探索视觉语言模型上的头部姿态接地新任务](../../../paper_images/2406.01914/x2.png)

![HPE-CogVLM：探索视觉语言模型上的头部姿态接地新任务](../../../paper_images/2406.01914/x3.png)

![HPE-CogVLM：探索视觉语言模型上的头部姿态接地新任务](../../../paper_images/2406.01914/x4.png)

![HPE-CogVLM：探索视觉语言模型上的头部姿态接地新任务](../../../paper_images/2406.01914/x5.png)

![HPE-CogVLM：探索视觉语言模型上的头部姿态接地新任务](../../../paper_images/2406.01914/left_head.png)

![HPE-CogVLM：探索视觉语言模型上的头部姿态接地新任务](../../../paper_images/2406.01914/right_head.png)

[Arxiv](https://arxiv.org/abs/2406.01914)