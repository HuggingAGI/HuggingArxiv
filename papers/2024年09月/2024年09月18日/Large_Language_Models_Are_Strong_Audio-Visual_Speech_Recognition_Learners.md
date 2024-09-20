# 大型语言模型在音视频语音识别方面表现出色。

发布时间：2024年09月18日

`LLM应用` `语音识别` `视频处理`

> Large Language Models Are Strong Audio-Visual Speech Recognition Learners

# 摘要

> 多模态大型语言模型 (MLLM) 因其卓越的多模态理解能力，近期备受瞩目。例如，在音频和语音领域，通过结合音频和文本标记，LLM 可轻松实现顶尖的 (自动) 语音识别 (ASR) 效果。然而，利用唇部运动信息的视觉和视听语音识别 (VSR/AVSR) 任务却鲜有人问津。为此，我们推出了 Llama-AVSR，一款具备强大视听语音识别能力的 MLLM。它整合预训练的音频和视频编码器，生成模态专属标记，再与文本标记一同输入预训练的 LLM (如 Llama3.1-8B)，以自回归方式输出结果。Llama-AVSR 仅需少量可训练参数，因其仅训练模态专属投影仪和 LoRA 模块，而多模态编码器和 LLM 保持不变。我们在 LRS3 基准测试中验证了其性能，ASR 和 AVSR 任务的 WER 分别达到 0.81% 和 0.77%，刷新了业界纪录。此外，我们还深入探讨了 Llama-AVSR 成功的关键因素：预训练编码器和 LLM 的选择、LoRA 模块的高效融合，以及模态感知压缩率带来的性能与效率最佳平衡。

> Multimodal large language models (MLLMs) have recently become a focal point of research due to their formidable multimodal understanding capabilities. For example, in the audio and speech domains, an LLM can be equipped with (automatic) speech recognition (ASR) abilities by just concatenating the audio tokens, computed with an audio encoder, and the text tokens to achieve state-of-the-art results. On the contrary, tasks like visual and audio-visual speech recognition (VSR/AVSR), which also exploit noise-invariant lip movement information, have received little or no attention. To bridge this gap, we propose Llama-AVSR, a new MLLM with strong audio-visual speech recognition capabilities. It leverages pre-trained audio and video encoders to produce modality-specific tokens which, together with the text tokens, are processed by a pre-trained LLM (e.g., Llama3.1-8B) to yield the resulting response in an auto-regressive fashion. Llama-AVSR requires a small number of trainable parameters as only modality-specific projectors and LoRA modules are trained whereas the multi-modal encoders and LLM are kept frozen. We evaluate our proposed approach on LRS3, the largest public AVSR benchmark, and we achieve new state-of-the-art results for the tasks of ASR and AVSR with a WER of 0.81% and 0.77%, respectively. To bolster our results, we investigate the key factors that underpin the effectiveness of Llama-AVSR: the choice of the pre-trained encoders and LLM, the efficient integration of LoRA modules, and the optimal performance-efficiency trade-off obtained via modality-aware compression rates.

[Arxiv](https://arxiv.org/abs/2409.12319)