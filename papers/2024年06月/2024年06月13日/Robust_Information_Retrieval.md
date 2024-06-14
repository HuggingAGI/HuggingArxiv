# 稳健的信息检索系统

发布时间：2024年06月13日

`RAG

这篇论文摘要主要讨论了信息检索系统（IR）的鲁棒性，特别是在大语言模型（LLM）背景下的情况。它涵盖了IR鲁棒性的基础知识、分类、对抗性和分布外鲁棒性，以及提升鲁棒性的最新方法。虽然涉及了LLM，但重点在于IR系统的鲁棒性，这与RAG（检索增强生成）领域的研究更为相关，因为RAG关注的是如何通过检索机制增强语言模型的性能和鲁棒性。因此，这篇论文更适合归类到RAG。` `信息检索`

> Robust Information Retrieval

# 摘要

> 信息检索系统的鲁棒性正逐渐成为研究焦点，不仅要求在常规情况下表现卓越，还需能应对各种异常状况。近年来，针对IR系统鲁棒性的研究蓬勃发展，众多学者深入分析并提出多种策略以应对挑战。本教程首先概述了IR鲁棒性的基础知识和分类，随后深入探讨了在特定IR环境下的对抗性和分布外鲁棒性，并回顾了提升鲁棒性的最新方法。最后，我们聚焦于大语言模型背景下的IR鲁棒性，探讨了当前面临的挑战及未来研究的可能方向。本教程旨在提升对IR鲁棒性问题的关注，帮助理解相关文献，并为研究者和实践者降低入门难度。

> Beyond effectiveness, the robustness of an information retrieval (IR) system is increasingly attracting attention. When deployed, a critical technology such as IR should not only deliver strong performance on average but also have the ability to handle a variety of exceptional situations. In recent years, research into the robustness of IR has seen significant growth, with numerous researchers offering extensive analyses and proposing myriad strategies to address robustness challenges. In this tutorial, we first provide background information covering the basics and a taxonomy of robustness in IR. Then, we examine adversarial robustness and out-of-distribution (OOD) robustness within IR-specific contexts, extensively reviewing recent progress in methods to enhance robustness. The tutorial concludes with a discussion on the robustness of IR in the context of large language models (LLMs), highlighting ongoing challenges and promising directions for future research. This tutorial aims to generate broader attention to robustness issues in IR, facilitate an understanding of the relevant literature, and lower the barrier to entry for interested researchers and practitioners.

[Arxiv](https://arxiv.org/abs/2406.08891)