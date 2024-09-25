# DepMamba：一种用于多模态抑郁症检测的渐进式融合 Mamba 模型

发布时间：2024年09月24日

`LLM应用` `心理健康`

> DepMamba: Progressive Fusion Mamba for Multimodal Depression Detection

# 摘要

> 抑郁症是全球数百万人的心头之患。现有多模态方法虽有潜力，但受限于长时间建模效率低下和模态间与模态内融合不理想。为此，我们推出了 DepMamba，一种音频-视觉渐进融合模型，专为抑郁症检测设计。DepMamba 通过分层建模和渐进融合两大核心技术，既提取长时间序列中的局部到全局特征，又实现模态间与模态内的信息高效融合。实验证明，DepMamba 在抑郁症检测方面超越了现有顶尖方法。代码已公开，详见 https://github.com/Jiaxin-Ye/DepMamba。

> Depression is a common mental disorder that affects millions of people worldwide. Although promising, current multimodal methods hinge on aligned or aggregated multimodal fusion, suffering two significant limitations: (i) inefficient long-range temporal modeling, and (ii) sub-optimal multimodal fusion between intermodal fusion and intramodal processing. In this paper, we propose an audio-visual progressive fusion Mamba for multimodal depression detection, termed DepMamba. DepMamba features two core designs: hierarchical contextual modeling and progressive multimodal fusion. On the one hand, hierarchical modeling introduces convolution neural networks and Mamba to extract the local-to-global features within long-range sequences. On the other hand, the progressive fusion first presents a multimodal collaborative State Space Model (SSM) extracting intermodal and intramodal information for each modality, and then utilizes a multimodal enhanced SSM for modality cohesion. Extensive experimental results on two large-scale depression datasets demonstrate the superior performance of our DepMamba over existing state-of-the-art methods. Code is available at https://github.com/Jiaxin-Ye/DepMamba.

[Arxiv](https://arxiv.org/abs/2409.15936)