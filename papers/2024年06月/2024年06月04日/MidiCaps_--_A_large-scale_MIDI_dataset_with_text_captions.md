# MidiCaps——集MIDI音乐与文本描述于一体的大型数据宝库

发布时间：2024年06月04日

`LLM应用

这篇论文介绍了一个新的公开大规模文本标注MIDI数据集——MidiCaps，旨在推动大型语言模型（LLMs）与符号音乐的结合研究。该数据集的创建是为了解决文本到MIDI转换模型缺乏的问题，这是由于之前缺乏标注的MIDI数据集。通过提供一个包含详细文本描述的MIDI文件数据集，该论文支持了多模态研究，并为音乐信息检索、理解和跨模态翻译等任务提供了丰富的训练与评估资源。因此，这项工作属于LLM应用类别，因为它专注于利用LLMs在音乐领域的应用，特别是通过创建和使用新的数据集来促进这一领域的研究。`

> MidiCaps -- A large-scale MIDI dataset with text captions

# 摘要

> 文本引导的生成模型日益流行，但文本到MIDI的转换模型尚不存在，主要原因是缺乏标注MIDI数据集。为此，我们推出了首个公开的大规模文本标注MIDI数据集——MidiCaps，旨在推动LLMs与符号音乐的结合研究。MIDI文件因其结构化格式能捕捉音乐细节，被广泛应用于音乐创作与分析。借鉴多领域标注技术的最新进展，我们精心策划了一个包含168,000多个MIDI文件的数据集，每个文件均附有文本描述，涵盖速度、和弦、拍号、乐器、风格及情绪等音乐要素，支持多模态研究。该数据集涵盖多样风格与复杂度，为音乐信息检索、理解和跨模态翻译等任务提供了丰富的训练与评估资源。我们详细统计了数据集，并通过广泛听觉研究确保了标注质量。期待这一资源能激发音乐与自然语言处理交叉领域的研究，促进两者的共同发展。

> Generative models guided by text prompts are increasingly becoming more popular. However, no text-to-MIDI models currently exist, mostly due to the lack of a captioned MIDI dataset. This work aims to enable research that combines LLMs with symbolic music by presenting the first large-scale MIDI dataset with text captions that is openly available: MidiCaps. MIDI (Musical Instrument Digital Interface) files are a widely used format for encoding musical information. Their structured format captures the nuances of musical composition and has practical applications by music producers, composers, musicologists, as well as performers. Inspired by recent advancements in captioning techniques applied to various domains, we present a large-scale curated dataset of over 168k MIDI files accompanied by textual descriptions. Each MIDI caption succinctly describes the musical content, encompassing tempo, chord progression, time signature, instruments present, genre and mood; thereby facilitating multi-modal exploration and analysis. The dataset contains a mix of various genres, styles, and complexities, offering a rich source for training and evaluating models for tasks such as music information retrieval, music understanding and cross-modal translation. We provide detailed statistics about the dataset and have assessed the quality of the captions in an extensive listening study. We anticipate that this resource will stimulate further research in the intersection of music and natural language processing, fostering advancements in both fields.

![MidiCaps——集MIDI音乐与文本描述于一体的大型数据宝库](../../../paper_images/2406.02255/intro_pic.png)

![MidiCaps——集MIDI音乐与文本描述于一体的大型数据宝库](../../../paper_images/2406.02255/p1.png)

![MidiCaps——集MIDI音乐与文本描述于一体的大型数据宝库](../../../paper_images/2406.02255/x1.png)

![MidiCaps——集MIDI音乐与文本描述于一体的大型数据宝库](../../../paper_images/2406.02255/x2.png)

![MidiCaps——集MIDI音乐与文本描述于一体的大型数据宝库](../../../paper_images/2406.02255/x3.png)

![MidiCaps——集MIDI音乐与文本描述于一体的大型数据宝库](../../../paper_images/2406.02255/x4.png)

![MidiCaps——集MIDI音乐与文本描述于一体的大型数据宝库](../../../paper_images/2406.02255/x5.png)

![MidiCaps——集MIDI音乐与文本描述于一体的大型数据宝库](../../../paper_images/2406.02255/x6.png)

[Arxiv](https://arxiv.org/abs/2406.02255)