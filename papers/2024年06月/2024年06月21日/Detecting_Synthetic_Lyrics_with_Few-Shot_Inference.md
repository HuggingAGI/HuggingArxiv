# 通过少量样本推理识别合成歌词

发布时间：2024年06月21日

`LLM应用

理由：这篇论文主要关注的是利用大型语言模型（LLM）生成音乐歌词的检测问题，这是一个具体的应用场景。论文中提到了创建一个高质量的合成歌词数据集，并评估了多种少样本内容检测方法，这些都是为了解决实际应用中的问题，即如何区分人类创作的歌词和机器生成的歌词。此外，论文还强调了进一步探索创意内容检测的必要性，这表明研究的重点在于应用层面，而不是理论探讨或Agent的设计与实现。因此，这篇论文最适合归类为LLM应用。` `内容检测`

> Detecting Synthetic Lyrics with Few-Shot Inference

# 摘要

> 近年来，音乐生成内容风靡一时，大型语言模型巧妙地创作出风格、主题和语言结构各异的人类般歌词。这一技术进步将艺术家从创作的束缚中解放出来，却也带来了版权争议、消费者满意度和内容泛滥的新问题。为此，检测生成歌词的方法应运而生。然而，现有研究尚未深入探讨这一特定领域或创意文本的机器生成内容检测方法和数据集。鉴于此，我们精心打造了首个高质量合成歌词数据集，并对多种少样本内容检测方法进行了全面定量评估，测试其泛化能力，并辅以人类评估。基于LLM2Vec的最佳少样本检测器，在区分人类与机器创作的内容方面，超越了风格和统计方法，这些方法在其他领域已显示出竞争力。它还展现出良好的泛化能力，适用于新艺术家和模型，并能有效识别生成后的改写。本研究强调了进一步探索创意内容检测的必要性，特别是在泛化和可扩展性方面，以应对日益庞大的歌曲库。所有数据集、预处理脚本和代码均在GitHub和Hugging Face上公开，遵循Apache 2.0许可。

> In recent years, generated content in music has gained significant popularity, with large language models being effectively utilized to produce human-like lyrics in various styles, themes, and linguistic structures. This technological advancement supports artists in their creative processes but also raises issues of authorship infringement, consumer satisfaction and content spamming. To address these challenges, methods for detecting generated lyrics are necessary. However, existing works have not yet focused on this specific modality or on creative text in general regarding machine-generated content detection methods and datasets. In response, we have curated the first dataset of high-quality synthetic lyrics and conducted a comprehensive quantitative evaluation of various few-shot content detection approaches, testing their generalization capabilities and complementing this with a human evaluation. Our best few-shot detector, based on LLM2Vec, surpasses stylistic and statistical methods, which are shown competitive in other domains at distinguishing human-written from machine-generated content. It also shows good generalization capabilities to new artists and models, and effectively detects post-generation paraphrasing. This study emphasizes the need for further research on creative content detection, particularly in terms of generalization and scalability with larger song catalogs. All datasets, pre-processing scripts, and code are available publicly on GitHub and Hugging Face under the Apache 2.0 license.

[Arxiv](https://arxiv.org/abs/2406.15231)