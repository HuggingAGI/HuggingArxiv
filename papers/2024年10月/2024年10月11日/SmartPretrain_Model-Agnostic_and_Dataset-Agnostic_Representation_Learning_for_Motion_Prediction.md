# SmartPretrain：一种模型与数据集无关的表示学习方法，专为运动预测设计。

发布时间：2024年10月11日

`其他` `自动驾驶`

> SmartPretrain: Model-Agnostic and Dataset-Agnostic Representation Learning for Motion Prediction

# 摘要

> 自动驾驶车辆在复杂环境中安全运行，关键在于准确预测周围物体的未来运动。然而，大规模驾驶数据集的缺乏限制了运动预测模型的发展，使其难以应对复杂的交互和道路环境。借鉴自然语言处理和计算机视觉的最新进展，自监督学习（SSL）成为运动预测领域的热门话题，旨在学习可迁移的场景表示。然而，现有预训练方法多局限于特定模型和单一数据集，限制了其应用范围。为此，我们推出了SmartPretrain，一个不依赖特定模型和数据集的通用SSL框架。该框架融合对比学习和重建学习，有效捕捉时空动态，同时采用数据集无关的采样策略，提升数据多样性和鲁棒性。实验证明，SmartPretrain在多个数据集上显著提升了预测性能，例如将Forecast-MAE的MissRate降低了10.6%。SmartPretrain为运动预测提供了一个统一、可扩展的解决方案，突破了数据稀缺的瓶颈。代码已开源，详见https://github.com/youngzhou1999/SmartPretrain。

> Predicting the future motion of surrounding agents is essential for autonomous vehicles (AVs) to operate safely in dynamic, human-robot-mixed environments. However, the scarcity of large-scale driving datasets has hindered the development of robust and generalizable motion prediction models, limiting their ability to capture complex interactions and road geometries. Inspired by recent advances in natural language processing (NLP) and computer vision (CV), self-supervised learning (SSL) has gained significant attention in the motion prediction community for learning rich and transferable scene representations. Nonetheless, existing pre-training methods for motion prediction have largely focused on specific model architectures and single dataset, limiting their scalability and generalizability. To address these challenges, we propose SmartPretrain, a general and scalable SSL framework for motion prediction that is both model-agnostic and dataset-agnostic. Our approach integrates contrastive and reconstructive SSL, leveraging the strengths of both generative and discriminative paradigms to effectively represent spatiotemporal evolution and interactions without imposing architectural constraints. Additionally, SmartPretrain employs a dataset-agnostic scenario sampling strategy that integrates multiple datasets, enhancing data volume, diversity, and robustness. Extensive experiments on multiple datasets demonstrate that SmartPretrain consistently improves the performance of state-of-the-art prediction models across datasets, data splits and main metrics. For instance, SmartPretrain significantly reduces the MissRate of Forecast-MAE by 10.6%. These results highlight SmartPretrain's effectiveness as a unified, scalable solution for motion prediction, breaking free from the limitations of the small-data regime. Codes are available at https://github.com/youngzhou1999/SmartPretrain

[Arxiv](https://arxiv.org/abs/2410.08669)