# 探讨概念驱动解释的易读性与准确性。

发布时间：2024年04月29日

`分类：LLM理论` `人工智能`

> Evaluating Readability and Faithfulness of Concept-based Explanations

# 摘要

> 大型语言模型（LLMs）虽然表现出了惊人的智能，但鉴于其不可预测的黑箱特性，我们对于将它们广泛应用于现实生活仍有所保留。为了提高透明度，基于概念的解释方法应运而生，旨在阐明LLMs的学习成果。然而，目前对这些概念的评估方法大多依赖于直觉和主观判断，如个案研究或人工评审，这限制了领域的进步。为此，我们提出了一种基于忠实度和可读性的新评估方法，旨在填补这一空白。我们首先定义了一个广泛适用的概念，并据此量化模型输出在扰动下的变化，以此衡量忠实度。接着，我们通过分析最能激活特定概念的模式的一致性，来自动评估可读性，以此替代人工评估。此外，我们基于测量理论，提出了一种元评估方法，用以评估上述度量的可靠性和有效性，该方法同样适用于其他任务。为了验证和优化概念评估度量的选择，我们已经开展了深入的实验分析。

> Despite the surprisingly high intelligence exhibited by Large Language Models (LLMs), we are somehow intimidated to fully deploy them into real-life applications considering their black-box nature. Concept-based explanations arise as a promising avenue for explaining what the LLMs have learned, making them more transparent to humans. However, current evaluations for concepts tend to be heuristic and non-deterministic, e.g. case study or human evaluation, hindering the development of the field. To bridge the gap, we approach concept-based explanation evaluation via faithfulness and readability. We first introduce a formal definition of concept generalizable to diverse concept-based explanations. Based on this, we quantify faithfulness via the difference in the output upon perturbation. We then provide an automatic measure for readability, by measuring the coherence of patterns that maximally activate a concept. This measure serves as a cost-effective and reliable substitute for human evaluation. Finally, based on measurement theory, we describe a meta-evaluation method for evaluating the above measures via reliability and validity, which can be generalized to other tasks as well. Extensive experimental analysis has been conducted to validate and inform the selection of concept evaluation measures.

[Arxiv](https://arxiv.org/abs/2404.18533)