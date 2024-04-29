# 探讨如何利用大型语言模型来构建能力本体的实践

发布时间：2024年04月26日

`LLM应用` `系统建模` `人工智能`

> On the Use of Large Language Models to Generate Capability Ontologies

# 摘要

> 能力本体论正日益广泛应用于系统或机器功能建模。构建这些包含所有属性和约束的本体论模型极为复杂，通常需要本体论专家的专业知识。幸运的是，大型语言模型（LLMs）已证明能够从自然语言文本中生成机器可理解的模型，为工程师和本体论专家提供助力。本篇论文探讨了如何利用LLMs来构建能力本体论。我们通过一系列实验研究，这些实验采用了不同的提示技巧和多种LLMs来生成不同复杂度的能力。实验中记录了生成本体论的错误，并进行了比较。为了评估生成本体论的质量，我们采用了一种结合RDF语法检查、OWL推理和SHACL约束的半自动化分析方法。研究结果显示，即便是处理复杂能力，生成的本体论也几乎无误，这一成果令人鼓舞。

> Capability ontologies are increasingly used to model functionalities of systems or machines. The creation of such ontological models with all properties and constraints of capabilities is very complex and can only be done by ontology experts. However, Large Language Models (LLMs) have shown that they can generate machine-interpretable models from natural language text input and thus support engineers / ontology experts. Therefore, this paper investigates how LLMs can be used to create capability ontologies. We present a study with a series of experiments in which capabilities with varying complexities are generated using different prompting techniques and with different LLMs. Errors in the generated ontologies are recorded and compared. To analyze the quality of the generated ontologies, a semi-automated approach based on RDF syntax checking, OWL reasoning, and SHACL constraints is used. The results of this study are very promising because even for complex capabilities, the generated ontologies are almost free of errors.

[Arxiv](https://arxiv.org/abs/2404.17524)