# 通过干预数据，大型语言模型（LLM）在时间领域的因果发现能力得到了增强。

发布时间：2024年04月23日

`LLM应用` `IT运维` `人工智能`

> LLM-Enhanced Causal Discovery in Temporal Domain from Interventional Data

# 摘要

> 在IT运维的人工智能应用中，因果发现对于维护图结构和执行根本原因分析等工业任务至关重要。时间因果发现技术通过分析观测数据来直接识别变量间的时间因果关系，对于实际应用中的干预目标依赖性强，且常忽视了现实系统中的文本信息，难以适应真实的工业环境。本文旨在探讨工业场景下的时间因果发现问题，面临两大挑战：一是如何不依赖难以获取的干预目标来发现因果关系；二是如何在复杂的工业环境中利用丰富的文本信息来发现因果关系。为此，我们提出了RealTCD框架，该框架能够在无需干预目标的情况下，借助领域知识来发现时间因果关系。我们首先开发了一种基于分数的时间因果发现方法，通过策略性掩蔽和正则化，在不依赖干预目标的情况下发现因果关系。进一步地，我们利用大型语言模型（LLMs）处理文本并整合领域知识，引入了LLM引导的元初始化，以提取系统中隐藏的文本信息中的元知识，从而提升发现的准确性。我们在模拟和现实世界数据集上进行了广泛的实验，验证了RealTCD框架相较于现有方法在发现时间因果结构上的优势。

> In the field of Artificial Intelligence for Information Technology Operations, causal discovery is pivotal for operation and maintenance of graph construction, facilitating downstream industrial tasks such as root cause analysis. Temporal causal discovery, as an emerging method, aims to identify temporal causal relationships between variables directly from observations by utilizing interventional data. However, existing methods mainly focus on synthetic datasets with heavy reliance on intervention targets and ignore the textual information hidden in real-world systems, failing to conduct causal discovery for real industrial scenarios. To tackle this problem, in this paper we propose to investigate temporal causal discovery in industrial scenarios, which faces two critical challenges: 1) how to discover causal relationships without the interventional targets that are costly to obtain in practice, and 2) how to discover causal relations via leveraging the textual information in systems which can be complex yet abundant in industrial contexts. To address these challenges, we propose the RealTCD framework, which is able to leverage domain knowledge to discover temporal causal relationships without interventional targets. Specifically, we first develop a score-based temporal causal discovery method capable of discovering causal relations for root cause analysis without relying on interventional targets through strategic masking and regularization. Furthermore, by employing Large Language Models (LLMs) to handle texts and integrate domain knowledge, we introduce LLM-guided meta-initialization to extract the meta-knowledge from textual information hidden in systems to boost the quality of discovery. We conduct extensive experiments on simulation and real-world datasets to show the superiority of our proposed RealTCD framework over existing baselines in discovering temporal causal structures.

[Arxiv](https://arxiv.org/abs/2404.14786)