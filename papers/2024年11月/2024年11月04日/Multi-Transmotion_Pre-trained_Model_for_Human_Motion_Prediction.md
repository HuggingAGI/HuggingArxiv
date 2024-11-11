# 多运动转换：用于人体运动预测的预训练模型

发布时间：2024年11月04日

`LLM应用` `自动驾驶` `社交机器人`

> Multi-Transmotion: Pre-trained Model for Human Motion Prediction

# 摘要

> 智能系统预测人类行为的能力至关重要，特别是在自动驾驶汽车导航和社交机器人等领域。然而，人类运动的复杂性阻碍了人类运动预测的标准化数据集的开发，从而阻碍了预训练模型的建立。在本文中，我们通过整合多个数据集（包括轨迹和 3D 姿态关键点）来解决这些限制，提出了一个用于人类运动预测的预训练模型。我们合并了跨越不同模态的七个不同的数据集，并对其格式进行了标准化。为了促进多模态预训练，我们引入了 Multi-Transmotion，这是一种基于创新变压器的为跨模态预训练设计的模型。此外，我们提出了一种新颖的掩蔽策略来捕获丰富的表示。我们的方法在包括 NBA 和 JTA 数据集中的轨迹预测以及 AMASS 和 3DPW 数据集中的姿态预测等多个下游任务的各种数据集上表现出有竞争力的性能。代码可公开获取：https://github.com/vita-epfl/multi-transmotion

> The ability of intelligent systems to predict human behaviors is crucial, particularly in fields such as autonomous vehicle navigation and social robotics. However, the complexity of human motion have prevented the development of a standardized dataset for human motion prediction, thereby hindering the establishment of pre-trained models. In this paper, we address these limitations by integrating multiple datasets, encompassing both trajectory and 3D pose keypoints, to propose a pre-trained model for human motion prediction. We merge seven distinct datasets across varying modalities and standardize their formats. To facilitate multimodal pre-training, we introduce Multi-Transmotion, an innovative transformer-based model designed for cross-modality pre-training. Additionally, we present a novel masking strategy to capture rich representations. Our methodology demonstrates competitive performance across various datasets on several downstream tasks, including trajectory prediction in the NBA and JTA datasets, as well as pose prediction in the AMASS and 3DPW datasets. The code is publicly available: https://github.com/vita-epfl/multi-transmotion

[Arxiv](https://arxiv.org/abs/2411.02673)