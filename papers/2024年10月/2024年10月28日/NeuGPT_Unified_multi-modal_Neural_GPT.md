# NeuGPT：统一的多模态神经生成式预训练模型

发布时间：2024年10月28日

`LLM应用` `神经科学` `多模态语言生成`

> NeuGPT: Unified multi-modal Neural GPT

# 摘要

> 这篇论文为您介绍 NeuGPT，这一具有开创性的多模态语言生成模型，旨在整合神经记录研究的碎片化状况。传统上，此领域的研究依信号类型被划分开来，像脑电图（EEG）、脑磁图（MEG）、皮层脑电图（ECoG）、立体定向脑电图（SEEG）、功能性磁共振成像（fMRI）和功能性近红外光谱（fNIRS）等数据都是单独分析的。鉴于交叉融合的巨大潜力尚未开发，以及神经信号在不同实验条件下的适应性，我们着手研发了一个能够与多种模态对接的统一模型。从自然语言处理、计算机视觉和语音处理中预训练大型模型的成功经验中获取灵感，NeuGPT 被构建成能够处理各类神经记录，并能与语音和文本数据互动。我们的模型重点在于脑到文本的解码，将 BLEU-1 上的 SOTA 从 6.94 提升至 12.92，将 ROUGE-1F 上的 SOTA 从 6.93 提升至 13.06。它还能够模拟脑信号，进而成为一种新颖的神经接口。代码可在 \href{https://github.com/NeuSpeech/NeuGPT}{NeuSpeech/NeuGPT (https://github.com/NeuSpeech/NeuGPT) 。}

> This paper introduces NeuGPT, a groundbreaking multi-modal language generation model designed to harmonize the fragmented landscape of neural recording research. Traditionally, studies in the field have been compartmentalized by signal type, with EEG, MEG, ECoG, SEEG, fMRI, and fNIRS data being analyzed in isolation. Recognizing the untapped potential for cross-pollination and the adaptability of neural signals across varying experimental conditions, we set out to develop a unified model capable of interfacing with multiple modalities. Drawing inspiration from the success of pre-trained large models in NLP, computer vision, and speech processing, NeuGPT is architected to process a diverse array of neural recordings and interact with speech and text data. Our model mainly focus on brain-to-text decoding, improving SOTA from 6.94 to 12.92 on BLEU-1 and 6.93 to 13.06 on ROUGE-1F. It can also simulate brain signals, thereby serving as a novel neural interface. Code is available at \href{https://github.com/NeuSpeech/NeuGPT}{NeuSpeech/NeuGPT (https://github.com/NeuSpeech/NeuGPT) .}

[Arxiv](https://arxiv.org/abs/2410.20916)