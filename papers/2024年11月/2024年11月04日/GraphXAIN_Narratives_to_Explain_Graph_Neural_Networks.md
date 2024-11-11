# GraphXAIN：解释图神经网络的叙述

发布时间：2024年11月04日

`LLM应用` `图神经网络` `可解释人工智能`

> GraphXAIN: Narratives to Explain Graph Neural Networks

# 摘要

> 图神经网络（GNNs）是在图结构数据上进行机器学习的强大技术，但它们带来了可解释性挑战，特别是对于非专家用户。现有的 GNN 解释方法通常产生诸如子图和特征重要性得分等技术输出，这些不容易理解。基于社会科学和其他可解释人工智能（XAI）方法的最新见解，我们提出了 GraphXAIN，这是一种解释 GNN 所做个别预测的自然语言叙述。我们提出了一种与模型无关和解释器无关的 XAI 方法，通过使用大型语言模型（LLMs）并整合图数据、GNN 的个别预测、解释性子图和特征重要性来生成 GraphXAIN，以补充图解释器。我们定义了 XAI 叙述和 XAI 描述，突出了它们的区别，并强调了叙述原则在有效解释中的重要性。通过纳入自然语言叙述，我们的方法支持图从业者和非专家用户，与关于可解释性的社会科学研究保持一致，并增强用户对复杂 GNN 模型的理解和信任。我们在真实世界的图数据集上展示了 GraphXAIN 的能力，说明了与传统的图解释器输出或其他描述性解释方法相比，其生成的叙述如何有助于理解。

> Graph Neural Networks (GNNs) are a powerful technique for machine learning on graph-structured data, yet they pose interpretability challenges, especially for non-expert users. Existing GNN explanation methods often yield technical outputs such as subgraphs and feature importance scores, which are not easily understood. Building on recent insights from social science and other Explainable AI (XAI) methods, we propose GraphXAIN, a natural language narrative that explains individual predictions made by GNNs. We present a model-agnostic and explainer-agnostic XAI approach that complements graph explainers by generating GraphXAINs, using Large Language Models (LLMs) and integrating graph data, individual predictions from GNNs, explanatory subgraphs, and feature importances. We define XAI Narratives and XAI Descriptions, highlighting their distinctions and emphasizing the importance of narrative principles in effective explanations. By incorporating natural language narratives, our approach supports graph practitioners and non-expert users, aligning with social science research on explainability and enhancing user understanding and trust in complex GNN models. We demonstrate GraphXAIN's capabilities on a real-world graph dataset, illustrating how its generated narratives can aid understanding compared to traditional graph explainer outputs or other descriptive explanation methods.

[Arxiv](https://arxiv.org/abs/2411.02540)