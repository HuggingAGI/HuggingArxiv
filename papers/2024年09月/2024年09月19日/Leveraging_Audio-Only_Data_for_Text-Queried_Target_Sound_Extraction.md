# 借助纯音频数据，实现文本查询的目标声音提取

发布时间：2024年09月19日

`LLM应用` `音频处理` `机器学习`

> Leveraging Audio-Only Data for Text-Queried Target Sound Extraction

# 摘要

> 文本查询目标声音提取 (TSE) 旨在从混合音频中提取指定声音源。虽然大规模文本-音频对有助于应对多样提示，但高质量数据稀缺限制了扩展。为此，我们探索如何利用无标题音频数据来扩展 TSE 任务。一种直接方法是使用联合音频-文本嵌入模型（如 CLAP）作为查询编码器，并基于真实音频嵌入训练 TSE 模型。尽管 CLAP 的音频和文本嵌入空间若对齐良好，此法应有效，但实际中嵌入的领域特定信息导致 TSE 模型对音频查询过度拟合。我们研究了多种避免过度拟合的方法，发现简单的嵌入操作（如 dropout）能有效缓解问题。实验证明，使用带 dropout 的纯音频数据与使用文本标题训练效果相当，且纯音频数据能有效提升 TSE 模型性能。

> The goal of text-queried target sound extraction (TSE) is to extract from a mixture a sound source specified with a natural-language caption. While it is preferable to have access to large-scale text-audio pairs to address a variety of text prompts, the limited number of available high-quality text-audio pairs hinders the data scaling. To this end, this work explores how to leverage audio-only data without any captions for the text-queried TSE task to potentially scale up the data amount. A straightforward way to do so is to use a joint audio-text embedding model, such as the contrastive language-audio pre-training (CLAP) model, as a query encoder and train a TSE model using audio embeddings obtained from the ground-truth audio. The TSE model can then accept text queries at inference time by switching to the text encoder. While this approach should work if the audio and text embedding spaces in CLAP were well aligned, in practice, the embeddings have domain-specific information that causes the TSE model to overfit to audio queries. We investigate several methods to avoid overfitting and show that simple embedding-manipulation methods such as dropout can effectively alleviate this issue. Extensive experiments demonstrate that using audio-only data with embedding dropout is as effective as using text captions during training, and audio-only data can be effectively leveraged to improve text-queried TSE models.

[Arxiv](https://arxiv.org/abs/2409.13152)