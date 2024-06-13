# OmniCorpus：汇聚百亿图像与文本，打造统一多模态语料库

发布时间：2024年06月12日

`LLM应用

理由：这篇论文介绍了 OmniCorpus 数据集，这是一个大规模的图像与文本交错的数据集，旨在促进多模态情境学习和多模态微调中大型语言模型的性能。该数据集的开发和分析直接应用于多模态大型语言模型的研究和开发，因此属于 LLM 应用类别。论文中提到的数据集的规模、多样性和质量的提升，以及其在多模态模型研究中的潜在应用，都强调了其在实际应用中的重要性。` `多模态学习` `数据集构建`

> OmniCorpus: An Unified Multimodal Corpus of 10 Billion-Level Images Interleaved with Text

# 摘要

> 图像与文本交错的数据集，以自然文档的形式呈现，既符合互联网数据的展示方式，又贴近人类的阅读习惯。研究表明，这种数据集能促进多模态情境学习，并在多模态微调中保持大型语言模型的性能。但目前这类数据集的规模和多样性不足，制约了多模态大型语言模型的发展。本文推出的 OmniCorpus 数据集，规模达 100 亿，通过高效的数据处理，精选出包含 86 亿图像和 16960 亿文本令牌的高质量文档。相较于同类数据集（如 MMC4、OBELICS），OmniCorpus 不仅规模扩大 15 倍，质量依旧上乘，而且来源更为多元，涵盖英语与非英语网站及视频网站，且格式转换灵活，可轻松转变为纯文本或图像-文本对。经过详尽的分析与实验，我们证实了 OmniCorpus 的高质量、实用性和有效性，期待它能为多模态模型研究奠定坚实的数据基础。相关代码和数据已公开于 https://github.com/OpenGVLab/OmniCorpus。

> Image-text interleaved data, consisting of multiple images and texts arranged in a natural document format, aligns with the presentation paradigm of internet data and closely resembles human reading habits. Recent studies have shown that such data aids multimodal in-context learning and maintains the capabilities of large language models during multimodal fine-tuning. However, the limited scale and diversity of current image-text interleaved data restrict the development of multimodal large language models. In this paper, we introduce OmniCorpus, a 10 billion-scale image-text interleaved dataset. Using an efficient data engine, we filter and extract large-scale high-quality documents, which contain 8.6 billion images and 1,696 billion text tokens. Compared to counterparts (e.g., MMC4, OBELICS), our dataset 1) has 15 times larger scales while maintaining good data quality; 2) features more diverse sources, including both English and non-English websites as well as video-centric websites; 3) is more flexible, easily degradable from an image-text interleaved format to pure text corpus and image-text pairs. Through comprehensive analysis and experiments, we validate the quality, usability, and effectiveness of the proposed dataset. We hope this could provide a solid data foundation for future multimodal model research. Code and data are released at https://github.com/OpenGVLab/OmniCorpus.

[Arxiv](https://arxiv.org/abs/2406.08418)