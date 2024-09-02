# 通过“看、比较、决定”这一流程，我们采用多视角多路径推理方法，有效减轻大型视觉-语言模型中的幻觉问题。

发布时间：2024年08月30日

`LLM应用` `计算机视觉` `人工智能`

> Look, Compare, Decide: Alleviating Hallucination in Large Vision-Language Models via Multi-View Multi-Path Reasoning

# 摘要

> 近期，大型视觉-语言模型（LVLMs）在多模态理解上表现卓越，但仍面临输出与图像内容不符的幻觉问题。为解决这一难题，我们提出了无需额外训练的**MVP**框架，通过**多视图多路径推理**策略，充分利用LVLMs的内在能力，有效减少幻觉现象。我们首先采用多视图信息获取策略，深入挖掘图像信息，增强LVLMs的视觉编码能力。同时，在答案生成阶段，我们发现答案的确定性与幻觉现象紧密相关，因此引入多路径推理机制，量化并整合各路径上的答案确定性，最终精准输出答案。实验证明，MVP框架在四大知名LVLMs中显著降低了幻觉率。源代码已公开，详见：[https://github.com/GasolSun36/MVP](https://github.com/GasolSun36/MVP)。

> Recently, Large Vision-Language Models (LVLMs) have demonstrated impressive capabilities in multi-modal context comprehension. However, they still suffer from hallucination problems referring to generating inconsistent outputs with the image content. To mitigate hallucinations, previous studies mainly focus on retraining LVLMs with custom datasets. Although effective, they inherently come with additional computational costs. In this paper, we propose a training-free framework, \textbf{MVP}, that aims to reduce hallucinations by making the most of the innate capabilities of the LVLMs via \textbf{M}ulti-\textbf{V}iew Multi-\textbf{P}ath Reasoning. Specifically, we first devise a multi-view information-seeking strategy to thoroughly perceive the comprehensive information in the image, which enriches the general global information captured by the original vision encoder in LVLMs. Furthermore, during the answer decoding, we observe that the occurrence of hallucinations has a strong correlation with the certainty of the answer tokens. Thus, we propose multi-path reasoning for each information view to quantify and aggregate the certainty scores for each potential answer among multiple decoding paths and finally decide the output answer. By fully grasping the information in the image and carefully considering the certainty of the potential answers when decoding, our MVP can effectively reduce hallucinations in LVLMs.The extensive experiments verify that our proposed MVP significantly mitigates the hallucination problem across four well-known LVLMs. The source code is available at: \url{https://github.com/GasolSun36/MVP}.

[Arxiv](https://arxiv.org/abs/2408.17150)