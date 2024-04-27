# AccidentBlip2：融合多视角 MotionBlip2 技术，精准捕捉事故瞬间

发布时间：2024年04月22日

`Agent` `智能交通` `事故检测`

> AccidentBlip2: Accident Detection With Multi-View MotionBlip2

# 摘要

> 智能车辆在多样化的交通情境中表现出色，但其搭载的复杂传感器和神经网络的推理功能在复杂交通系统中对事故检测的精准度仍有局限。本文介绍了一种全新的基于纯视觉的多模态大型模型——AccidentBlip2，用于事故检测。该方法首先利用 ViT-14g 对多视角图像进行处理，并将处理后的特征送入 Qformer 的交叉注意力层。我们独创的 Motion Qformer 则用时间注意力层替代了 Blip2 中 Qformer 的自注意力层。在推理阶段，前一帧生成的查询会输入到时间注意力层，以实现对时间信息的推理。接着，通过自回归推理分析查询，以判断周围环境是否发生了事故。此外，我们将此方法扩展至多车协作系统，通过在每辆车上部署 Motion Qformer 并输入推理生成的查询至 MLP 进行自回归推理，进一步提升了检测的准确性。这种方法不仅提高了现有视频大型语言模型的检测精度，而且适应于多车系统，更符合智能交通场景的应用需求。

> Intelligent vehicles have demonstrated excellent capabilities in many transportation scenarios, but the complex on-board sensors and the inference capabilities of on-board neural networks limit the accuracy of intelligent vehicles for accident detection in complex transportation systems. In this paper, we present AccidentBlip2, a pure vision-based multimodal large model Blip2 accident detection method. Our method first processes the multi-view through ViT-14g and inputs the multi-view features into the cross attention layer of the Qformer, while our self-designed Motion Qformer replaces the self-attention layer in Blip2's Qformer with the Temporal Attention layer in the In the inference process, the query generated in the previous frame is input into the Temporal Attention layer to realize the inference for temporal information. Then we detect whether there is an accident in the surrounding environment by performing autoregressive inference on the query input to the MLP. We also extend our approach to a multi-vehicle cooperative system by deploying Motion Qformer on each vehicle and simultaneously inputting the inference-generated query into the MLP for autoregressive inference. Our approach detects the accuracy of existing video large language models and also adapts to multi-vehicle systems, making it more applicable to intelligent transportation scenarios.

![AccidentBlip2：融合多视角 MotionBlip2 技术，精准捕捉事故瞬间](../../../paper_images/2404.12149/x1.png)

![AccidentBlip2：融合多视角 MotionBlip2 技术，精准捕捉事故瞬间](../../../paper_images/2404.12149/x2.png)

![AccidentBlip2：融合多视角 MotionBlip2 技术，精准捕捉事故瞬间](../../../paper_images/2404.12149/x3.png)

![AccidentBlip2：融合多视角 MotionBlip2 技术，精准捕捉事故瞬间](../../../paper_images/2404.12149/x4.png)

![AccidentBlip2：融合多视角 MotionBlip2 技术，精准捕捉事故瞬间](../../../paper_images/2404.12149/x5.png)

[Arxiv](https://arxiv.org/abs/2404.12149)