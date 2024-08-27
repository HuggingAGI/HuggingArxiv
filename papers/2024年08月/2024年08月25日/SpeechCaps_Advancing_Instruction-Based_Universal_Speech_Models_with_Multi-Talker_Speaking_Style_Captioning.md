# SpeechCaps：借助多说话者风格字幕，推动基于指令的通用语音模型发展

发布时间：2024年08月25日

`LLM应用` `语音处理` `人工智能`

> SpeechCaps: Advancing Instruction-Based Universal Speech Models with Multi-Talker Speaking Style Captioning

# 摘要

> 基于指令的语音处理日益流行。多任务训练虽能提升性能，但收集多样化、大规模数据集成本高昂。为此，我们设计了一个多说话者说话风格标注任务，旨在增强对说话者和韵律信息的理解。利用大型语言模型生成描述后，我们通过预训练和指令调优训练模型。评估结果显示，我们的模型在说话者和情感识别方面表现优异，但在多说话者问答任务中，模型在性别、音高和语速等属性上仍有挑战。相关代码和数据集已公开发布。

> Instruction-based speech processing is becoming popular. Studies show that training with multiple tasks boosts performance, but collecting diverse, large-scale tasks and datasets is expensive. Thus, it is highly desirable to design a fundamental task that benefits other downstream tasks. This paper introduces a multi-talker speaking style captioning task to enhance the understanding of speaker and prosodic information. We used large language models to generate descriptions for multi-talker speech. Then, we trained our model with pre-training on this captioning task followed by instruction tuning. Evaluation on Dynamic-SUPERB shows our model outperforming the baseline pre-trained only on single-talker tasks, particularly in speaker and emotion recognition. Additionally, tests on a multi-talker QA task reveal that current models struggle with attributes such as gender, pitch, and speaking rate. The code and dataset are available at https://github.com/cyhuang-tw/speechcaps.

[Arxiv](https://arxiv.org/abs/2408.13891)