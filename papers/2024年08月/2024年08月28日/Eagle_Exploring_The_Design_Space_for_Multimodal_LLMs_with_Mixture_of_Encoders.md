# Eagle 项目：探索多模态大型语言模型中编码器混合的设计空间

发布时间：2024年08月28日

`LLM应用` `计算机视觉` `人工智能`

> Eagle: Exploring The Design Space for Multimodal LLMs with Mixture of Encoders

# 摘要

> 在多模态大型语言模型（MLLMs）中，准确解读复杂视觉信息的能力至关重要。最新研究表明，提升视觉感知能大幅减少错误，并优化光学字符识别等对分辨率敏感的任务。近期MLLMs通过结合多种视觉编码器取得显著成效，但相关系统比较和深入分析仍显不足。本研究深入探索了MLLMs的设计空间，揭示了共通的设计原则，简化了设计流程。我们发现，将互补视觉编码器的视觉令牌简单串联，效果不亚于复杂混合策略。同时，引入预对齐技术，强化了视觉与语言的融合，提升了模型整体性。Eagle系列模型在MLLM基准测试中表现卓越，代码已开放。详情请访问：https://github.com/NVlabs/Eagle

> The ability to accurately interpret complex visual information is a crucial topic of multimodal large language models (MLLMs). Recent work indicates that enhanced visual perception significantly reduces hallucinations and improves performance on resolution-sensitive tasks, such as optical character recognition and document analysis. A number of recent MLLMs achieve this goal using a mixture of vision encoders. Despite their success, there is a lack of systematic comparisons and detailed ablation studies addressing critical aspects, such as expert selection and the integration of multiple vision experts. This study provides an extensive exploration of the design space for MLLMs using a mixture of vision encoders and resolutions. Our findings reveal several underlying principles common to various existing strategies, leading to a streamlined yet effective design approach. We discover that simply concatenating visual tokens from a set of complementary vision encoders is as effective as more complex mixing architectures or strategies. We additionally introduce Pre-Alignment to bridge the gap between vision-focused encoders and language tokens, enhancing model coherence. The resulting family of MLLMs, Eagle, surpasses other leading open-source models on major MLLM benchmarks. Models and code: https://github.com/NVlabs/Eagle

[Arxiv](https://arxiv.org/abs/2408.15998)