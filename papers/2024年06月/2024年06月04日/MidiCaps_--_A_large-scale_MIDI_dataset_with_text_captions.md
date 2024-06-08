# MidiCaps —— 大型 MIDI 数据集，附带文本描述

发布时间：2024年06月04日

`LLM应用

这篇论文介绍了首个公开的大规模文本标注MIDI数据集——MidiCaps，旨在推动大型语言模型（LLM）与符号音乐的结合研究。该数据集的创建是为了解决文本到MIDI转换模型发展中的数据集缺乏问题，这是LLM在音乐领域应用的一个具体实例。因此，这篇论文属于LLM应用分类。` `音乐制作`

> MidiCaps -- A large-scale MIDI dataset with text captions

# 摘要

> 随着文本引导的生成模型日益流行，文本到MIDI的转换模型却尚未出现，这主要归咎于缺乏标注MIDI数据集。为此，我们推出了首个公开的大规模文本标注MIDI数据集——MidiCaps，旨在推动大型语言模型与符号音乐的结合研究。MIDI文件作为音乐信息编码的常用格式，其结构化特性不仅捕捉了音乐创作的精妙，也广泛应用于音乐制作、作曲、音乐学及表演领域。借鉴多领域标注技术的最新进展，我们精心策划了一个包含16.8万多个MIDI文件的数据集，每个文件均附有详尽的文本描述，涵盖速度、和弦、拍号、乐器、风格及情绪等音乐要素，极大地便利了多模态研究与分析。该数据集涵盖了多样化的音乐风格与复杂度，为音乐信息检索、理解和跨模态翻译等任务提供了丰富的训练与评估资源。我们对数据集进行了详尽的统计分析，并通过广泛的听觉研究确保了标注质量。我们期待这一资源能够激发音乐与自然语言处理交叉领域的研究热情，促进两大领域的共同发展。

> Generative models guided by text prompts are increasingly becoming more popular. However, no text-to-MIDI models currently exist, mostly due to the lack of a captioned MIDI dataset. This work aims to enable research that combines LLMs with symbolic music by presenting the first large-scale MIDI dataset with text captions that is openly available: MidiCaps. MIDI (Musical Instrument Digital Interface) files are a widely used format for encoding musical information. Their structured format captures the nuances of musical composition and has practical applications by music producers, composers, musicologists, as well as performers. Inspired by recent advancements in captioning techniques applied to various domains, we present a large-scale curated dataset of over 168k MIDI files accompanied by textual descriptions. Each MIDI caption succinctly describes the musical content, encompassing tempo, chord progression, time signature, instruments present, genre and mood; thereby facilitating multi-modal exploration and analysis. The dataset contains a mix of various genres, styles, and complexities, offering a rich source for training and evaluating models for tasks such as music information retrieval, music understanding and cross-modal translation. We provide detailed statistics about the dataset and have assessed the quality of the captions in an extensive listening study. We anticipate that this resource will stimulate further research in the intersection of music and natural language processing, fostering advancements in both fields.

![MidiCaps —— 大型 MIDI 数据集，附带文本描述](../../../paper_images/2406.02255/intro_pic.png)

![MidiCaps —— 大型 MIDI 数据集，附带文本描述](../../../paper_images/2406.02255/p1.png)

![MidiCaps —— 大型 MIDI 数据集，附带文本描述](../../../paper_images/2406.02255/x1.png)

![MidiCaps —— 大型 MIDI 数据集，附带文本描述](../../../paper_images/2406.02255/x2.png)

![MidiCaps —— 大型 MIDI 数据集，附带文本描述](../../../paper_images/2406.02255/x3.png)

![MidiCaps —— 大型 MIDI 数据集，附带文本描述](../../../paper_images/2406.02255/x4.png)

![MidiCaps —— 大型 MIDI 数据集，附带文本描述](../../../paper_images/2406.02255/x5.png)

![MidiCaps —— 大型 MIDI 数据集，附带文本描述](../../../paper_images/2406.02255/x6.png)

[Arxiv](https://arxiv.org/abs/2406.02255)