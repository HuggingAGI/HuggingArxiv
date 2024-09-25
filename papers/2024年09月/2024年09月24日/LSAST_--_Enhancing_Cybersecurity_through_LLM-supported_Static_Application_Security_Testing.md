# LSAST：借助 LLM 支持的静态应用安全测试提升网络安全

发布时间：2024年09月24日

`LLM应用` `网络安全` `软件开发`

> LSAST -- Enhancing Cybersecurity through LLM-supported Static Application Security Testing

# 摘要

> 在网络安全领域，LLM 正发挥着越来越重要的作用，尤其是在代码分析方面。本文提出了一种创新方法，通过结合传统的 SAST 扫描器与 LLM 技术，打造出 LSAST 这一新型安全测试工具。我们的方法不仅大幅提升了 LLM 在漏洞扫描中的表现，还为该领域设定了新标杆。我们通过对比实验，展示了 LSAST 的高效性，并探讨了 LLM 在漏洞扫描中的局限性，如依赖静态数据集和隐私问题。为此，我们采用开源 LLM 确保隐私，并通过创新的信息收集方法，使 LLM 始终掌握最新漏洞信息。

> In the fast-evolving landscape of cybersecurity, Large Language Models (LLMs) play a pivotal role, continually improving their ability to analyze software code. This paper introduces a novel approach to vulnerability scanning by integrating conservative SAST (Static Application Security Testing) scanners with LLM capabilities, resulting in the creation of LSAST (LLM-supported Static Application Security Testing). Our approach significantly enhances the performance of LLMs in vulnerability scanning, establishing a new standard in this field. We benchmark LSAST's efficiency and compare its results with a state-of-the-art LLM. Additionally, we address the inherent drawbacks of LLMs in vulnerability scanning: their reliance on static training datasets, which leads to the exclusion of the latest vulnerabilities, and the privacy concerns associated with sending code to third-party LLM providers. To mitigate these issues, we utilize an open-source LLM to ensure privacy and employ a novel approach to gather relevant vulnerability information, thereby equipping the LLM with up-to-date knowledge.

[Arxiv](https://arxiv.org/abs/2409.15735)