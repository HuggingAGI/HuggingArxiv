# LiMTR：利用多模态特征集成，精准预测多样道路使用者的时间序列运动。

发布时间：2024年10月21日

`其他` `自动驾驶` `交通管理`

> LiMTR: Time Series Motion Prediction for Diverse Road Users through Multimodal Feature Integration

# 摘要

> 在城市或人口密集地区，准确预测道路使用者的行为对自动驾驶车辆的安全操作至关重要。因此，时间序列运动预测研究近年来备受关注，技术不断进步。然而，利用 LiDAR 数据捕捉更细致的局部特征（如人的注视或姿势）的潜力仍待发掘。为此，我们基于 PointNet 架构，融合 LiDAR 局部特征，开发了一种创新的多模态运动预测方法。在 Waymo Open Dataset 上的测试表明，与之前的顶尖技术 MTR 相比，我们的方法在 minADE 和 mAP 上分别提升了 6.20% 和 1.58%。我们已将 LiMTR 模型的代码开源。

> Predicting the behavior of road users accurately is crucial to enable the safe operation of autonomous vehicles in urban or densely populated areas. Therefore, there has been a growing interest in time series motion prediction research, leading to significant advancements in state-of-the-art techniques in recent years. However, the potential of using LiDAR data to capture more detailed local features, such as a person's gaze or posture, remains largely unexplored. To address this, we develop a novel multimodal approach for motion prediction based on the PointNet foundation model architecture, incorporating local LiDAR features. Evaluation on the Waymo Open Dataset shows a performance improvement of 6.20% and 1.58% in minADE and mAP respectively, when integrated and compared with the previous state-of-the-art MTR. We open-source the code of our LiMTR model.

[Arxiv](https://arxiv.org/abs/2410.15819)