# 本文旨在探究大型视觉-语言模型所生成描述的独特性和准确性。

发布时间：2024年04月26日

`分类：LLM应用` `计算机视觉`

> Exploring the Distinctiveness and Fidelity of the Descriptions Generated by Large Vision-Language Models

# 摘要

> 大型视觉-语言模型（LVLMs）因其卓越的视觉与文本数据处理能力而备受瞩目。然而，这些模型在生成精细、详尽的文本描述方面的潜力尚未被充分挖掘。本研究聚焦于“独特性”与“忠实度”，探讨了Open-Flamingo、IDEFICS和MiniGPT-4等模型区分相似物体和精确表述视觉特征的能力。我们引入了文本检索增强分类（TRAC）框架，借助其生成特性，深入探讨了细粒度视觉描述的生成机制。此项研究深化了我们对LVLMs生成质量的认识，尤其是在多模态语言模型的理解上。特别值得一提的是，MiniGPT-4在生成精细描述方面表现更为出色，超越了其他两种模型。相关代码已在\url{https://anonymous.4open.science/r/Explore_FGVDs-E277}提供。

> Large Vision-Language Models (LVLMs) are gaining traction for their remarkable ability to process and integrate visual and textual data. Despite their popularity, the capacity of LVLMs to generate precise, fine-grained textual descriptions has not been fully explored. This study addresses this gap by focusing on \textit{distinctiveness} and \textit{fidelity}, assessing how models like Open-Flamingo, IDEFICS, and MiniGPT-4 can distinguish between similar objects and accurately describe visual features. We proposed the Textual Retrieval-Augmented Classification (TRAC) framework, which, by leveraging its generative capabilities, allows us to delve deeper into analyzing fine-grained visual description generation. This research provides valuable insights into the generation quality of LVLMs, enhancing the understanding of multimodal language models. Notably, MiniGPT-4 stands out for its better ability to generate fine-grained descriptions, outperforming the other two models in this aspect. The code is provided at \url{https://anonymous.4open.science/r/Explore_FGVDs-E277}.

[Arxiv](https://arxiv.org/abs/2404.17534)