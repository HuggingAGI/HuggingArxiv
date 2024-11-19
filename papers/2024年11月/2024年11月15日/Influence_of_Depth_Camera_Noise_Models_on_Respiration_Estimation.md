# 深度相机噪声模型对呼吸估算的影响力

发布时间：2024年11月15日

`其他` `生命体征监测`

> Influence of Depth Camera Noise Models on Respiration Estimation

# 摘要

> 深度相机是捕获呼吸率等生命体征的有趣手段。在受控环境下，提取生命体征的方法众多，但要想更灵活地应用于多相机场景等，就需要一个模拟环境来生成足够的数据，以供新算法训练和测试。我们展示了一个 3D 渲染模拟管道的首批成果，其聚焦于不同的噪声模型，旨在利用合成和真实的呼吸信号作基准，生成逼真的基于深度相机的呼吸信号。在这种情况下，多数噪声能被准确建模为高斯噪声，但我们能证明，一旦可用图像分辨率过低，不同噪声模型的差异就会浮现。

> Depth cameras are an interesting modality for capturing vital signs such as respiratory rate. Plenty approaches exist to extract vital signs in a controlled setting, but in order to apply them more flexibly for example in multi-camera settings, a simulated environment is needed to generate enough data for training and testing of new algorithms. We show first results of a 3D-rendering simulation pipeline that focuses on different noise models in order to generate realistic, depth-camera based respiratory signals using both synthetic and real respiratory signals as a baseline. While most noise can be accurately modelled as Gaussian in this context, we can show that as soon as the available image resolution is too low, the differences between different noise models surface.

[Arxiv](https://arxiv.org/abs/2411.10081)