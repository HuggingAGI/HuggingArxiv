# EEG2TEXT：采用 EEG 预训练和多视角变换技术，实现开放词汇表的 EEG 到文本的转换。

发布时间：2024年05月03日

`分类：Agent` `脑-机接口`

> EEG2TEXT: Open Vocabulary EEG-to-Text Decoding with EEG Pre-Training and Multi-View Transformer

# 摘要

> 探索人脑的奥秘一直是人类数百年来的渴望。脑-机接口（BCI）技术的最近进展，尤其是结合运动想象，已经帮助瘫痪患者恢复了伸手、抓握和行走等基本动作。但是，从大脑信号中解析自然语言仍然是一大难题。脑电图（EEG）作为一种非侵入性技术，通过在头皮上放置电极来捕捉大脑的电活动。尽管先前对EEG至文本转换的研究在有限词汇量上取得了高精度，但在处理更广泛的词汇时仍显不足。我们提出了一种创新的方法——EEG2TEXT，旨在提升开放词汇量EEG至文本转换的准确度。EEG2TEXT通过EEG预训练强化了从EEG信号中提取语义的学习，并引入了多视角变换器来模拟大脑不同区域对EEG信号的处理。实验结果表明，EEG2TEXT的性能超越了当前最先进方法，其BLEU和ROUGE评分的绝对提升高达5%。EEG2TEXT为实现高效能的开放词汇脑到文本转换系统，从而促进沟通提供了巨大的可能性。

> Deciphering the intricacies of the human brain has captivated curiosity for centuries. Recent strides in Brain-Computer Interface (BCI) technology, particularly using motor imagery, have restored motor functions such as reaching, grasping, and walking in paralyzed individuals. However, unraveling natural language from brain signals remains a formidable challenge. Electroencephalography (EEG) is a non-invasive technique used to record electrical activity in the brain by placing electrodes on the scalp. Previous studies of EEG-to-text decoding have achieved high accuracy on small closed vocabularies, but still fall short of high accuracy when dealing with large open vocabularies. We propose a novel method, EEG2TEXT, to improve the accuracy of open vocabulary EEG-to-text decoding. Specifically, EEG2TEXT leverages EEG pre-training to enhance the learning of semantics from EEG signals and proposes a multi-view transformer to model the EEG signal processing by different spatial regions of the brain. Experiments show that EEG2TEXT has superior performance, outperforming the state-of-the-art baseline methods by a large margin of up to 5% in absolute BLEU and ROUGE scores. EEG2TEXT shows great potential for a high-performance open-vocabulary brain-to-text system to facilitate communication.

[Arxiv](https://arxiv.org/abs/2405.02165)