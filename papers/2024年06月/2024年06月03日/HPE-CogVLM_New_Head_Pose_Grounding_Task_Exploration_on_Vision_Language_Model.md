# HPE-CogVLM：探索视觉语言模型中的头部姿态基础新任务

发布时间：2024年06月03日

`Agent

理由：这篇论文主要讨论了如何利用CogVLM（一种视觉语言模型）来增强头部姿态估计（HPE）任务的性能。论文中提到的新框架涉及解决大型语言模型中的灾难性遗忘问题，并通过模型合并策略提升HPE性能。这表明论文的重点在于开发和应用一个特定的Agent（即CogVLM）来解决实际问题（HPE），而不是专注于LLM的理论研究或应用。因此，这篇论文更适合归类为Agent。` `计算机视觉` `人机交互`

> HPE-CogVLM: New Head Pose Grounding Task Exploration on Vision Language Model

# 摘要

> 头部姿态估计（HPE）任务对3D空间关系的理解要求极高，且需精确计算偏航、俯仰和滚转的欧拉角。传统HPE研究多依赖非大型语言模型（Non-LLMs），这些模型以裁剪自完整图像的近距离人头部为输入，实际应用中鲁棒性不足。本文创新性地利用CogVLM的视觉定位能力，提出了一种增强HPE预测的新框架。CogVLM作为具备预测物体边界框能力的视觉语言模型，使HPE得以利用完整图像信息进行训练和预测。为将HPE融入VLM，我们首先解决了大型语言模型中的灾难性遗忘问题，通过调整数据复现比率。接着，我们提出并验证了一种基于LoRA层的模型合并策略，确保参数完整性，显著提升了HPE性能。实验表明，我们的HPE-CogVLM在跨数据集评估中，相比基于Non-LLM的顶尖技术，将平均绝对误差降低了31.5%。与其他方法相比，我们的框架在所有HPE指标上均展现出更优的性能。

> Head pose estimation (HPE) task requires a sophisticated understanding of 3D spatial relationships and precise numerical output of yaw, pitch, and roll Euler angles. Previous HPE studies are mainly based on Non-large language models (Non-LLMs), which rely on close-up human heads cropped from the full image as inputs and lack robustness in real-world scenario. In this paper, we present a novel framework to enhance the HPE prediction task by leveraging the visual grounding capability of CogVLM. CogVLM is a vision language model (VLM) with grounding capability of predicting object bounding boxes (BBoxes), which enables HPE training and prediction using full image information input. To integrate the HPE task into the VLM, we first cop with the catastrophic forgetting problem in large language models (LLMs) by investigating the rehearsal ratio in the data rehearsal method. Then, we propose and validate a LoRA layer-based model merging method, which keeps the integrity of parameters, to enhance the HPE performance in the framework. The results show our HPE-CogVLM achieves a 31.5\% reduction in Mean Absolute Error for HPE prediction over the current Non-LLM based state-of-the-art in cross-dataset evaluation. Furthermore, we compare our LoRA layer-based model merging method with LoRA fine-tuning only and other merging methods in CogVLM. The results demonstrate our framework outperforms them in all HPE metrics.

![HPE-CogVLM：探索视觉语言模型中的头部姿态基础新任务](../../../paper_images/2406.01914/x1.png)

![HPE-CogVLM：探索视觉语言模型中的头部姿态基础新任务](../../../paper_images/2406.01914/x2.png)

![HPE-CogVLM：探索视觉语言模型中的头部姿态基础新任务](../../../paper_images/2406.01914/x3.png)

![HPE-CogVLM：探索视觉语言模型中的头部姿态基础新任务](../../../paper_images/2406.01914/x4.png)

![HPE-CogVLM：探索视觉语言模型中的头部姿态基础新任务](../../../paper_images/2406.01914/x5.png)

![HPE-CogVLM：探索视觉语言模型中的头部姿态基础新任务](../../../paper_images/2406.01914/left_head.png)

![HPE-CogVLM：探索视觉语言模型中的头部姿态基础新任务](../../../paper_images/2406.01914/right_head.png)

[Arxiv](https://arxiv.org/abs/2406.01914)