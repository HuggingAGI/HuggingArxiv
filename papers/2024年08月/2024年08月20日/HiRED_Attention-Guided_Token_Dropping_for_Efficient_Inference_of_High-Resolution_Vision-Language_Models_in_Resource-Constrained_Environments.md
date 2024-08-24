# HiRED 技术通过注意力引导的令牌丢弃，优化了在资源受限环境下高分辨率视觉-语言模型的高效推断。

发布时间：2024年08月20日

`LLM应用` `计算机视觉` `人工智能`

> HiRED: Attention-Guided Token Dropping for Efficient Inference of High-Resolution Vision-Language Models in Resource-Constrained Environments

# 摘要

> 高分辨率视觉-语言模型（VLMs）在多模态任务中通过保留图像细节广泛提升了准确性。然而，这些模型因编码多个图像分区而产生过多视觉标记，这在资源受限环境下处理起来颇具挑战。为此，我们推出了高分辨率早期丢弃（HiRED）方案，该方案在LLM阶段前，依据固定标记预算进行操作，无需额外训练即可与现有高分辨率VLMs无缝集成，保持高准确性。我们巧妙利用视觉编码器初始层的注意力来评估各图像分区的视觉内容，并据此分配标记预算。随后，通过最终层的注意力，在预算内精选各分区的重要视觉标记，其余则被丢弃。实测显示，在NVIDIA TESLA P40 GPU上应用至LLaVA-Next-7B时，采用20%标记预算的HiRED不仅使标记生成吞吐量提升4.7倍，首标记生成延迟缩短15秒，还为单次推理节省了2.3 GB的GPU内存。

> High-resolution Vision-Language Models (VLMs) have been widely used in multimodal tasks to enhance accuracy by preserving detailed image information. However, these models often generate excessive visual tokens due to encoding multiple partitions of the input image. Processing these excessive visual tokens is computationally challenging, especially in resource-constrained environments with commodity GPUs. To support high-resolution images while meeting resource constraints, we propose High-Resolution Early Dropping (HiRED), a token-dropping scheme that operates within a fixed token budget before the Large Language Model (LLM) stage. HiRED can be integrated with existing high-resolution VLMs in a plug-and-play manner, as it requires no additional training while still maintaining superior accuracy. We strategically use the vision encoder's attention in the initial layers to assess the visual content of each image partition and allocate the token budget accordingly. Then, using the attention in the final layer, we select the most important visual tokens from each partition within the allocated budget, dropping the rest. Empirically, when applied to LLaVA-Next-7B on NVIDIA TESLA P40 GPU, HiRED with a 20% token budget increases token generation throughput by 4.7, reduces first-token generation latency by 15 seconds, and saves 2.3 GB of GPU memory for a single inference.

[Arxiv](https://arxiv.org/abs/2408.10945)