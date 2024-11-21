# Stereo-Talker：一种基于先验引导的专家混合的音频驱动 3D 人体合成技术

发布时间：2024年10月31日

`LLM应用` `视频合成` `音频处理`

> Stereo-Talker: Audio-driven 3D Human Synthesis with Prior-Guided Mixture-of-Experts

# 摘要

> 这篇论文为您呈现 Stereo-Talker，这是一个全新的一次性音频驱动的人类视频合成系统，它能生成具备精准唇同步、生动的身体姿态、时间连贯的逼真效果以及连续视角控制的 3D 说话视频。其流程采用了两阶段的方式。在第一阶段，该系统把音频输入转化为高保真的运动序列，涵盖了上半身的手势和面部表情。为使运动更具多样性和真实性，将大型语言模型（LLM）的先验知识与文本对齐的语义音频特征相融合，借助 LLM 的跨模态泛化能力提升运动质量。在第二阶段，我们通过融入先验引导的混合专家（MoE）机制来优化基于扩散的视频生成模型：视图引导的 MoE 聚焦于特定视图的属性，掩码引导的 MoE 则增强了基于区域的渲染稳定性。另外，还设计了一个掩码预测模块，从运动数据中获取人体掩码，提升掩码的稳定性和准确性，并在推理时实现掩码引导。我们还推出了一个全面的人类视频数据集，包含 2,203 个个体，涵盖了各式各样的身体手势和详尽的注释，有利于广泛推广。代码、数据和预训练模型将会为研究用途而发布。

> This paper introduces Stereo-Talker, a novel one-shot audio-driven human video synthesis system that generates 3D talking videos with precise lip synchronization, expressive body gestures, temporally consistent photo-realistic quality, and continuous viewpoint control. The process follows a two-stage approach. In the first stage, the system maps audio input to high-fidelity motion sequences, encompassing upper-body gestures and facial expressions. To enrich motion diversity and authenticity, large language model (LLM) priors are integrated with text-aligned semantic audio features, leveraging LLMs' cross-modal generalization power to enhance motion quality. In the second stage, we improve diffusion-based video generation models by incorporating a prior-guided Mixture-of-Experts (MoE) mechanism: a view-guided MoE focuses on view-specific attributes, while a mask-guided MoE enhances region-based rendering stability. Additionally, a mask prediction module is devised to derive human masks from motion data, enhancing the stability and accuracy of masks and enabling mask guiding during inference. We also introduce a comprehensive human video dataset with 2,203 identities, covering diverse body gestures and detailed annotations, facilitating broad generalization. The code, data, and pre-trained models will be released for research purposes.

[Arxiv](https://arxiv.org/abs/2410.23836)