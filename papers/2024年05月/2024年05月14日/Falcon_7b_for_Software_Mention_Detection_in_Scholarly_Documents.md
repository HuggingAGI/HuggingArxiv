# Falcon 7b：学术文档中软件提及的精准侦测者在学术文档的浩瀚海洋中，Falcon 7b 如同一位敏锐的侦探，专门负责捕捉那些关于软件的微妙提及。它的任务不仅仅是识别，更是深入理解，确保每一条软件相关的信息都能被准确无误地捕获。

发布时间：2024年05月14日

`LLM应用

这篇论文探讨了如何使用大型语言模型（LLM）如Falcon-7b来解决跨学科研究中的一个具体问题，即在学术文本中识别和分类软件提及。它专注于学术出版物软件提及检测（SOMD）的子任务，并通过实验研究了不同的训练策略以提高检测精度。这表明论文是在应用LLM来解决特定的实际问题，因此属于LLM应用类别。` `学术出版` `软件识别`

> Falcon 7b for Software Mention Detection in Scholarly Documents

# 摘要

> 本文探讨了如何利用Falcon-7b模型来应对跨学科研究中软件工具日益融合的挑战，特别是在学术文本中识别和分类软件提及。研究聚焦于学术出版物软件提及检测（SOMD）的子任务I，旨在从学术文献中精准捕捉软件相关信息。通过一系列精心设计的实验，本文尝试了多种训练策略，如双分类器方法、自适应采样和加权损失调整，以期在应对类别不平衡和学术语言的复杂性时提升检测精度。研究发现，精心挑选的标注和自适应采样能够显著提升模型性能，但同时也指出，策略的叠加并不总是带来性能的叠加提升。这项研究不仅展示了大型语言模型在特定任务（如SOMD）上的应用潜力，也强调了针对学术文本分析的特殊挑战，定制化策略的重要性。

> This paper aims to tackle the challenge posed by the increasing integration of software tools in research across various disciplines by investigating the application of Falcon-7b for the detection and classification of software mentions within scholarly texts. Specifically, the study focuses on solving Subtask I of the Software Mention Detection in Scholarly Publications (SOMD), which entails identifying and categorizing software mentions from academic literature. Through comprehensive experimentation, the paper explores different training strategies, including a dual-classifier approach, adaptive sampling, and weighted loss scaling, to enhance detection accuracy while overcoming the complexities of class imbalance and the nuanced syntax of scholarly writing. The findings highlight the benefits of selective labelling and adaptive sampling in improving the model's performance. However, they also indicate that integrating multiple strategies does not necessarily result in cumulative improvements. This research offers insights into the effective application of large language models for specific tasks such as SOMD, underlining the importance of tailored approaches to address the unique challenges presented by academic text analysis.

[Arxiv](https://arxiv.org/abs/2405.08514)