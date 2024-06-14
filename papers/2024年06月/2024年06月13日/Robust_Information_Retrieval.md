# 稳健的信息检索系统

发布时间：2024年06月13日

`RAG

理由：这篇论文摘要主要讨论了信息检索（IR）系统的鲁棒性，特别是在大语言模型背景下的情况。它涵盖了鲁棒性的基础、分类、对抗性和分布外鲁棒性，以及提升鲁棒性的方法。这些内容与RAG（Retrieval-Augmented Generation）模型紧密相关，因为RAG模型是一种结合了检索和生成的方法，旨在提高语言模型的鲁棒性和适应性。因此，这篇论文更适合归类于RAG。` `信息检索` `人工智能`

> Robust Information Retrieval

# 摘要

> 信息检索（IR）系统的鲁棒性正成为研究热点，不仅要求平均性能卓越，还需能应对各种异常情况。近年来，IR鲁棒性研究蓬勃发展，众多研究者深入分析并提出多种策略应对挑战。本教程首先概述IR鲁棒性的基础与分类，随后深入探讨对抗性和分布外鲁棒性，并回顾了提升鲁棒性的最新方法。最后，我们聚焦于大语言模型背景下的IR鲁棒性，探讨现有挑战与未来研究方向，旨在提升对IR鲁棒性问题的关注，并帮助研究者和实践者更好地理解和参与这一领域。

> Beyond effectiveness, the robustness of an information retrieval (IR) system is increasingly attracting attention. When deployed, a critical technology such as IR should not only deliver strong performance on average but also have the ability to handle a variety of exceptional situations. In recent years, research into the robustness of IR has seen significant growth, with numerous researchers offering extensive analyses and proposing myriad strategies to address robustness challenges. In this tutorial, we first provide background information covering the basics and a taxonomy of robustness in IR. Then, we examine adversarial robustness and out-of-distribution (OOD) robustness within IR-specific contexts, extensively reviewing recent progress in methods to enhance robustness. The tutorial concludes with a discussion on the robustness of IR in the context of large language models (LLMs), highlighting ongoing challenges and promising directions for future research. This tutorial aims to generate broader attention to robustness issues in IR, facilitate an understanding of the relevant literature, and lower the barrier to entry for interested researchers and practitioners.

[Arxiv](https://arxiv.org/abs/2406.08891)