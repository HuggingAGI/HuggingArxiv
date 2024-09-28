# LLM4Brain：打造专为脑视频理解而生的大型语言模型

发布时间：2024年09月26日

`LLM应用` `神经科学`

> LLM4Brain: Training a Large Language Model for Brain Video Understanding

# 摘要

> 从不同受试者的 fMRI 信号中解码视觉-语义信息面临诸多挑战，如低信噪比和数据有限。本研究利用 LLM 处理多模态信息的优势，提出了一种从视频刺激引发的 fMRI 信号中重建视觉-语义信息的方法。通过微调 fMRI 编码器，将大脑反应转化为与视频对齐的表示，再由 LLM 映射为文本。结合自监督领域适应方法，我们增强了信息与大脑反应的对齐，取得了良好的定量语义指标结果，并与真实信息高度相似。

> Decoding visual-semantic information from brain signals, such as functional MRI (fMRI), across different subjects poses significant challenges, including low signal-to-noise ratio, limited data availability, and cross-subject variability. Recent advancements in large language models (LLMs) show remarkable effectiveness in processing multimodal information. In this study, we introduce an LLM-based approach for reconstructing visual-semantic information from fMRI signals elicited by video stimuli. Specifically, we employ fine-tuning techniques on an fMRI encoder equipped with adaptors to transform brain responses into latent representations aligned with the video stimuli. Subsequently, these representations are mapped to textual modality by LLM. In particular, we integrate self-supervised domain adaptation methods to enhance the alignment between visual-semantic information and brain responses. Our proposed method achieves good results using various quantitative semantic metrics, while yielding similarity with ground-truth information.

[Arxiv](https://arxiv.org/abs/2409.17987)