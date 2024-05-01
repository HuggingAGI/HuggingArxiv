# 构建了一个框架，旨在通过人类计算游戏来丰富知识图谱，以提升关键生成性AI应用的准确性。

发布时间：2024年04月30日

`分类：LLM应用

这篇论文的摘要主要讨论了如何通过外部知识图谱增强大型语言模型（LLM）的性能，特别是在需要高度可解释性的领域。此外，论文提出了GAME-KG框架，利用众包反馈来调整知识图谱中的显式和隐式联系。这些内容都与LLM的应用相关，因此将这篇论文归类为LLM应用。` `人口贩卖数据分析` `知识图谱`

> A Framework for Leveraging Human Computation Gaming to Enhance Knowledge Graphs for Accuracy Critical Generative AI Applications

# 摘要

> 外部知识图谱能增强大型语言模型，并为人类提供了一个可审查的、基于事实的知识库，这在需要高度可解释性的领域如人口贩卖数据分析中尤为重要。但构建知识图谱并非易事，因为从文档中提取的知识图谱可能仅包含直接陈述的显式联系，而忽略了那些对人类显而易见但未明确表述的隐式联系。为应对这些挑战，本研究提出了GAME-KG框架，即“通过游戏化增强元数据和提升知识图谱”。该框架利用视频游戏中收集的众包反馈，以联合方式调整知识图谱中的显式和隐式联系。通过两个案例展示了GAME-KG的有效性：一是Dark Shadows视频游戏，它收集了关于美国司法部发布的人口贩卖新闻稿中知识图谱的反馈；二是OpenAI的GPT-4模型在基于修改和未修改的知识图谱上回答问题的实验。初步结果显示，GAME-KG不仅能有效提升知识图谱的质量，还能提供一套经过人工验证的、结构化的可解释事实集。

> External knowledge graphs (KGs) can be used to augment large language models (LLMs), while simultaneously providing an explainable knowledge base of facts that can be inspected by a human. This approach may be particularly valuable in domains where explainability is critical, like human trafficking data analysis. However, creating KGs can pose challenges. KGs parsed from documents may comprise explicit connections (those directly stated by a document) but miss implicit connections (those obvious to a human although not directly stated). To address these challenges, this preliminary research introduces the GAME-KG framework, standing for "Gaming for Augmenting Metadata and Enhancing Knowledge Graphs." GAME-KG is a federated approach to modifying explicit as well as implicit connections in KGs by using crowdsourced feedback collected through video games. GAME-KG is shown through two demonstrations: a Unity test scenario from Dark Shadows, a video game that collects feedback on KGs parsed from US Department of Justice (DOJ) Press Releases on human trafficking, and a following experiment where OpenAI's GPT-4 is prompted to answer questions based on a modified and unmodified KG. Initial results suggest that GAME-KG can be an effective framework for enhancing KGs, while simultaneously providing an explainable set of structured facts verified by humans.

[Arxiv](https://arxiv.org/abs/2404.19729)