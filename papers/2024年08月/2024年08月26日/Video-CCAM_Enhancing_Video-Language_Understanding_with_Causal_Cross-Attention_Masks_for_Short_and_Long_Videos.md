# 视频-CCAM 技术通过因果交叉注意力掩码，提升了对短视频和长视频的视频-语言理解能力。

发布时间：2024年08月26日

`LLM应用` `视频处理` `人工智能`

> Video-CCAM: Enhancing Video-Language Understanding with Causal Cross-Attention Masks for Short and Long Videos

# 摘要

> 多模态大型语言模型（MLLMs）在跨领域任务中潜力巨大。Video-MLLMs，特别是处理视频的模型，在视频语言理解领域备受瞩目。然而，长视频的视觉标记多，处理难度大。现有方法或牺牲分辨率，或降低推理速度。为此，我们在视觉编码器与LLM间引入交叉注意力层，并加入因果交叉注意力掩码（CCAMs）以增强时间敏感性。Video-CCAM模型通过两阶段训练：特征对齐与视觉指令调整，基于不同大小的LLMs（4B、9B、14B）开发。该模型在短至长视频中表现卓越，在多个基准测试中名列前茅。即使在仅用图像和16帧视频训练的情况下，Video-CCAM也能适应长视频理解，使用96帧时，在VideoVista和MLVU中分别取得领先成绩。代码已公开在\url{https://github.com/QQ-MM/Video-CCAM}。

> Multi-modal large language models (MLLMs) have demonstrated considerable potential across various downstream tasks that require cross-domain knowledge. MLLMs capable of processing videos, known as Video-MLLMs, have attracted broad interest in video-language understanding. However, videos, especially long videos, contain more visual tokens than images, making them difficult for LLMs to process. Existing works either downsample visual features or extend the LLM context size, risking the loss of high-resolution information or slowing down inference speed. To address these limitations, we apply cross-attention layers in the intermediate projector between the visual encoder and the large language model (LLM). As the naive cross-attention mechanism is insensitive to temporal order, we further introduce causal cross-attention masks (CCAMs) within the cross-attention layers. This Video-MLLM, named Video-CCAM, is trained in a straightforward two-stage fashion: feature alignment and visual instruction tuning. We develop several Video-CCAM models based on LLMs of different sizes (4B, 9B, and 14B). Video-CCAM proves to be a robust Video-MLLM and shows outstanding performance from short videos to long ones. Among standard video benchmarks like MVBench and VideoChatGPT-QA, Video-CCAM shows outstanding performances (1st/2nd/3rd in MVBench and TGIF-QA, 2nd/3rd/4th in MSVD-QA, MSRVTT-QA, and ActivityNet-QA). In benchmarks encompassing long videos, Video-CCAM models can be directly adapted to long video understanding and still achieve exceptional scores despite being trained solely with images and 16-frame videos. Using 96 frames (6$\times$ the training number of frames), Video-CCAM models rank 1st/2nd/3rd in VideoVista and 1st/2nd/4th in MLVU among all open-source Video-MLLMs, respectively. The code is publicly available in \url{https://github.com/QQ-MM/Video-CCAM}.

[Arxiv](https://arxiv.org/abs/2408.14023)