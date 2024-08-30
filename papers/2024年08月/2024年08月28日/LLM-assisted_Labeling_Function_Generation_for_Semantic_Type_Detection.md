# 借助 LLM 生成标签函数，助力语义类型检测

发布时间：2024年08月28日

`LLM应用` `数据湖` `数据管理`

> LLM-assisted Labeling Function Generation for Semantic Type Detection

# 摘要

> 检测数据湖表中列的语义类型至关重要。然而，由于数据湖的复杂性，人类标注成为语义类型检测的一大难题。本文提出利用程序化弱监督和标注函数来辅助训练数据的标注。面对数据量大且质量低下的挑战，我们采用大型语言模型（LLMs）自动生成标注函数，并设计了多种提示工程策略。实验结果显示，我们的方法在真实网页表数据集上表现良好，为该领域研究提供了新的视角和方向。

> Detecting semantic types of columns in data lake tables is an important application. A key bottleneck in semantic type detection is the availability of human annotation due to the inherent complexity of data lakes. In this paper, we propose using programmatic weak supervision to assist in annotating the training data for semantic type detection by leveraging labeling functions. One challenge in this process is the difficulty of manually writing labeling functions due to the large volume and low quality of the data lake table datasets. To address this issue, we explore employing Large Language Models (LLMs) for labeling function generation and introduce several prompt engineering strategies for this purpose. We conduct experiments on real-world web table datasets. Based on the initial results, we perform extensive analysis and provide empirical insights and future directions for researchers in this field.

[Arxiv](https://arxiv.org/abs/2408.16173)