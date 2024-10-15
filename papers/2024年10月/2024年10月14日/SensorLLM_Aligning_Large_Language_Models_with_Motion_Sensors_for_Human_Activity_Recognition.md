# SensorLLM：融合大型语言模型与运动传感器，助力人类活动识别

发布时间：2024年10月14日

`LLM应用` `可穿戴设备` `人工智能`

> SensorLLM: Aligning Large Language Models with Motion Sensors for Human Activity Recognition

# 摘要

> 我们通过让 LLM 理解人类活动识别等时间序列任务，连接了可穿戴传感器与个性化 AI 助手。尽管 LLM 推理能力强，但用于传感器数据仍未充分探索。挑战包括时间序列数据缺乏语义、计算限制及 LLM 处理数值输入的困难。为此，我们提出 SensorLLM，一个两阶段框架。首先，通过特殊标记和自动生成趋势描述文本，SensorLLM 能捕捉数值变化、通道信息和不同长度的传感器数据，无需人工标注。其次，通过任务感知调优，SensorLLM 在 HAR 分类上表现优异，甚至超越最先进模型。SensorLLM 还能泛化到多样化数据集，成为有效的传感器学习者、推理者和分类器。我们的工作为未来时间序列与文本对齐研究铺平道路，推动传感器数据基础模型的发展。

> In this work, we bridge the gap between wearable sensor technology and personalized AI assistants by enabling Large Language Models (LLMs) to understand time-series tasks like human activity recognition (HAR). Despite the strong reasoning and generalization capabilities of LLMs, leveraging them for sensor data tasks remains largely unexplored. This gap stems from challenges like the lack of semantic context in time-series data, computational limitations, and LLMs' difficulty processing numerical inputs. To address these issues, we introduce SensorLLM, a two-stage framework to unlock LLMs' potential for sensor data tasks. In the Sensor-Language Alignment Stage, we introduce special tokens for each sensor channel and automatically generate trend-descriptive text to align sensor data with textual inputs, enabling SensorLLM to capture numerical changes, channel-specific information, and sensor data of varying lengths-capabilities that existing LLMs typically struggle with, all without the need for human annotations. Next, in Task-Aware Tuning Stage, we refine the model for HAR classification using the frozen LLM and alignment module, achieving performance on par with or surpassing state-of-the-art models. We further demonstrate that SensorLLM evolves into an effective sensor learner, reasoner, and classifier through Sensor-Language Alignment, enabling it to generalize across diverse datasets for HAR tasks. We strongly believe our work lays the stepstone for future time-series and text alignment research, offering a path toward foundation models for sensor data.

[Arxiv](https://arxiv.org/abs/2410.10624)