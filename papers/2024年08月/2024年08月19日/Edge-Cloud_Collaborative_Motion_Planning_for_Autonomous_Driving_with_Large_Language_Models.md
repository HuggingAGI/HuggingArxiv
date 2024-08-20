# 自动驾驶中的边缘-云协同运动规划，借助大型语言模型实现。

发布时间：2024年08月19日

`LLM应用` `自动驾驶` `边缘计算`

> Edge-Cloud Collaborative Motion Planning for Autonomous Driving with Large Language Models

# 摘要

> 将 LLM 融入自动驾驶，提升了开放场景下的个性化与适应性。但传统边缘计算在处理复杂驾驶数据时，尤其在实时性与效率上仍显不足。为此，我们推出了 EC-Drive，一款集数据漂移检测于一体的边缘-云协同自动驾驶系统。EC-Drive 通过漂移检测算法，精准上传关键数据至云端由 GPT-4 处理，同时边缘设备上的小型 LLM 高效处理常规数据。此举不仅缩短了延迟，更通过优化通信资源使用提升了系统效率。实验证实，该系统在实际驾驶环境中表现出色，有效展示了边缘-云协作的优势。相关数据与系统演示将在 https://sites.google.com/view/ec-drive 公开。

> Integrating large language models (LLMs) into autonomous driving enhances personalization and adaptability in open-world scenarios. However, traditional edge computing models still face significant challenges in processing complex driving data, particularly regarding real-time performance and system efficiency. To address these challenges, this study introduces EC-Drive, a novel edge-cloud collaborative autonomous driving system with data drift detection capabilities. EC-Drive utilizes drift detection algorithms to selectively upload critical data, including new obstacles and traffic pattern changes, to the cloud for processing by GPT-4, while routine data is efficiently managed by smaller LLMs on edge devices. This approach not only reduces inference latency but also improves system efficiency by optimizing communication resource use. Experimental validation confirms the system's robust processing capabilities and practical applicability in real-world driving conditions, demonstrating the effectiveness of this edge-cloud collaboration framework. Our data and system demonstration will be released at https://sites.google.com/view/ec-drive.

[Arxiv](https://arxiv.org/abs/2408.09972)