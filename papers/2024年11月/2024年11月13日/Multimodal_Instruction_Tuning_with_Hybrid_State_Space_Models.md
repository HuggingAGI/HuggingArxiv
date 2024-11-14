# 多模态指令调整与混合状态空间模型

发布时间：2024年11月13日

`LLM应用` `多模态` `计算机视觉`

> Multimodal Instruction Tuning with Hybrid State Space Models

# 摘要

> 处理冗长的上下文对于增强多模态大型语言模型（MLLMs）在处理高分辨率图像或高帧率视频等应用中的识别和理解能力至关重要。图像分辨率和帧率的提高由于输入标记数量的增加而大大增加了计算需求。由于自注意力机制相对于序列长度的二次复杂性，这一挑战进一步加剧。大多数先前的工作要么使用长上下文预训练模型，忽略了效率问题，要么试图通过下采样（例如，识别关键图像补丁或帧）来减少上下文长度以降低上下文长度，这可能导致信息丢失。为了在保持 MLLMs 显著有效性的同时规避此问题，我们提出了一种使用混合变压器-MAMBA 模型的新方法，以在多模态应用中有效地处理长上下文。我们的多模态模型可以有效地处理超过 100k 个标记的长上下文输入，在各种基准测试中优于现有模型。值得注意的是，与当前模型相比，我们的模型将高分辨率图像和高帧率视频的推理效率提高了约 4 倍，并且随着图像分辨率或视频帧的增加，效率提升也会增加。此外，我们的模型是第一个在低分辨率图像或低帧率视频上进行训练，同时能够对高分辨率图像和高帧率视频进行推理的模型，为不同场景中的推理提供了灵活性。

> Handling lengthy context is crucial for enhancing the recognition and understanding capabilities of multimodal large language models (MLLMs) in applications such as processing high-resolution images or high frame rate videos. The rise in image resolution and frame rate substantially increases computational demands due to the increased number of input tokens. This challenge is further exacerbated by the quadratic complexity with respect to sequence length of the self-attention mechanism. Most prior works either pre-train models with long contexts, overlooking the efficiency problem, or attempt to reduce the context length via downsampling (e.g., identify the key image patches or frames) to decrease the context length, which may result in information loss. To circumvent this issue while keeping the remarkable effectiveness of MLLMs, we propose a novel approach using a hybrid transformer-MAMBA model to efficiently handle long contexts in multimodal applications. Our multimodal model can effectively process long context input exceeding 100k tokens, outperforming existing models across various benchmarks. Remarkably, our model enhances inference efficiency for high-resolution images and high-frame-rate videos by about 4 times compared to current models, with efficiency gains increasing as image resolution or video frames rise. Furthermore, our model is the first to be trained on low-resolution images or low-frame-rate videos while being capable of inference on high-resolution images and high-frame-rate videos, offering flexibility for inference in diverse scenarios.

[Arxiv](https://arxiv.org/abs/2411.08840)