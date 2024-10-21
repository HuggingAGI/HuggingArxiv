# AI检测器靠谱吗？一份关于机器生成文本数据集质量的调查报告

发布时间：2024年10月18日

`LLM应用` `信息安全` `人工智能`

> Are AI Detectors Good Enough? A Survey on Quality of Datasets With Machine-Generated Texts

# 摘要

> 自回归 LLM 的迅猛发展提升了生成文本的质量，但也催生了大量检测器。尽管某些检测方法在特定数据集上表现出色，但在实际应用中却往往失效。这不禁让人质疑：高基准分数是否源于评估数据集的低质量？本文强调，评估生成数据的方法需具备稳健性和定性，以抵御未来模型的偏见和低泛化能力。我们系统回顾了 AI 生成内容检测竞赛中的数据集，并提出评估方法。此外，我们探讨了利用高质量生成数据来提升检测模型和数据集的可能性。我们的研究旨在深化对人类与机器文本动态关系的理解，从而在自动化时代维护信息的真实性。

> The rapid development of autoregressive Large Language Models (LLMs) has significantly improved the quality of generated texts, necessitating reliable machine-generated text detectors. A huge number of detectors and collections with AI fragments have emerged, and several detection methods even showed recognition quality up to 99.9% according to the target metrics in such collections. However, the quality of such detectors tends to drop dramatically in the wild, posing a question: Are detectors actually highly trustworthy or do their high benchmark scores come from the poor quality of evaluation datasets? In this paper, we emphasise the need for robust and qualitative methods for evaluating generated data to be secure against bias and low generalising ability of future model. We present a systematic review of datasets from competitions dedicated to AI-generated content detection and propose methods for evaluating the quality of datasets containing AI-generated fragments. In addition, we discuss the possibility of using high-quality generated data to achieve two goals: improving the training of detection models and improving the training datasets themselves. Our contribution aims to facilitate a better understanding of the dynamics between human and machine text, which will ultimately support the integrity of information in an increasingly automated world.

[Arxiv](https://arxiv.org/abs/2410.14677)