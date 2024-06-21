# 语音语言模型的指令数据生成与无监督适应

发布时间：2024年06月18日

`LLM应用

这篇论文探讨了如何利用大型语言模型（LLM）生成合成数据，以训练和评估能够处理文本和语音的多模态大型语言模型。这种方法涉及使用LLM生成文本内容，并结合文本转语音技术生成语音部分，以解决双模态样本稀缺的问题。论文的重点在于应用LLM技术来增强多模态系统的性能，并探索跨模态关系的建模，这直接关联到LLM的实际应用，而非其理论基础或Agent的设计与实现。因此，将其归类为LLM应用是合适的。` `多模态学习` `语音识别`

> Instruction Data Generation and Unsupervised Adaptation for Speech Language Models

# 摘要

> 本文提出了三种创新方法，用于生成合成数据，旨在训练和评估能同时处理文本与语音的多模态大型语言模型。面对双模态样本的稀缺，合成数据生成成为提升系统性能、促进语音与文本间跨模态关系建模的关键策略。我们采用大型语言模型生成文本内容，结合文本转语音技术生成语音部分。这些方法不仅实用，而且有效扩大了模型的训练数据集。实验表明，我们正逐步实现对文本与语音的深度整合理解。此外，我们发现利用未标记语音数据生成的合成样本，其质量可与有转录样本媲美，为模型向更多语言的扩展提供了可能。

> In this paper, we propose three methods for generating synthetic samples to train and evaluate multimodal large language models capable of processing both text and speech inputs. Addressing the scarcity of samples containing both modalities, synthetic data generation emerges as a crucial strategy to enhance the performance of such systems and facilitate the modeling of cross-modal relationships between the speech and text domains. Our process employs large language models to generate textual components and text-to-speech systems to generate speech components. The proposed methods offer a practical and effective means to expand the training dataset for these models. Experimental results show progress in achieving an integrated understanding of text and speech. We also highlight the potential of using unlabeled speech data to generate synthetic samples comparable in quality to those with available transcriptions, enabling the expansion of these models to more languages.

[Arxiv](https://arxiv.org/abs/2406.12946)