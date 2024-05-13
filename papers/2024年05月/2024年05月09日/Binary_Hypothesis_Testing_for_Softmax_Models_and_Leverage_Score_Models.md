# Softmax模型与杠杆分数模型的二元假设检验探索

发布时间：2024年05月09日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）中的注意力机制，特别是softmax模型在二元假设检验中的应用。它研究了如何通过查询次数来确定未知模型属于两个已知模型中的哪一个，并分析了查询次数与模型参数间距离的关系。此外，论文还将softmax模型与杠杆分数模型进行了对比。这些内容属于对LLMs内部机制的理论分析，因此归类为LLM理论。` `机器学习`

> Binary Hypothesis Testing for Softmax Models and Leverage Score Models

# 摘要

> 在机器学习领域，softmax分布广泛应用于大型语言模型（LLMs）的注意力单元中。我们将注意力机制简化为softmax模型，该模型接收向量输入并输出基于该输入的softmax分布。本研究探讨了在softmax模型背景下进行二元假设检验的问题，即如何通过查询次数来确定未知模型属于两个已知模型中的哪一个。研究表明，所需的查询次数与模型参数间的距离$ε$的平方成反比。此外，我们将softmax模型与杠杆分数模型进行了对比，后者是线性代数和图论算法设计中的关键工具。杠杆分数模型同样接收向量输入，并输出依赖于输入的分布。对于杠杆分数模型，我们也得到了关于二元假设检验问题的相似结论。

> Softmax distributions are widely used in machine learning, including Large Language Models (LLMs) where the attention unit uses softmax distributions. We abstract the attention unit as the softmax model, where given a vector input, the model produces an output drawn from the softmax distribution (which depends on the vector input). We consider the fundamental problem of binary hypothesis testing in the setting of softmax models. That is, given an unknown softmax model, which is known to be one of the two given softmax models, how many queries are needed to determine which one is the truth? We show that the sample complexity is asymptotically $O(ε^{-2})$ where $ε$ is a certain distance between the parameters of the models.
  Furthermore, we draw analogy between the softmax model and the leverage score model, an important tool for algorithm design in linear algebra and graph theory. The leverage score model, on a high level, is a model which, given vector input, produces an output drawn from a distribution dependent on the input. We obtain similar results for the binary hypothesis testing problem for leverage score models.

[Arxiv](https://arxiv.org/abs/2405.06003)