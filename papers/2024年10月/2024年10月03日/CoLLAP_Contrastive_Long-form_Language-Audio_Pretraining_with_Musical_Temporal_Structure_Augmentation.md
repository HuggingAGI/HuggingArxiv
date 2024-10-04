# CoLLAP：结合音乐时间结构增强的对比长篇语言与音频预训练

发布时间：2024年10月03日

`LLM应用` `信息检索`

> CoLLAP: Contrastive Long-form Language-Audio Pretraining with Musical Temporal Structure Augmentation

# 摘要

> 在音频波形表示学习中，时间特征建模至关重要。我们提出的CoLLAP方法，不仅大幅扩展了音频（长达5分钟）和文本（超过250字）的感知窗口，还实现了跨模态和时间动态的对比学习。借助Music-LLMs生成的长篇音乐描述，结合音乐时间结构，我们从AudioSet数据集中提取了51.3K音频-文本对，平均音频长度达288秒。我们创新性地将每首歌曲分割成片段，提取嵌入，融合语言与结构化音频表示，并通过注意力机制捕捉多模态时间相关性，自动优化融合分数，提升对比对齐效果。我们还开发了两种CoLLAP模型变体，分别采用不同类型的骨干语言模型。实验结果表明，在多个长篇音乐-文本检索数据集上，CoLLAP显著提升了检索准确性，并能灵活应用于各种音乐信息检索任务，处理复杂的多模态长篇上下文。

> Modeling temporal characteristics plays a significant role in the representation learning of audio waveform. We propose Contrastive Long-form Language-Audio Pretraining (\textbf{CoLLAP}) to significantly extend the perception window for both the input audio (up to 5 minutes) and the language descriptions (exceeding 250 words), while enabling contrastive learning across modalities and temporal dynamics. Leveraging recent Music-LLMs to generate long-form music captions for full-length songs, augmented with musical temporal structures, we collect 51.3K audio-text pairs derived from the large-scale AudioSet training dataset, where the average audio length reaches 288 seconds. We propose a novel contrastive learning architecture that fuses language representations with structured audio representations by segmenting each song into clips and extracting their embeddings. With an attention mechanism, we capture multimodal temporal correlations, allowing the model to automatically weigh and enhance the final fusion score for improved contrastive alignment. Finally, we develop two variants of the CoLLAP model with different types of backbone language models. Through comprehensive experiments on multiple long-form music-text retrieval datasets, we demonstrate consistent performance improvement in retrieval accuracy compared with baselines. We also show the pretrained CoLLAP models can be transferred to various music information retrieval tasks, with heterogeneous long-form multimodal contexts.

[Arxiv](https://arxiv.org/abs/2410.02271)