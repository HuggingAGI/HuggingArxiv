# 交互探索：精挑细选，发现最匹配的上下文学习案例

发布时间：2024年06月16日

`LLM应用

这篇论文主要探讨了如何通过创新的提示工程流程，特别是通过引入“演示笔记本”这一工具，来为每个问题自动定制最佳的情境学习（ICL）演示。这种方法旨在提高大型语言模型（LLMs）在处理不同推理问题时的效能。论文的研究重点在于应用层面的创新，即如何通过技术手段优化LLM的提示工程，以提升其在特定任务上的表现。因此，这篇论文应归类于LLM应用。` `人工智能`

> Demonstration Notebook: Finding the Most Suited In-Context Learning Example from Interactions

# 摘要

> 大型语言模型（LLMs）得益于精妙的提示工程，其中情境学习（ICL）尤为关键。以往的方法虽提供了多种构建ICL演示的途径，却常忽略数据集内部的多样性，对所有推理问题一概而论。我们发现，演示的效用因问题而异。这激发了我们利用提示工程来精选演示的探索。为应对为每个问题自动定制演示的挑战，我们设计了一种创新的提示工程流程，核心是一个名为“演示笔记本”的新工具。它通过整合LLM的历史交互信息，为每个问题精准匹配最佳ICL示例。实验证明，此法在自动演示构建与选择上超越了现有技术，在多个推理测试中刷新了记录。其灵活性在文本摘要和提示压缩任务中也得到了验证。我们还开发了一种严谨的分析手段，揭示了演示的“示范模式”，为理解不同问题类型与演示之间的关系提供了深刻洞见。

> Large language models (LLMs) benefit greatly from prompt engineering, with in-context learning standing as a pivital technique. While former approaches have provided various ways to construct the demonstrations used for in-context learning, they often ignore the inherent heterogeneity within datasets, applying the same demonstrations to all reasoning questions. We observed that the effectiveness of demonstrations varies depending on the specific question. This motivates our exploration of using prompt engineering to select appropriate demonstrations. To address the challenge of automatically creating and choosing demonstrations tailored to each question, we propose a novel prompt engineering workflow built around a novel object called the "demonstration notebook." This notebook helps identify the most suitable in-context learning example for a question by gathering and reusing information from the LLM's past interactions. Our experiments show that this approach outperforms all existing methods for automatic demonstration construction and selection (as far as we know), achieving state-of-the-art results on serveral reasoning benchmarks. The method's versatility is further demonstrated by its success in text summarization and prompt compression tasks. Additionally, we contribute a rigorous analysis method to reveal the "demonstrative regime" of a demonstration, providing valuable insights into how demonstrations relate to different question types within a dataset.

[Arxiv](https://arxiv.org/abs/2406.10878)