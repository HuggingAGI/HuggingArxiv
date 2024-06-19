# 借助 LLM 代理的代码分析，揭示软件系统中那些关键的性能敏感配置。

发布时间：2024年06月18日

`LLM应用

这篇论文介绍了 PerfSense，一个利用大型语言模型（LLMs）来高效识别软件配置错误的轻量级框架。它通过模拟开发者和性能工程师的交互，并使用先进的提示技术（如提示链和检索增强生成）来提高识别准确性。这种方法在实际测试中显示出了较高的准确率，并且减少了人工工作量。因此，这篇论文属于LLM应用分类，因为它展示了如何将LLMs应用于实际的软件性能优化问题中。` `软件开发` `性能优化`

> Identifying Performance-Sensitive Configurations in Software Systems through Code Analysis with LLM Agents

# 摘要

> 配置设置对于定制软件性能至关重要，但错误的配置普遍存在，且识别它们极具挑战性。为此，我们开发了 PerfSense，一个轻量级框架，它利用 LLMs 高效识别关键配置，同时减少开销。通过模拟开发者和性能工程师的交互，PerfSense 使用先进的提示技术，如提示链和检索增强生成，显著提高了识别准确性。在七个 Java 系统的测试中，PerfSense 的平均准确率达到了 64.77%，超越了现有方法。特别是，提示链技术在保持精确度的同时，将召回率提升了 10% 至 30%。此外，对误分类的分析揭示了 LLMs 对需求的误解等问题。PerfSense 不仅大幅减少了人工工作量，还为未来的 LLM 代码分析研究提供了宝贵洞见。

> Configuration settings are essential for tailoring software behavior to meet specific performance requirements. However, incorrect configurations are widespread, and identifying those that impact system performance is challenging due to the vast number and complexity of possible settings. In this work, we present PerfSense, a lightweight framework that leverages Large Language Models (LLMs) to efficiently identify performance-sensitive configurations with minimal overhead. PerfSense employs LLM agents to simulate interactions between developers and performance engineers using advanced prompting techniques such as prompt chaining and retrieval-augmented generation (RAG). Our evaluation of seven open-source Java systems demonstrates that PerfSense achieves an average accuracy of 64.77% in classifying performance-sensitive configurations, outperforming both our LLM baseline (50.36%) and the previous state-of-the-art method (61.75%). Notably, our prompt chaining technique improves recall by 10% to 30% while maintaining similar precision levels. Additionally, a manual analysis of 362 misclassifications reveals common issues, including LLMs' misunderstandings of requirements (26.8%). In summary, PerfSense significantly reduces manual effort in classifying performance-sensitive configurations and offers valuable insights for future LLM-based code analysis research.

![借助 LLM 代理的代码分析，揭示软件系统中那些关键的性能敏感配置。](../../../paper_images/2406.12806/x1.png)

![借助 LLM 代理的代码分析，揭示软件系统中那些关键的性能敏感配置。](../../../paper_images/2406.12806/Performance-Sensitive.png)

[Arxiv](https://arxiv.org/abs/2406.12806)