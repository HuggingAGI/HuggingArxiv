# AVG-LLaVA：一款具备自适应视觉粒度的多模态大型模型

发布时间：2024年09月20日

`LLM应用` `计算机视觉` `人工智能`

> AVG-LLaVA: A Multimodal Large Model with Adaptive Visual Granularity

# 摘要

> 近期，处理高分辨率图像时，主流LMMs常将其分割为多个局部和全局图像，导致大量视觉标记。为此，我们推出AVG-LLaVA，一种能根据输入图像和指令自适应选择视觉粒度的LMM。这不仅减少了视觉标记数量，加快推理速度，还提升了模型整体性能。我们在LLaVA-NeXT基础上引入：(a) 视觉粒度缩放器，含多层池化，获取不同粒度视觉标记；(b) 视觉粒度路由器，含Transformer、MLP和投票层，根据图像和指令选择适当粒度。此外，我们提出RGLF，一种无需额外手动标注数据的新训练范式，使路由器预测粒度与LMM偏好对齐。实验表明，AVG-LLaVA在11个基准测试中表现卓越，视觉标记减少85.3%，推理速度提升2.53倍。

> Recently, when dealing with high-resolution images, dominant LMMs usually divide them into multiple local images and one global image, which will lead to a large number of visual tokens. In this work, we introduce AVG-LLaVA, an LMM that can adaptively select the appropriate visual granularity based on the input image and instruction. This approach not only reduces the number of visual tokens and speeds up inference, but also improves the overall model performance. Specifically, we introduce the following modules based on LLaVA-NeXT: (a) a visual granularity scaler that includes multiple pooling layers to obtain visual tokens with different granularities; (b) a visual granularity router, which includes a Transformer layer, an MLP layer, and a voter layer, used to select the appropriate visual granularity based on the image and instruction. Furthermore, we propose RGLF, a novel training paradigm that aims at aligning the granularity predicted by the router with the preferences of the LMM, without the need for additional manually annotated data. Extensive experiments and analysis show that AVG-LLaVA achieves superior performance across 11 benchmarks, as well as significantly reduces the number of visual tokens and speeds up inference (e.g., an 85.3% reduction in visual tokens and a 2.53$\times$ increase in inference speed on the AI2D benchmark).

[Arxiv](https://arxiv.org/abs/2410.02745)