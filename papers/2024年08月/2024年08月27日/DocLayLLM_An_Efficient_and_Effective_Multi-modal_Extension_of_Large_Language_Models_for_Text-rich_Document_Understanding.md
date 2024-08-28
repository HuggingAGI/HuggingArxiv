# DocLayLLM 是一款高效且有效的多模态扩展，专为理解富含文本的文档而设计，依托于大型语言模型。

发布时间：2024年08月27日

`LLM应用` `文档处理` `人工智能`

> DocLayLLM: An Efficient and Effective Multi-modal Extension of Large Language Models for Text-rich Document Understanding

# 摘要

> 文本丰富的文档理解（TDU）涉及分析和理解富含文本的文档。随着大型语言模型（LLM）的迅速进步，其卓越的多功能性和泛化能力使其在TDU领域得到广泛应用。本文介绍的DocLayLLM，是专为TDU设计的高效多模态LLM扩展。通过融合视觉补丁与2D位置信息至LLM，并利用LLM自身编码文档内容，我们不仅充分发挥了LLM的文档理解潜力，还提升了其对OCR信息的感知能力。此外，我们深入探讨了思维链（CoT）的作用，并创新性地引入了CoT预训练与CoT退火技术。DocLayLLM在轻量级训练条件下即能展现卓越性能，凸显其高效与实效。实验结果显示，DocLayLLM不仅超越了依赖OCR的传统方法，也在无OCR的竞争中独占鳌头。

> Text-rich document understanding (TDU) refers to analyzing and comprehending documents containing substantial textual content. With the rapid evolution of large language models (LLMs), they have been widely leveraged for TDU due to their remarkable versatility and generalization. In this paper, we introduce DocLayLLM, an efficient and effective multi-modal extension of LLMs specifically designed for TDU. By integrating visual patch tokens and 2D positional tokens into LLMs and encoding the document content using the LLMs themselves, we fully take advantage of the document comprehension capability of LLMs and enhance their perception of OCR information. We have also deeply considered the role of the chain-of-thought (CoT) and innovatively proposed the techniques of CoT Pre-training and CoT Annealing. Our DocLayLLM can achieve remarkable performances with lightweight training settings, showcasing its efficiency and effectiveness. Experimental results demonstrate that our DocLayLLM surpasses existing OCR-dependent methods and also outperforms OCR-free competitors.

[Arxiv](https://arxiv.org/abs/2408.15045)