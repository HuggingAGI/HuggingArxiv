# 本文提出了一种高效的途径，用于探究多语言模型中的跨语言传递效应。

发布时间：2024年03月29日

`LLM理论` `跨语言迁移`

> An Efficient Approach for Studying Cross-Lingual Transfer in Multilingual Language Models

# 摘要

> 多语言预训练模型（MLMs）在零样本跨语言迁移方面的能力已得到广泛认可。然而，在复杂的多语言环境下，正负迁移效应及语言选择的具体影响仍待深入探究。本研究提出了一种新颖的方法，通过专用适配器单元，将任务与语言分离，以研究转移语言对目标语言零样本性能的影响。研究发现，某些语言对其他语言的影响微乎其微，而某些语言，尤其是预训练阶段未出现的语言，对目标语言可能带来极大的益处或损害。有趣的是，我们观察到，对于那些MLMs未曾接触过的语言，几乎总能从任何语言的迁移中获益。此外，我们利用模块化方法有效衡量了负面干扰，并据此对语言进行分类。我们还列出了一系列有望提升目标语言性能的转移-目标语言搭配。相关代码和数据已公开：https://github.com/ffaisal93/neg_inf

> The capacity and effectiveness of pre-trained multilingual models (MLMs) for zero-shot cross-lingual transfer is well established. However, phenomena of positive or negative transfer, and the effect of language choice still need to be fully understood, especially in the complex setting of massively multilingual LMs. We propose an \textit{efficient} method to study transfer language influence in zero-shot performance on another target language. Unlike previous work, our approach disentangles downstream tasks from language, using dedicated adapter units. Our findings suggest that some languages do not largely affect others, while some languages, especially ones unseen during pre-training, can be extremely beneficial or detrimental for different target languages. We find that no transfer language is beneficial for all target languages. We do, curiously, observe languages previously unseen by MLMs consistently benefit from transfer from almost any language. We additionally use our modular approach to quantify negative interference efficiently and categorize languages accordingly. Furthermore, we provide a list of promising transfer-target language configurations that consistently lead to target language performance improvements. Code and data are publicly available: https://github.com/ffaisal93/neg_inf

[Arxiv](https://arxiv.org/abs/2403.20088)