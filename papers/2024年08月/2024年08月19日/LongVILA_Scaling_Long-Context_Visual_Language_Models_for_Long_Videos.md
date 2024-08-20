# LongVILA：扩展长上下文视觉语言模型以适应长视频处理

发布时间：2024年08月19日

`LLM应用` `视频处理` `人工智能`

> LongVILA: Scaling Long-Context Visual Language Models for Long Videos

# 摘要

> 长上下文能力是多模态基础模型的关键。我们推出的LongVILA，是一个全面的长上下文视觉语言模型解决方案，涵盖系统架构、模型训练和数据集构建。在系统层面，我们首创了多模态序列并行（MM-SP）技术，支持大规模长上下文训练与推理，实现256个GPU上2M上下文长度的训练。MM-SP技术高效，比传统环形序列并行快2.1至5.7倍，在纯文本环境下比Megatron-LM快1.1至1.4倍，并完美兼容Hugging Face Transformers。模型训练方面，我们设计了五阶段流程，包括对齐、预训练、上下文扩展及长短联合微调。数据集方面，我们精心打造了大规模视觉语言预训练数据集和长视频指令数据集，以支撑多阶段训练需求。LongVILA的全栈方案将视觉语言模型处理帧数提升128倍，从8帧增至1024帧，显著提升长视频描述得分至3.26，实现1400帧视频中高达99.5%的精准度。LongVILA-8B在VideoMME基准测试中，随着视频帧数增加，长视频处理性能稳步提升。

> Long-context capability is critical for multi-modal foundation models. We introduce LongVILA, a full-stack solution for long-context vision-language models, including system, model training, and dataset development. On the system side, we introduce the first Multi-Modal Sequence Parallelism (MM-SP) system that enables long-context training and inference, enabling 2M context length training on 256 GPUs. MM-SP is also efficient, being 2.1x - 5.7x faster than Ring-Style Sequence Parallelism and 1.1x - 1.4x faster than Megatron-LM in text-only settings. Moreover, it seamlessly integrates with Hugging Face Transformers. For model training, we propose a five-stage pipeline comprising alignment, pre-training, context extension, and long-short joint supervised fine-tuning. Regarding datasets, we meticulously construct large-scale visual language pre-training datasets and long video instruction-following datasets to support our multi-stage training process. The full-stack solution extends the feasible frame number of VILA by a factor of 128 (from 8 to 1024 frames) and improves long video captioning score from 2.00 to 3.26 (1.6x), achieving 99.5% accuracy in 1400-frames video (274k context length) needle in a haystack. LongVILA-8B also demonstrates a consistent improvement in performance on long videos within the VideoMME benchmark as the video frames increase.

[Arxiv](https://arxiv.org/abs/2408.10188)