# Bench4Merge：一个全面基准，专为微交互车辆在真实密集交通中的合并挑战而设

发布时间：2024年10月21日

`Agent` `自动驾驶` `交通管理`

> Bench4Merge: A Comprehensive Benchmark for Merging in Realistic Dense Traffic with Micro-Interactive Vehicles

# 摘要

> 尽管自动驾驶技术飞速进步，但在密集车流中合并仍是一大难题。虽然已有多种运动规划方法，但评估难度大。现有闭环模拟器多采用基于规则的控制，导致场景单一，难以准确评估高度交互场景中的运动规划能力。传统评估指标也显不足。为此，我们推出了一个闭环评估基准，专门用于评估合并场景中的运动规划能力。该基准通过在大规模数据集上训练的微行为特征，显著提升了场景的复杂性和多样性。我们还利用大型语言模型，重新设计了评估机制，以更全面地评估每辆自主车辆合并到主路的表现。实验证明，该基准具有先进性，能有效评估现有方法并发现常见问题。我们设计的环境和车辆运动规划模型可在 https://anonymous.4open.science/r/Bench4Merge-EB5D 获取。

> While the capabilities of autonomous driving have advanced rapidly, merging into dense traffic remains a significant challenge, many motion planning methods for this scenario have been proposed but it is hard to evaluate them. Most existing closed-loop simulators rely on rule-based controls for other vehicles, which results in a lack of diversity and randomness, thus failing to accurately assess the motion planning capabilities in highly interactive scenarios. Moreover, traditional evaluation metrics are insufficient for comprehensively evaluating the performance of merging in dense traffic. In response, we proposed a closed-loop evaluation benchmark for assessing motion planning capabilities in merging scenarios. Our approach involves other vehicles trained in large scale datasets with micro-behavioral characteristics that significantly enhance the complexity and diversity. Additionally, we have restructured the evaluation mechanism by leveraging large language models to assess each autonomous vehicle merging onto the main road. Extensive experiments have demonstrated the advanced nature of this evaluation benchmark. Through this benchmark, we have obtained an evaluation of existing methods and identified common issues. The environment and vehicle motion planning models we have designed can be accessed at https://anonymous.4open.science/r/Bench4Merge-EB5D

[Arxiv](https://arxiv.org/abs/2410.15912)