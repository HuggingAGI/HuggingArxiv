# EMMA：用于自动驾驶的端到端多模态模型

发布时间：2024年11月04日

`LLM应用` `自动驾驶` `多模态模型`

> EMMA: End-to-End Multimodal Model for Autonomous Driving

# 摘要

> 我们引入了 EMMA，这是一个用于自动驾驶的端到端多模态模型。基于多模态大型语言模型基础构建，EMMA 直接将原始相机传感器数据映射为各种特定于驾驶的输出，包括规划器轨迹、感知对象和道路图元素。EMMA 通过将所有非传感器输入（例如导航指令和自我车辆状态）和输出（例如轨迹和 3D 位置）表示为自然语言文本，最大限度地利用了预训练大型语言模型中的世界知识。这种方法允许 EMMA 在统一的语言空间中联合处理各种驾驶任务，并使用特定于任务的提示生成每个任务的输出。从经验上看，我们通过在 nuScenes 上的运动规划中实现最先进的性能以及在 Waymo 开放运动数据集（WOMD）上获得有竞争力的结果，证明了 EMMA 的有效性。EMMA 在 Waymo 开放数据集（WOD）上的以相机为主的 3D 对象检测方面也取得了有竞争力的结果。我们表明，将 EMMA 与规划器轨迹、对象检测和道路图任务共同训练可以在所有三个领域带来改进，突出了 EMMA 作为自动驾驶应用的多面手模型的潜力。然而，EMMA 也存在一定的局限性：它只能处理少量的图像帧，未纳入像 LiDAR 或雷达这样准确的 3D 传感模式，并且计算成本高昂。我们希望我们的结果能激发进一步的研究，以减轻这些问题，并进一步推动自动驾驶模型架构的技术发展。

> We introduce EMMA, an End-to-end Multimodal Model for Autonomous driving. Built on a multi-modal large language model foundation, EMMA directly maps raw camera sensor data into various driving-specific outputs, including planner trajectories, perception objects, and road graph elements. EMMA maximizes the utility of world knowledge from the pre-trained large language models, by representing all non-sensor inputs (e.g. navigation instructions and ego vehicle status) and outputs (e.g. trajectories and 3D locations) as natural language text. This approach allows EMMA to jointly process various driving tasks in a unified language space, and generate the outputs for each task using task-specific prompts. Empirically, we demonstrate EMMA's effectiveness by achieving state-of-the-art performance in motion planning on nuScenes as well as competitive results on the Waymo Open Motion Dataset (WOMD). EMMA also yields competitive results for camera-primary 3D object detection on the Waymo Open Dataset (WOD). We show that co-training EMMA with planner trajectories, object detection, and road graph tasks yields improvements across all three domains, highlighting EMMA's potential as a generalist model for autonomous driving applications. However, EMMA also exhibits certain limitations: it can process only a small amount of image frames, does not incorporate accurate 3D sensing modalities like LiDAR or radar and is computationally expensive. We hope that our results will inspire further research to mitigate these issues and to further evolve the state of the art in autonomous driving model architectures.

[Arxiv](https://arxiv.org/abs/2410.23262)