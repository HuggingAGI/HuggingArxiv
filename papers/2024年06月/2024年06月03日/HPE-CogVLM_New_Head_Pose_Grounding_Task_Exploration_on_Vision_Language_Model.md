# HPE-CogVLM：探索视觉语言模型中的头部姿态定位新任务

发布时间：2024年06月03日

`Agent

理由：这篇论文主要介绍了一种创新的框架，通过结合CogVLM（一种视觉语言模型）的能力来提升头部姿态估计（HPE）任务的准确性。虽然CogVLM是一个语言模型，但论文的重点在于如何利用这一模型来增强HPE任务，特别是在处理视觉信息和预测物体边界框方面。这与Agent分类中的智能体应用相关，因为Agent通常涉及如何利用模型或技术来解决特定任务或问题。此外，论文中提到的模型合并策略和灾难性遗忘问题的解决，也体现了对模型性能优化的关注，这是Agent领域常见的研究方向。因此，将这篇论文归类为Agent更为合适。` `计算机视觉` `人工智能`

> HPE-CogVLM: New Head Pose Grounding Task Exploration on Vision Language Model

# 摘要

> 头部姿态估计（HPE）任务要求对三维空间关系有精深理解，并准确计算出偏航、俯仰和滚转的欧拉角。以往的研究多依赖于非大型语言模型（Non-LLMs），这些模型以裁剪自完整图像的近距离人头部为输入，其在现实场景中的鲁棒性不足。本文介绍了一种创新框架，通过CogVLM的视觉定位能力提升HPE预测的准确性。CogVLM作为具备预测物体边界框能力的视觉语言模型，使得HPE能够利用完整图像信息进行训练和预测。为将HPE融入VLM，我们首先解决了大型语言模型中的灾难性遗忘问题，并通过数据复现方法调整复现比率。随后，我们提出并验证了一种基于LoRA层的模型合并策略，确保参数完整性，从而增强HPE性能。实验表明，我们的HPE-CogVLM在跨数据集评估中，相比基于Non-LLM的顶尖技术，将平均绝对误差降低了31.5%。此外，与仅LoRA微调及其他合并方法相比，我们的框架在所有HPE指标上均展现出更优性能。

> Head pose estimation (HPE) task requires a sophisticated understanding of 3D spatial relationships and precise numerical output of yaw, pitch, and roll Euler angles. Previous HPE studies are mainly based on Non-large language models (Non-LLMs), which rely on close-up human heads cropped from the full image as inputs and lack robustness in real-world scenario. In this paper, we present a novel framework to enhance the HPE prediction task by leveraging the visual grounding capability of CogVLM. CogVLM is a vision language model (VLM) with grounding capability of predicting object bounding boxes (BBoxes), which enables HPE training and prediction using full image information input. To integrate the HPE task into the VLM, we first cop with the catastrophic forgetting problem in large language models (LLMs) by investigating the rehearsal ratio in the data rehearsal method. Then, we propose and validate a LoRA layer-based model merging method, which keeps the integrity of parameters, to enhance the HPE performance in the framework. The results show our HPE-CogVLM achieves a 31.5\% reduction in Mean Absolute Error for HPE prediction over the current Non-LLM based state-of-the-art in cross-dataset evaluation. Furthermore, we compare our LoRA layer-based model merging method with LoRA fine-tuning only and other merging methods in CogVLM. The results demonstrate our framework outperforms them in all HPE metrics.

![HPE-CogVLM：探索视觉语言模型中的头部姿态定位新任务](../../../paper_images/2406.01914/x1.png)

![HPE-CogVLM：探索视觉语言模型中的头部姿态定位新任务](../../../paper_images/2406.01914/x2.png)

![HPE-CogVLM：探索视觉语言模型中的头部姿态定位新任务](../../../paper_images/2406.01914/x3.png)

![HPE-CogVLM：探索视觉语言模型中的头部姿态定位新任务](../../../paper_images/2406.01914/x4.png)

![HPE-CogVLM：探索视觉语言模型中的头部姿态定位新任务](../../../paper_images/2406.01914/x5.png)

![HPE-CogVLM：探索视觉语言模型中的头部姿态定位新任务](../../../paper_images/2406.01914/left_head.png)

![HPE-CogVLM：探索视觉语言模型中的头部姿态定位新任务](../../../paper_images/2406.01914/right_head.png)

[Arxiv](https://arxiv.org/abs/2406.01914)