# 利用知识基础的大型语言模型改进科学假设的生成

发布时间：2024年11月04日

`LLM应用` `科学研究`

> Improving Scientific Hypothesis Generation with Knowledge Grounded Large Language Models

# 摘要

> 大型语言模型（LLMs）在从自然语言处理到复杂问题解决任务等各种科学领域中展现出了非凡的能力。它们理解和生成类人文本的能力为推进科学研究开辟了新的可能性，能够实现诸如数据分析、文献综述甚至实验设计等任务。在这种情况下，LLMs 最有前景的应用之一是假设生成，它们可以通过分析现有知识来确定新的研究方向。然而，尽管它们有潜力，LLMs 容易产生“幻觉”，即听起来合理但实际上不正确的输出。这样的问题在要求严格准确性和可验证性的科学领域中带来了重大挑战，可能导致错误或误导性的结论。为了克服这些挑战，我们提出了 KG-CoI（基于知识的思路链），这是一个通过整合来自知识图谱（KGs）的外部结构化知识来增强 LLM 假设生成的新系统。KG-CoI 通过结构化推理过程引导 LLMs，将其输出组织为思路链（CoI），并包括一个由 KG 支持的用于检测幻觉的模块。通过在我们新构建的假设生成数据集上进行实验，我们证明 KG-CoI 不仅提高了 LLM 生成假设的准确性，而且减少了其推理链中的幻觉，突出了其在推进现实世界科学研究方面的有效性。

> Large language models (LLMs) have demonstrated remarkable capabilities in various scientific domains, from natural language processing to complex problem-solving tasks. Their ability to understand and generate human-like text has opened up new possibilities for advancing scientific research, enabling tasks such as data analysis, literature review, and even experimental design. One of the most promising applications of LLMs in this context is hypothesis generation, where they can identify novel research directions by analyzing existing knowledge. However, despite their potential, LLMs are prone to generating ``hallucinations'', outputs that are plausible-sounding but factually incorrect. Such a problem presents significant challenges in scientific fields that demand rigorous accuracy and verifiability, potentially leading to erroneous or misleading conclusions. To overcome these challenges, we propose KG-CoI (Knowledge Grounded Chain of Ideas), a novel system that enhances LLM hypothesis generation by integrating external, structured knowledge from knowledge graphs (KGs). KG-CoI guides LLMs through a structured reasoning process, organizing their output as a chain of ideas (CoI), and includes a KG-supported module for the detection of hallucinations. With experiments on our newly constructed hypothesis generation dataset, we demonstrate that KG-CoI not only improves the accuracy of LLM-generated hypotheses but also reduces the hallucination in their reasoning chains, highlighting its effectiveness in advancing real-world scientific research.

[Arxiv](https://arxiv.org/abs/2411.02382)