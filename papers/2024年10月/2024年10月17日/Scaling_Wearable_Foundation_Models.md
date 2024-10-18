# 扩展可穿戴基础模型

发布时间：2024年10月17日

`其他` `可穿戴设备`

> Scaling Wearable Foundation Models

# 摘要

> 可穿戴传感器因其丰富的健康追踪功能而普及，但由此产生的大量日常数据却难以转化为科学和实用的见解。借鉴生成建模的成功经验，我们探索了传感器基础模型在计算、数据和模型规模上的扩展特性。通过分析来自165,000多人的4000万小时心率、心率变异性等数据，我们构建了LSM，一个涵盖广泛传感器模态的多模态基础模型。研究结果揭示了LSM在时间与传感器模态间插补、内插和外推任务中的扩展规律，并展示了其在运动和活动识别等下游任务中的高效学习能力。

> Wearable sensors have become ubiquitous thanks to a variety of health tracking features. The resulting continuous and longitudinal measurements from everyday life generate large volumes of data; however, making sense of these observations for scientific and actionable insights is non-trivial. Inspired by the empirical success of generative modeling, where large neural networks learn powerful representations from vast amounts of text, image, video, or audio data, we investigate the scaling properties of sensor foundation models across compute, data, and model size. Using a dataset of up to 40 million hours of in-situ heart rate, heart rate variability, electrodermal activity, accelerometer, skin temperature, and altimeter per-minute data from over 165,000 people, we create LSM, a multimodal foundation model built on the largest wearable-signals dataset with the most extensive range of sensor modalities to date. Our results establish the scaling laws of LSM for tasks such as imputation, interpolation and extrapolation, both across time and sensor modalities. Moreover, we highlight how LSM enables sample-efficient downstream learning for tasks like exercise and activity recognition.

[Arxiv](https://arxiv.org/abs/2410.13638)