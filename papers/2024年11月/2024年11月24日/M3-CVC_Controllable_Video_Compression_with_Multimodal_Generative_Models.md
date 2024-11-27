# M3-CVC：借助多模态生成模型实现可控的视频压缩

发布时间：2024年11月24日

`LLM应用` `视频编码` `多模态模型`

> M3-CVC: Controllable Video Compression with Multimodal Generative Models

# 摘要

> 传统和神经视频编解码器在超低比特率编码场景中，往往在可控性和通用性上存在局限。为了应对这些难题，我们推出了 M3-CVC，这是一个融合多模态生成模型的可控视频压缩框架。此框架运用语义 - 运动复合策略来选取关键帧，从而留存关键信息。针对每个关键帧及其对应的视频片段，基于对话的大型多模态模型（LMM）方法能够提取分层时空细节，实现帧间和帧内的呈现，既提升了视频的保真度，又增强了编码的可解释性。M3-CVC 还采用了基于条件扩散、文本引导的关键帧压缩手段，在帧重建时达到了高保真效果。在解码时，由 LMM 得出的文本描述引导扩散过程，精准还原原始视频的内容。实验结果显示，在超低比特率的情形下，M3-CVC 明显优于当下最先进的 VVC 标准，尤其在保留语义和感知保真度上表现出色。

> Traditional and neural video codecs commonly encounter limitations in controllability and generality under ultra-low-bitrate coding scenarios. To overcome these challenges, we propose M3-CVC, a controllable video compression framework incorporating multimodal generative models. The framework utilizes a semantic-motion composite strategy for keyframe selection to retain critical information. For each keyframe and its corresponding video clip, a dialogue-based large multimodal model (LMM) approach extracts hierarchical spatiotemporal details, enabling both inter-frame and intra-frame representations for improved video fidelity while enhancing encoding interpretability. M3-CVC further employs a conditional diffusion-based, text-guided keyframe compression method, achieving high fidelity in frame reconstruction. During decoding, textual descriptions derived from LMMs guide the diffusion process to restore the original video's content accurately. Experimental results demonstrate that M3-CVC significantly outperforms the state-of-the-art VVC standard in ultra-low bitrate scenarios, particularly in preserving semantic and perceptual fidelity.

[Arxiv](https://arxiv.org/abs/2411.15798)