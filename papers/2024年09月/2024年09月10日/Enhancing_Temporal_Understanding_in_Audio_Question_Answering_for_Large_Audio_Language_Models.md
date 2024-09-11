# 提升大型音频语言模型在音频问答中的时间感知能力

发布时间：2024年09月10日

`LLM应用` `音频处理` `人工智能`

> Enhancing Temporal Understanding in Audio Question Answering for Large Audio Language Models

# 摘要

> 音频问答任务涵盖音频事件分类、描述和开放式推理。随着大型音频语言模型的兴起，这一领域备受瞩目。当前研究主要通过投影模块将音频编码器与文本模型结合，构建LALM。尽管LALM在音频理解上表现优异，但在时间推理上仍有不足，限制了其商业应用和设备部署。本文针对这一问题，首先提出了一种数据增强技术，利用LLM生成可靠的音频时间问题和答案。接着，我们设计了一种持续微调课程学习策略，专注于时间推理，同时保持微调任务的性能。最后，我们开发了一种由LLM辅助的自动化指标，智能评估LALM响应与真实数据的相关性。通过在公开音频基准数据集上使用SOTA LALM，我们验证了这些技术的有效性。

> The Audio Question Answering task includes audio event classification, audio captioning, and open ended reasoning. Recently, Audio Question Answering has garnered attention due to the advent of Large Audio Language Models. Current literature focuses on constructing LALMs by integrating audio encoders with text only Large Language Models through a projection module. While Large Audio Language Models excel in general audio understanding, they are limited in temporal reasoning which may hinder their commercial applications and on device deployment. This paper addresses these challenges and limitations in audio temporal reasoning. First, we introduce a data augmentation technique for generating reliable audio temporal questions and answers using an LLM. Second, we propose a continued finetuning curriculum learning strategy to specialize in temporal reasoning without compromising performance on finetuned tasks. Finally, we develop a reliable and transparent automated metric, assisted by an LLM, to measure the correlation between Large Audio Language Model responses and ground truth data intelligently. We demonstrate the effectiveness of our proposed techniques using SOTA LALMs on public audio benchmark datasets.

[Arxiv](https://arxiv.org/abs/2409.06223)