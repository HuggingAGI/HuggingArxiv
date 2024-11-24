# EnvoDat：一个用于异构环境中机器人空间感知与语义推理的大规模多感官数据集

发布时间：2024年10月29日

`其他` `机器人` `自动驾驶`

> EnvoDat: A Large-Scale Multisensory Dataset for Robotic Spatial Awareness and Semantic Reasoning in Heterogeneous Environments

# 摘要

> 要保证机器人在各类现实状况下的自主运行效率，高质量的异构数据集对于衡量操作算法的性能与稳健性不可或缺。当下的基准测试多聚焦于城市地形，尤其是道路自动驾驶，而像地下隧道、自然田野和现代室内空间这类多退化、植被浓密、动态且特征稀疏的环境，却缺乏足够的代表性。为弥补这一空缺，我们推出了 EnvoDat，这是一个在多样环境和条件下采集的大规模多模态数据集，涵盖高光照、雾、雨以及不同时段的零能见度。总的来说，EnvoDat 包含来自 13 个场景的 26 个序列、10 种传感模式、超过 1.9TB 的数据以及超过 89K 针对 82 个以上对象和地形类别的基于细粒度多边形的标注。我们将 EnvoDat 以不同格式进行了后处理，以支持对 SLAM 和监督学习算法的基准测试，以及对多模态视觉模型的微调。凭借 EnvoDat，我们为条件极端恶劣地区的环境适应型机器人自主运行贡献了力量。数据集及其他相关资源可通过 https://linusnep.github.io/EnvoDat/ 获取。

> To ensure the efficiency of robot autonomy under diverse real-world conditions, a high-quality heterogeneous dataset is essential to benchmark the operating algorithms' performance and robustness. Current benchmarks predominantly focus on urban terrains, specifically for on-road autonomous driving, leaving multi-degraded, densely vegetated, dynamic and feature-sparse environments, such as underground tunnels, natural fields, and modern indoor spaces underrepresented. To fill this gap, we introduce EnvoDat, a large-scale, multi-modal dataset collected in diverse environments and conditions, including high illumination, fog, rain, and zero visibility at different times of the day. Overall, EnvoDat contains 26 sequences from 13 scenes, 10 sensing modalities, over 1.9TB of data, and over 89K fine-grained polygon-based annotations for more than 82 object and terrain classes. We post-processed EnvoDat in different formats that support benchmarking SLAM and supervised learning algorithms, and fine-tuning multimodal vision models. With EnvoDat, we contribute to environment-resilient robotic autonomy in areas where the conditions are extremely challenging. The datasets and other relevant resources can be accessed through https://linusnep.github.io/EnvoDat/.

[Arxiv](https://arxiv.org/abs/2410.22200)