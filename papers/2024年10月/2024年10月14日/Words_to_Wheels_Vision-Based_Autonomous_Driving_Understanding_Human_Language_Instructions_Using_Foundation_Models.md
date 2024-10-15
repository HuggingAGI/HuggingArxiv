# 从文字到车轮：基于视觉的自动驾驶系统，利用基础模型理解人类语言指令

发布时间：2024年10月14日

`LLM应用` `机器人` `自动驾驶`

> Words to Wheels: Vision-Based Autonomous Driving Understanding Human Language Instructions Using Foundation Models

# 摘要

> 本文展示了一种创新的基础模型应用，使配备 RGB-D 摄像头的无人地面车辆 (UGV) 能够根据人类语言指令导航到指定目的地。与传统学习方法不同，该方法无需预先训练，而是利用现有基础模型，从而轻松适应新环境。接收到人类语言指令后，通过大型语言模型 (LLM) 将其转换为“认知路线描述”，即详细的人类语言导航路线。车辆随后将此描述分解为地标和导航操作，并通过地形分割模型 GANav 评估不同区域的高程成本和导航性水平。这些信息被传递给模型预测路径积分 (MPPI) 规划器进行局部路径规划。同时，车辆使用 YOLO-World 和 EfficientViT-SAM 等基础模型搜索目标地标。最终，车辆执行导航命令，成功到达指定目的地。实验证明，该应用在陌生地形或城市等新环境中，能够有效引导 UGV 根据人类语言指令到达目的地。

> This paper introduces an innovative application of foundation models, enabling Unmanned Ground Vehicles (UGVs) equipped with an RGB-D camera to navigate to designated destinations based on human language instructions. Unlike learning-based methods, this approach does not require prior training but instead leverages existing foundation models, thus facilitating generalization to novel environments. Upon receiving human language instructions, these are transformed into a 'cognitive route description' using a large language model (LLM)-a detailed navigation route expressed in human language. The vehicle then decomposes this description into landmarks and navigation maneuvers. The vehicle also determines elevation costs and identifies navigability levels of different regions through a terrain segmentation model, GANav, trained on open datasets. Semantic elevation costs, which take both elevation and navigability levels into account, are estimated and provided to the Model Predictive Path Integral (MPPI) planner, responsible for local path planning. Concurrently, the vehicle searches for target landmarks using foundation models, including YOLO-World and EfficientViT-SAM. Ultimately, the vehicle executes the navigation commands to reach the designated destination, the final landmark. Our experiments demonstrate that this application successfully guides UGVs to their destinations following human language instructions in novel environments, such as unfamiliar terrain or urban settings.

[Arxiv](https://arxiv.org/abs/2410.10577)