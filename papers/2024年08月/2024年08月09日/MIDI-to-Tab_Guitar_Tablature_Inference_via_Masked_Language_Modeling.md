# MIDI转吉他谱：利用掩码语言建模技术进行吉他谱推断

发布时间：2024年08月09日

`LLM应用

解释：这篇论文描述了一个基于深度学习的解决方案，使用编码器-解码器Transformer模型在掩码语言建模范式中进行音符分配。这涉及到使用大型语言模型（LLM）来处理和生成吉他谱，因此属于LLM应用的范畴。` `人工智能`

> MIDI-to-Tab: Guitar Tablature Inference via Masked Language Modeling

# 摘要

> 吉他谱通过将音符精确分配到吉他的弦和品位，丰富了传统音乐记谱的结构。然而，从符号音乐表示生成吉他谱是一个复杂问题，涉及在整个作品中推断每个音符的弦和品位分配。由于大多数音高在吉他上可能有多种分配方式，这导致了一个庞大的组合空间，难以通过穷举搜索解决。为此，我们提出了一种基于深度学习的创新解决方案，使用编码器-解码器Transformer模型在掩码语言建模范式中进行音符分配。该模型首先在大型数据集DadaGP上预训练，随后在专业转录的吉他表演集上微调。为了评估吉他谱质量，我们在吉他手中开展了一项用户研究，结果显示我们的系统在可演奏性上显著超越了现有算法。

> Guitar tablatures enrich the structure of traditional music notation by assigning each note to a string and fret of a guitar in a particular tuning, indicating precisely where to play the note on the instrument. The problem of generating tablature from a symbolic music representation involves inferring this string and fret assignment per note across an entire composition or performance. On the guitar, multiple string-fret assignments are possible for most pitches, which leads to a large combinatorial space that prevents exhaustive search approaches. Most modern methods use constraint-based dynamic programming to minimize some cost function (e.g.\ hand position movement). In this work, we introduce a novel deep learning solution to symbolic guitar tablature estimation. We train an encoder-decoder Transformer model in a masked language modeling paradigm to assign notes to strings. The model is first pre-trained on DadaGP, a dataset of over 25K tablatures, and then fine-tuned on a curated set of professionally transcribed guitar performances. Given the subjective nature of assessing tablature quality, we conduct a user study amongst guitarists, wherein we ask participants to rate the playability of multiple versions of tablature for the same four-bar excerpt. The results indicate our system significantly outperforms competing algorithms.

[Arxiv](https://arxiv.org/abs/2408.05024)