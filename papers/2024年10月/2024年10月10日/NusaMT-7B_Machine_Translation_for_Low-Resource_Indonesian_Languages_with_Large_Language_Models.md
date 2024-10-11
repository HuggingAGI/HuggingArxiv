# NusaMT-7B：借助大型语言模型，为资源匮乏的印尼语提供机器翻译解决方案。

发布时间：2024年10月10日

`LLM应用` `语言保护` `跨文化交流`

> NusaMT-7B: Machine Translation for Low-Resource Indonesian Languages with Large Language Models

# 摘要

> 大型语言模型 (LLM) 在高资源语言的翻译任务中表现出色，但在低资源语言中，由于平行语料库和单语语料库的稀缺以及噪音的存在，其性能受限。因此，这些 LLM 在对齐方面存在困难，并且在这些情况下落后于最先进的 (SoTA) 神经机器翻译 (NMT) 模型。本文介绍了 NusaMT-7B，一个基于 LLM 的低资源印度尼西亚语言机器翻译模型，从巴厘语和米南卡保语开始。我们利用预训练的 LLaMA2-7B，结合单语数据的继续预训练、监督微调 (SFT)、自我学习和基于 LLM 的数据清洁器来减少平行句子中的噪音。在 FLORES-200 多语言翻译基准测试中，NusaMT-7B 在翻译成巴厘语和米南卡保语时，在 spBLEU 指标上比 SoTA 模型高出最多 +6.69 spBLEU，但在翻译成高资源语言时表现不佳，最多落后 -3.38 spBLEU。我们的研究结果表明，微调的 LLM 可以显著提高低资源语言的翻译质量，有助于语言保护和跨文化交流。

> Large Language Models (LLMs) have demonstrated exceptional promise in translation tasks for high-resource languages. However, their performance in low-resource languages is limited by the scarcity of both parallel and monolingual corpora, as well as the presence of noise. Consequently, such LLMs suffer with alignment and have lagged behind State-of-The-Art (SoTA) neural machine translation (NMT) models in these settings. This paper introduces NusaMT-7B, an LLM-based machine translation model for low-resource Indonesian languages, starting with Balinese and Minangkabau. Leveraging the pretrained LLaMA2-7B, our approach integrates continued pre-training on monolingual data, Supervised Fine-Tuning (SFT), self-learning, and an LLM-based data cleaner to reduce noise in parallel sentences. In the FLORES-200 multilingual translation benchmark, NusaMT-7B outperforms SoTA models in the spBLEU metric by up to +6.69 spBLEU in translations into Balinese and Minangkabau, but underperforms by up to -3.38 spBLEU in translations into higher-resource languages. Our results show that fine-tuned LLMs can enhance translation quality for low-resource languages, aiding in linguistic preservation and cross-cultural communication.

[Arxiv](https://arxiv.org/abs/2410.07830)