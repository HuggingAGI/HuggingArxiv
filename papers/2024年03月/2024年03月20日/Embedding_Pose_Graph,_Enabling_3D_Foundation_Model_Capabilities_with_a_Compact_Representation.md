# 通过嵌入姿态图并采用紧凑的表达形式，赋予三维基础模型强大的功能能力。

发布时间：2024年03月20日

`Agent` `机器人` `三维空间理解`

> Embedding Pose Graph, Enabling 3D Foundation Model Capabilities with a Compact Representation

> 本文带来了一项名为“嵌入姿态图”（EPG）的革新性技术，巧妙地融合了基础模型的力量和适应于机器人应用场景的简洁3D表达方式。针对机器人对空间高效认知的需求，EPG独辟蹊径，将基础模型特征与姿态图节点相结合，形成一种既精炼又强劲的方法论，不同于那些依赖于体积庞大数据格式（如体素网格或点云）的传统手段，EPG更为轻巧且具备良好的扩展性。此方法有力支持了一系列机器人任务，涵盖开放词汇查询、消解歧义、基于图像的查询、以语言指导的导航以及在三维环境中进行重定位等。我们通过实际应用案例展现了EPG在处理这些任务时的高效表现，凸显其在提升机器人在复杂环境下互动及导航能力方面的潜力。同时，借助定性与定量评测，我们证实了EPG卓越的性能，并揭示其在重定位任务上超越现有方法的实力。这项研究标志着我们在助力机器人高效理解和运作大规模三维空间方面取得的重大进展。

> This paper presents the Embedding Pose Graph (EPG), an innovative method that combines the strengths of foundation models with a simple 3D representation suitable for robotics applications. Addressing the need for efficient spatial understanding in robotics, EPG provides a compact yet powerful approach by attaching foundation model features to the nodes of a pose graph. Unlike traditional methods that rely on bulky data formats like voxel grids or point clouds, EPG is lightweight and scalable. It facilitates a range of robotic tasks, including open-vocabulary querying, disambiguation, image-based querying, language-directed navigation, and re-localization in 3D environments. We showcase the effectiveness of EPG in handling these tasks, demonstrating its capacity to improve how robots interact with and navigate through complex spaces. Through both qualitative and quantitative assessments, we illustrate EPG's strong performance and its ability to outperform existing methods in re-localization. Our work introduces a crucial step forward in enabling robots to efficiently understand and operate within large-scale 3D spaces.

[Arxiv](https://arxiv.org/abs/2403.13777)