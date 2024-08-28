# StyleSpeech：为预训练的可控文本转语音系统提供参数高效的微调方案

发布时间：2024年08月26日

`LLM应用` `语音合成` `虚拟助手`

> StyleSpeech: Parameter-efficient Fine Tuning for Pre-trained Controllable Text-to-Speech

# 摘要

> 本文推出的 StyleSpeech 系统，通过创新的 Style Decorator 结构，结合 Lower Rank Adaptation (LoRA) 技术，显著提升了文本到语音 (TTS) 合成的自然度和准确性。新引入的 LLM-Guided Mean Opinion Score (LLM-MOS) 评估指标，利用大型语言模型，为 TTS 性能提供了客观且稳健的自动评估方法。实验证明，StyleSpeech 在生成高质量语音方面超越了现有顶尖技术，不仅拓展了 TTS 的应用范围，还为交互式虚拟助手、适应性有声书和定制游戏语音等专业领域带来了新的可能性。更多语音样本，请访问 https://style-speech.vercel.app。

> This paper introduces StyleSpeech, a novel Text-to-Speech~(TTS) system that enhances the naturalness and accuracy of synthesized speech. Building upon existing TTS technologies, StyleSpeech incorporates a unique Style Decorator structure that enables deep learning models to simultaneously learn style and phoneme features, improving adaptability and efficiency through the principles of Lower Rank Adaptation~(LoRA). LoRA allows efficient adaptation of style features in pre-trained models. Additionally, we introduce a novel automatic evaluation metric, the LLM-Guided Mean Opinion Score (LLM-MOS), which employs large language models to offer an objective and robust protocol for automatically assessing TTS system performance. Extensive testing on benchmark datasets shows that our approach markedly outperforms existing state-of-the-art baseline methods in producing natural, accurate, and high-quality speech. These advancements not only pushes the boundaries of current TTS system capabilities, but also facilitate the application of TTS system in more dynamic and specialized, such as interactive virtual assistants, adaptive audiobooks, and customized voice for gaming. Speech samples can be found in https://style-speech.vercel.app

[Arxiv](https://arxiv.org/abs/2408.14713)