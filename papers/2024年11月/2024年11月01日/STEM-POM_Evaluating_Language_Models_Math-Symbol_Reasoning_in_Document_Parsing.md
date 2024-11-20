# STEM-POM：评估语言模型于文档解析中的数学符号推理能力

发布时间：2024年11月01日

`LLM应用`

> STEM-POM: Evaluating Language Models Math-Symbol Reasoning in Document Parsing

# 摘要

> 大型语言模型（LLMs）的发展促使人们研究如何增强其推理能力，尤其是在富含数学的 STEM 文档方面。尽管 LLMs 能生成方程或解答数学相关的问题，但其在充分理解和阐释长篇且富含数学的文档中的抽象数学符号时，能力仍有限。本文中，我们推出了 STEM-PoM，这是一个用于评估 LLMs 在上下文科学文本中对数学符号推理能力的综合性基准数据集。该数据集源自真实的 ArXiv 文档，包含超 2K 个数学符号，被分为变量、常量、运算符和单位描述符的主要属性，还有变量的标量/向量/矩阵以及常量和运算符的局部/全局/学科特定等额外子属性。我们大量的实验显示，最先进的 LLMs 在上下文学习下平均准确率为 20 - 60%，微调下为 50 - 60%，这揭示出其数学推理能力存在明显差距。STEM-PoM 为未来开发能有力处理数学符号的高级 Math-AI 模型的研究助力。

> Advances in large language models (LLMs) have spurred research into enhancing their reasoning capabilities, particularly in math-rich STEM documents. While LLMs can generate equations or solve math-related queries, their ability to fully understand and interpret abstract mathematical symbols in long, math-rich documents remains limited. In this paper, we introduce STEM-PoM, a comprehensive benchmark dataset designed to evaluate LLMs' reasoning abilities on math symbols within contextual scientific text. The dataset, sourced from real-world ArXiv documents, contains over 2K math symbols classified as main attributes of variables, constants, operators, and unit descriptors, with additional sub-attributes including scalar/vector/matrix for variables and local/global/discipline-specific labels for both constants and operators. Our extensive experiments show that state-of-the-art LLMs achieve an average of 20-60% accuracy under in-context learning and 50-60% accuracy with fine-tuning, revealing a significant gap in their mathematical reasoning capabilities. STEM-PoM fuels future research of developing advanced Math-AI models that can robustly handle math symbols.

[Arxiv](https://arxiv.org/abs/2411.00387)