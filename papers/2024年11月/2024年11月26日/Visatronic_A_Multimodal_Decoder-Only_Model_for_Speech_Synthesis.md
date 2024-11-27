# Visatronic：一种用于语音合成的多模态仅解码器模型

发布时间：2024年11月26日

`LLM应用` `语音生成` `多模态`

> Visatronic: A Multimodal Decoder-Only Model for Speech Synthesis

# 摘要

> 在本文中，我们提出一项新任务——从人物视频及其转录本生成语音（VTTS），以推动多模态语音生成的新技术发展。该任务拓展了从裁剪唇部视频生成语音的范畴，且比从视频和文本生成通用音频片段（如狗叫声）的任务更为复杂。此任务的多语言版本有望为跨语言配音催生新技术。我们还针对该任务推出了一个仅解码器的多模态模型，名为 Visatronic。该模型将视觉、文本和语音直接嵌入到 Transformer 模型的公共子空间，并运用自回归损失来学习基于说话者视频及其语音转录本的离散化梅尔频谱图生成模型。由于将所有模态嵌入到同一公共子空间，Visatronic 相比仅以文本或视频为输入的模型能取得更优成果。而且，与那些依靠唇部检测器和复杂架构来融合模态并取得较好效果的主流方法相比，它为多模态语音生成提供了更简便的途径。鉴于该模型具有足够的灵活性，能够适应不同的输入排序方式，我们仔细探究了不同策略，以更好地明晰将信息传递至生成步骤的最佳方式。为助力 VTTS 的进一步研究，我们将发布（i）代码，（ii）大规模 VoxCeleb2 数据集的清晰转录本，以及（iii）融合客观和主观指标的 VTTS 标准化评估协议。

> In this paper, we propose a new task -- generating speech from videos of people and their transcripts (VTTS) -- to motivate new techniques for multimodal speech generation. This task generalizes the task of generating speech from cropped lip videos, and is also more complicated than the task of generating generic audio clips (e.g., dog barking) from videos and text. Multilingual versions of the task could lead to new techniques for cross-lingual dubbing. We also present a decoder-only multimodal model for this task, which we call Visatronic. This model embeds vision, text and speech directly into the common subspace of a transformer model and uses an autoregressive loss to learn a generative model of discretized mel-spectrograms conditioned on speaker videos and transcripts of their speech. By embedding all modalities into a common subspace, Visatronic can achieve improved results over models that use only text or video as input. Further, it presents a much simpler approach for multimodal speech generation compared to prevailing approaches which rely on lip-detectors and complicated architectures to fuse modalities while producing better results. Since the model is flexible enough to accommodate different ways of ordering inputs as a sequence, we carefully explore different strategies to better understand the best way to propagate information to the generative steps. To facilitate further research on VTTS, we will release (i) our code, (ii) clean transcriptions for the large-scale VoxCeleb2 dataset, and (iii) a standardized evaluation protocol for VTTS incorporating both objective and subjective metrics.

[Arxiv](https://arxiv.org/abs/2411.17690)