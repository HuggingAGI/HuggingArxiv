# 在安全关键场景中，风险感知的车辆轨迹预测

发布时间：2024年07月18日

`Agent` `自动驾驶` `交通安全`

> Risk-Aware Vehicle Trajectory Prediction Under Safety-Critical Scenarios

# 摘要

> 轨迹预测对智能车实现高级自动驾驶至关重要，但现有研究多聚焦于安全场景，忽视了关键安全场景，尤其是即将发生碰撞的情况。为此，本文提出了一种针对关键安全场景的风险感知轨迹预测框架，包含三个核心风险感知组件：风险融合场景编码器、结合端点风险的意图查询和辅助风险预测任务。此外，我们还引入了专门的数据集和评估指标。通过与多个SOTA模型的比较，我们的模型在大多数指标上表现更优，显著提升了自动驾驶车辆在关键安全场景下的避撞能力，从而增强了道路交通的安全性。

> Trajectory prediction is significant for intelligent vehicles to achieve high-level autonomous driving, and a lot of relevant research achievements have been made recently. Despite the rapid development, most existing studies solely focused on normal safe scenarios while largely neglecting safety-critical scenarios, particularly those involving imminent collisions. This oversight may result in autonomous vehicles lacking the essential predictive ability in such situations, posing a significant threat to safety. To tackle these, this paper proposes a risk-aware trajectory prediction framework tailored to safety-critical scenarios. Leveraging distinctive hazardous features, we develop three core risk-aware components. First, we introduce a risk-incorporated scene encoder, which augments conventional encoders with quantitative risk information to achieve risk-aware encoding of hazardous scene contexts. Next, we incorporate endpoint-risk-combined intention queries as prediction priors in the decoder to ensure that the predicted multimodal trajectories cover both various spatial intentions and risk levels. Lastly, an auxiliary risk prediction task is implemented for the ultimate risk-aware prediction. Furthermore, to support model training and performance evaluation, we introduce a safety-critical trajectory prediction dataset and tailored evaluation metrics. We conduct comprehensive evaluations and compare our model with several SOTA models. Results demonstrate the superior performance of our model, with a significant improvement in most metrics. This prediction advancement enables autonomous vehicles to execute correct collision avoidance maneuvers under safety-critical scenarios, eventually enhancing road traffic safety.

[Arxiv](https://arxiv.org/abs/2407.13480)