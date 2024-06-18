# 交互探索：精挑细选，发现最佳上下文学习案例

发布时间：2024年06月16日

`LLM应用

这篇论文摘要主要讨论了大型语言模型（LLMs）在情境学习中的应用，特别是在提示工程方面的创新。通过提出“演示笔记本”这一工具，该论文展示了如何利用LLM的历史交互信息来智能地选择最适合的情境学习示例，从而提高推理任务的性能。此外，论文还探讨了演示与数据集中各类问题之间的关联，这进一步证明了其在LLM应用领域的贡献。因此，这篇论文最适合归类为LLM应用。` `人工智能`

> Demonstration Notebook: Finding the Most Suited In-Context Learning Example from Interactions

# 摘要

> 大型语言模型（LLMs）得益于提示工程，尤其是情境学习这一核心技术。以往的方法虽提供了多种构建演示的途径，却常忽视数据集内部的多样性，对所有推理问题一概而论。我们发现，演示的有效性因问题而异，这激发了我们利用提示工程来精选演示的探索。为此，我们创新性地提出了一个名为“演示笔记本”的工具，它通过整合LLM的历史交互信息，智能地为每个问题挑选最合适的情境学习示例。实验证明，这一方法在自动演示的构建与选择上超越了现有技术，在多个推理测试中取得了顶尖成绩。此外，该方法在文本摘要和提示压缩任务中也表现出色，展现了其广泛的适用性。我们还开发了一种分析方法，揭示了演示的“示范制度”，深入探讨了演示与数据集中各类问题之间的关联。

> Large language models (LLMs) benefit greatly from prompt engineering, with in-context learning standing as a pivital technique. While former approaches have provided various ways to construct the demonstrations used for in-context learning, they often ignore the inherent heterogeneity within datasets, applying the same demonstrations to all reasoning questions. We observed that the effectiveness of demonstrations varies depending on the specific question. This motivates our exploration of using prompt engineering to select appropriate demonstrations. To address the challenge of automatically creating and choosing demonstrations tailored to each question, we propose a novel prompt engineering workflow built around a novel object called the "demonstration notebook." This notebook helps identify the most suitable in-context learning example for a question by gathering and reusing information from the LLM's past interactions. Our experiments show that this approach outperforms all existing methods for automatic demonstration construction and selection (as far as we know), achieving state-of-the-art results on serveral reasoning benchmarks. The method's versatility is further demonstrated by its success in text summarization and prompt compression tasks. Additionally, we contribute a rigorous analysis method to reveal the "demonstrative regime" of a demonstration, providing valuable insights into how demonstrations relate to different question types within a dataset.

[Arxiv](https://arxiv.org/abs/2406.10878)