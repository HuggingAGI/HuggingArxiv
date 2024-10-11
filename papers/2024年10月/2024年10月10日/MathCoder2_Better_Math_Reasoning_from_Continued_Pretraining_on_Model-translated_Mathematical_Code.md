# MathCoder2：通过持续预训练模型翻译的数学代码，提升了数学推理能力

发布时间：2024年10月10日

`LLM应用` `软件开发`

> MathCoder2: Better Math Reasoning from Continued Pretraining on Model-translated Mathematical Code

# 摘要

> 代码因其精确性和准确性，已被证明能有效提升大型语言模型的数学推理能力。然而，以往的连续数学预训练工作多使用面向工程、机器学习等领域的数学包代码，而非直接针对数学推理。本文提出了一种新方法，通过整合网络数据、数学包代码、教科书及合成数据，构建高质量的预训练数据集，并从中提取LaTeX表达式及其条件与结果，生成相应的数学代码，以精确捕捉推理过程。将这些代码与推理步骤配对，结合原始数据，形成19.2B-token的MathCode-Pile预训练语料库，显著提升了基础模型的数学能力，诞生了MathCoder2系列模型。所有代码均已开源，确保研究透明且易于复现。代码详见https://github.com/mathllm/MathCoder2。

> Code has been shown to be effective in enhancing the mathematical reasoning abilities of large language models due to its precision and accuracy. Previous works involving continued mathematical pretraining often include code that utilizes math-related packages, which are primarily designed for fields such as engineering, machine learning, signal processing, or module testing, rather than being directly focused on mathematical reasoning. In this paper, we introduce a novel method for generating mathematical code accompanied with corresponding reasoning steps for continued pretraining. Our approach begins with the construction of a high-quality mathematical continued pretraining dataset by incorporating math-related web data, code using mathematical packages, math textbooks, and synthetic data. Next, we construct reasoning steps by extracting LaTeX expressions, the conditions needed for the expressions, and the results of the expressions from the previously collected dataset. Based on this extracted information, we generate corresponding code to accurately capture the mathematical reasoning process. Appending the generated code to each reasoning step results in data consisting of paired natural language reasoning steps and their corresponding code. Combining this data with the original dataset results in a 19.2B-token high-performing mathematical pretraining corpus, which we name MathCode-Pile. Training several popular base models with this corpus significantly improves their mathematical abilities, leading to the creation of the MathCoder2 family of models. All of our data processing and training code is open-sourced, ensuring full transparency and easy reproducibility of the entire data collection and training pipeline. The code is released at https://github.com/mathllm/MathCoder2 .

[Arxiv](https://arxiv.org/abs/2410.08196)