# Lumina-T2X：借助基于流的巨型扩散变换器，将文本灵活转换为多样化的模态、高分辨率及任意时长，开启文本表达的新纪元。

发布时间：2024年05月09日

`LLM应用

这篇论文介绍了一种名为Lumina-T2X的大型扩散变换器系列，它能够根据文本指令生成多种模态的数据，包括图像、视频、3D物体和音频片段。该模型采用了先进的技术，如RoPE、RMSNorm和流匹配，以提高其稳定性、灵活性和可扩展性。论文强调了该模型在生成超高清图像和长视频方面的能力，并讨论了其在分辨率外推、高分辨率编辑、生成一致的3D视图和合成无缝过渡视频方面的初步能力。这些特性表明，该论文属于大型语言模型（LLM）的应用范畴，因为它展示了LLM在多模态内容生成方面的实际应用。` `多媒体生成` `人工智能`

> Lumina-T2X: Transforming Text into Any Modality, Resolution, and Duration via Flow-based Large Diffusion Transformers

# 摘要

> Sora展示了扩散变换器在生成任意分辨率、宽高比和时长的逼真图像和视频方面的潜力，但实施细节尚不充分。在本报告中，我们推出了Lumina-T2X系列——一系列基于流的、配备零初始化注意力的大型扩散变换器，旨在根据文本指令将噪声转化为图像、视频、多视角3D物体和音频片段。通过引入可学习的占位符，如[nextline]和[nextframe]标记，Lumina-T2X实现了不同模态在各种时空分辨率下的统一表示。这种方法使得在同一框架内训练不同模态成为可能，并允许在推理时灵活生成任意分辨率、宽高比和长度的多模态数据。采用RoPE、RMSNorm和流匹配等先进技术，增强了Flag-DiT的稳定性、灵活性和可扩展性，使Lumina-T2X模型能够扩展到70亿参数，并将上下文窗口扩展到128K标记。这对于使用Lumina-T2I模型生成超高清图像和使用Lumina-T2V模型生成长720p视频尤为有益。值得一提的是，由50亿参数Flag-DiT驱动的Lumina-T2I，其训练计算成本仅为6亿参数的朴素DiT的35%。我们的深入分析揭示了Lumina-T2X在分辨率外推、高分辨率编辑、生成一致的3D视图和合成无缝过渡视频方面的初步能力。我们期待Lumina-T2X的开源将激发生成式AI社区的创造力、透明度和多样性。

> Sora unveils the potential of scaling Diffusion Transformer for generating photorealistic images and videos at arbitrary resolutions, aspect ratios, and durations, yet it still lacks sufficient implementation details. In this technical report, we introduce the Lumina-T2X family - a series of Flow-based Large Diffusion Transformers (Flag-DiT) equipped with zero-initialized attention, as a unified framework designed to transform noise into images, videos, multi-view 3D objects, and audio clips conditioned on text instructions. By tokenizing the latent spatial-temporal space and incorporating learnable placeholders such as [nextline] and [nextframe] tokens, Lumina-T2X seamlessly unifies the representations of different modalities across various spatial-temporal resolutions. This unified approach enables training within a single framework for different modalities and allows for flexible generation of multimodal data at any resolution, aspect ratio, and length during inference. Advanced techniques like RoPE, RMSNorm, and flow matching enhance the stability, flexibility, and scalability of Flag-DiT, enabling models of Lumina-T2X to scale up to 7 billion parameters and extend the context window to 128K tokens. This is particularly beneficial for creating ultra-high-definition images with our Lumina-T2I model and long 720p videos with our Lumina-T2V model. Remarkably, Lumina-T2I, powered by a 5-billion-parameter Flag-DiT, requires only 35% of the training computational costs of a 600-million-parameter naive DiT. Our further comprehensive analysis underscores Lumina-T2X's preliminary capability in resolution extrapolation, high-resolution editing, generating consistent 3D views, and synthesizing videos with seamless transitions. We expect that the open-sourcing of Lumina-T2X will further foster creativity, transparency, and diversity in the generative AI community.

[Arxiv](https://arxiv.org/abs/2405.05945)