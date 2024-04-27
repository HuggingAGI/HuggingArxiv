# AccidentBlip2：运用多视角 MotionBlip2 技术进行事故识别

发布时间：2024年04月22日

`分类：Agent` `智能交通` `事故检测`

> AccidentBlip2: Accident Detection With Multi-View MotionBlip2

# 摘要

> 智能车辆在多元交通情境下展现了非凡性能，但车载传感器的复杂性和神经网络的推理限制了其在复杂系统中的事故检测精度。本文介绍了一种名为 AccidentBlip2 的全新纯视觉多模态大型模型事故检测技术。该技术首先利用 ViT-14g 对多视角图像进行处理，并将处理后的特征送入 Qformer 的交叉注意力层。我们独创的 Motion Qformer 通过时间注意力层取代了 Blip2 中 Qformer 的自注意力层。在推理阶段，前一帧生成的查询被送入时间注意力层，以实现对时间信息的推理。随后，通过自回归推理，我们检测查询输入到 MLP 后周围是否发生了事故。此外，我们将此方法扩展至多车协作系统，通过在每辆车部署 Motion Qformer 并同时将推理生成的查询输入 MLP 进行自回归推理。这种方法不仅提升了现有视频大型语言模型的检测精度，还适应了多车系统，更加契合智能交通的应用需求。

> Intelligent vehicles have demonstrated excellent capabilities in many transportation scenarios, but the complex on-board sensors and the inference capabilities of on-board neural networks limit the accuracy of intelligent vehicles for accident detection in complex transportation systems. In this paper, we present AccidentBlip2, a pure vision-based multimodal large model Blip2 accident detection method. Our method first processes the multi-view through ViT-14g and inputs the multi-view features into the cross attention layer of the Qformer, while our self-designed Motion Qformer replaces the self-attention layer in Blip2's Qformer with the Temporal Attention layer in the In the inference process, the query generated in the previous frame is input into the Temporal Attention layer to realize the inference for temporal information. Then we detect whether there is an accident in the surrounding environment by performing autoregressive inference on the query input to the MLP. We also extend our approach to a multi-vehicle cooperative system by deploying Motion Qformer on each vehicle and simultaneously inputting the inference-generated query into the MLP for autoregressive inference. Our approach detects the accuracy of existing video large language models and also adapts to multi-vehicle systems, making it more applicable to intelligent transportation scenarios.

![AccidentBlip2：运用多视角 MotionBlip2 技术进行事故识别](../../../paper_images/2404.12149/x1.png)

![AccidentBlip2：运用多视角 MotionBlip2 技术进行事故识别](../../../paper_images/2404.12149/x2.png)

![AccidentBlip2：运用多视角 MotionBlip2 技术进行事故识别](../../../paper_images/2404.12149/x3.png)

![AccidentBlip2：运用多视角 MotionBlip2 技术进行事故识别](../../../paper_images/2404.12149/x4.png)

![AccidentBlip2：运用多视角 MotionBlip2 技术进行事故识别](../../../paper_images/2404.12149/x5.png)

[Arxiv](https://arxiv.org/abs/2404.12149)