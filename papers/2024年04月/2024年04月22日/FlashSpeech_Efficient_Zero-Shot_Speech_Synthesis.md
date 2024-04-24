# FlashSpeech：零次拍摄下的高效语音合成

发布时间：2024年04月22日

`分类：LLM应用

这篇论文摘要描述了一种新型的大规模零样本语音合成系统，名为 FlashSpeech。该系统在生成效率和计算资源消耗上有所提升，并且采用了创新的训练策略和韵律生成器模块。这些特点表明，FlashSpeech 是一种基于语言模型的应用，因此将其归类为 LLM应用。` `语音合成` `音频处理`

> FlashSpeech: Efficient Zero-Shot Speech Synthesis

# 摘要

> 近期，大规模零样本语音合成技术因语言模型和扩散模型的突破而显著进步。尽管如此，现有方法在生成效率和计算资源消耗上仍有待提升。本文提出了 FlashSpeech，一种新型的大规模零样本语音合成系统，其推理时间仅为先前技术的 5%。该系统基于潜在一致性模型，并采用了创新的对抗性一致性训练策略，无需预训练的扩散模型即可从头开始训练。此外，新引入的韵律生成器模块丰富了语音的韵律多样性，使得语音节奏更加贴近自然语言。FlashSpeech 能够在保持高音质和高相似度的同时，通过一到两个采样步骤高效完成语音生成。实验结果证明，FlashSpeech 在性能上超越了其他零样本语音合成系统，速度提升高达 20 倍，同时在音质和相似度上保持了同等水平。FlashSpeech 还展示了其在声音转换、语音编辑和多样化语音采样等任务上的高效性和多功能性。相关音频样本可访问 https://flashspeech.github.io/。

> Recent progress in large-scale zero-shot speech synthesis has been significantly advanced by language models and diffusion models. However, the generation process of both methods is slow and computationally intensive. Efficient speech synthesis using a lower computing budget to achieve quality on par with previous work remains a significant challenge. In this paper, we present FlashSpeech, a large-scale zero-shot speech synthesis system with approximately 5\% of the inference time compared with previous work. FlashSpeech is built on the latent consistency model and applies a novel adversarial consistency training approach that can train from scratch without the need for a pre-trained diffusion model as the teacher. Furthermore, a new prosody generator module enhances the diversity of prosody, making the rhythm of the speech sound more natural. The generation processes of FlashSpeech can be achieved efficiently with one or two sampling steps while maintaining high audio quality and high similarity to the audio prompt for zero-shot speech generation. Our experimental results demonstrate the superior performance of FlashSpeech. Notably, FlashSpeech can be about 20 times faster than other zero-shot speech synthesis systems while maintaining comparable performance in terms of voice quality and similarity. Furthermore, FlashSpeech demonstrates its versatility by efficiently performing tasks like voice conversion, speech editing, and diverse speech sampling. Audio samples can be found in https://flashspeech.github.io/.

[Arxiv](https://arxiv.org/abs/2404.14700)