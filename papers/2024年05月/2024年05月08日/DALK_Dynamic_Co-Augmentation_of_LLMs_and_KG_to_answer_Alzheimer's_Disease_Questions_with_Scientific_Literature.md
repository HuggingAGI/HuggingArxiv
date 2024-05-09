# DALK：通过动态协同增强 LLMs 与 KG，精准解答阿尔茨海默病相关的科学文献问题。

发布时间：2024年05月08日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在特定领域（如阿尔茨海默病研究）的应用，并提出了一个名为DALK的框架，该框架通过与知识图谱（KG）的协同增强来提升LLMs在专业领域的应用能力。这种方法涉及构建动态知识图谱和采用特定的采样策略及知识检索技术，以增强LLM的推理能力。因此，这篇论文属于LLM应用类别，因为它专注于LLMs在实际问题解决中的应用，特别是在生物医学领域的知识整合和推理增强。` `生物医学` `知识图谱`

> DALK: Dynamic Co-Augmentation of LLMs and KG to answer Alzheimer's Disease Questions with Scientific Literature

# 摘要

> 大型语言模型（LLMs）的最新进展在多个领域展现出潜力，但整合长尾知识的难题仍限制了其在专业领域的应用。本研究提出了DALK（动态LLMs与知识图谱协同增强），旨在解决这一问题，并在阿尔茨海默病（AD）研究这一生物医学重要领域中验证其效能。通过LLM与KG的互补增强框架，我们首先利用LLM构建了一个源自AD研究文献的动态AD知识图谱，随后采用精细的采样策略和创新的自适应知识检索技术，从KG中精选知识以提升LLM的推理能力。在自建的AD问答（ADQA）测试集上的实验结果证实了DALK的有效性。此外，我们还进行了一系列深入分析，为LLM与KG相互增强这一新兴领域提供了宝贵的见解和指导。相关代码和数据将在https://github.com/David-Li0406/DALK公开发布。

> Recent advancements in large language models (LLMs) have achieved promising performances across various applications. Nonetheless, the ongoing challenge of integrating long-tail knowledge continues to impede the seamless adoption of LLMs in specialized domains. In this work, we introduce DALK, a.k.a. Dynamic Co-Augmentation of LLMs and KG, to address this limitation and demonstrate its ability on studying Alzheimer's Disease (AD), a specialized sub-field in biomedicine and a global health priority. With a synergized framework of LLM and KG mutually enhancing each other, we first leverage LLM to construct an evolving AD-specific knowledge graph (KG) sourced from AD-related scientific literature, and then we utilize a coarse-to-fine sampling method with a novel self-aware knowledge retrieval approach to select appropriate knowledge from the KG to augment LLM inference capabilities. The experimental results, conducted on our constructed AD question answering (ADQA) benchmark, underscore the efficacy of DALK. Additionally, we perform a series of detailed analyses that can offer valuable insights and guidelines for the emerging topic of mutually enhancing KG and LLM. We will release the code and data at https://github.com/David-Li0406/DALK.

[Arxiv](https://arxiv.org/abs/2405.04819)