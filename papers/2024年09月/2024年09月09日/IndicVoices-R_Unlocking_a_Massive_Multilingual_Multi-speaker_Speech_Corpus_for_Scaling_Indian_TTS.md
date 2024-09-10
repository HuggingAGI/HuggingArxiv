# IndicVoices-R：开启大规模多语言多说话者语音库，助力印度 TTS 扩展

发布时间：2024年09月09日

`LLM应用` `语音技术` `印度语言`

> IndicVoices-R: Unlocking a Massive Multilingual Multi-speaker Speech Corpus for Scaling Indian TTS

# 摘要

> 最新 TTS 技术显示，大规模网络数据训练的模型能生成极自然的语音。但印度语言因缺乏高质量字幕数据而受限。为此，我们改进了低质量环境下的 ASR 数据集，生成高质量 TTS 训练数据。利用英语训练的去噪和语音增强模型，我们创建了 IndicVoices-R (IV-R)，包含 22 种印度语言的 1,704 小时高质量语音，媲美 LJSpeech 等黄金标准。我们还推出了 IV-R 基准，首次评估印度语音的零样本、少样本和多样本泛化能力，涵盖年龄、性别和风格多样性。实验表明，结合 IndicTTS 和 IV-R 数据集微调的模型，零样本泛化能力优于仅用 IndicTTS。此外，我们发现先前模型对印度语音的零样本泛化有限，通过多样化数据集微调得以改善。我们开源所有资源，发布了首个涵盖 22 种官方印度语言的 TTS 模型。

> Recent advancements in text-to-speech (TTS) synthesis show that large-scale models trained with extensive web data produce highly natural-sounding output. However, such data is scarce for Indian languages due to the lack of high-quality, manually subtitled data on platforms like LibriVox or YouTube. To address this gap, we enhance existing large-scale ASR datasets containing natural conversations collected in low-quality environments to generate high-quality TTS training data. Our pipeline leverages the cross-lingual generalization of denoising and speech enhancement models trained on English and applied to Indian languages. This results in IndicVoices-R (IV-R), the largest multilingual Indian TTS dataset derived from an ASR dataset, with 1,704 hours of high-quality speech from 10,496 speakers across 22 Indian languages. IV-R matches the quality of gold-standard TTS datasets like LJSpeech, LibriTTS, and IndicTTS. We also introduce the IV-R Benchmark, the first to assess zero-shot, few-shot, and many-shot speaker generalization capabilities of TTS models on Indian voices, ensuring diversity in age, gender, and style. We demonstrate that fine-tuning an English pre-trained model on a combined dataset of high-quality IndicTTS and our IV-R dataset results in better zero-shot speaker generalization compared to fine-tuning on the IndicTTS dataset alone. Further, our evaluation reveals limited zero-shot generalization for Indian voices in TTS models trained on prior datasets, which we improve by fine-tuning the model on our data containing diverse set of speakers across language families. We open-source all data and code, releasing the first TTS model for all 22 official Indian languages.

[Arxiv](https://arxiv.org/abs/2409.05356)