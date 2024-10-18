# 语言模型如何在线性子空间中比较数值属性，揭示了数值推理的几何学奥秘。

发布时间：2024年10月16日

`LLM理论` `人工智能` `数据分析`

> The Geometry of Numerical Reasoning: Language Models Compare Numeric Properties in Linear Subspaces

# 摘要

> 本文探讨了 LLM 在回答逻辑比较问题时，是否利用了嵌入空间低维子空间中的数值属性。我们通过偏最小二乘回归识别这些子空间，并展示了通过干预这些子空间来操纵隐藏状态，从而改变比较结果的因果关系。实验证实，LLM 确实利用了线性编码的数值信息进行推理。

> This paper investigates whether large language models (LLMs) utilize numerical attributes encoded in a low-dimensional subspace of the embedding space when answering logical comparison questions (e.g., Was Cristiano born before Messi?). We first identified these subspaces using partial least squares regression, which effectively encodes the numerical attributes associated with the entities in comparison prompts. Further, we demonstrate causality by intervening in these subspaces to manipulate hidden states, thereby altering the LLM's comparison outcomes. Experimental results show that our findings hold for different numerical attributes, indicating that LLMs utilize the linearly encoded information for numerical reasoning.

[Arxiv](https://arxiv.org/abs/2410.13194)