# LogicPro：借助程序引导的学习，提升复杂逻辑推理能力

发布时间：2024年09月19日

`LLM应用` `人工智能` `软件开发`

> LogicPro: Improving Complex Logical Reasoning via Program-Guided Learning

# 摘要

> 本文介绍了一种名为 LogicPro 的创新方法，通过程序示例提升 LLM 的复杂逻辑推理能力。我们利用广泛可用的算法问题及其代码解决方案，构建了多样化的测试样本，并设计了复杂的推理问题。结合代码解决方案的中间变量输出，我们推导出推理过程和最终答案。这种方法构建了一个足够困难、多样化且可扩展的数据集，并生成了高质量的推理过程。在多个数据集上，LogicPro 显著提升了模型性能，超越了现有的推理数据集。

> In this paper, we present a novel approach, called LogicPro, to enhance Large Language Models (LLMs) complex Logical reasoning through Program Examples. We do this effectively by simply utilizing widely available algorithmic problems and their code solutions. First, we constructed diverse test samples input based on algorithmic questions and code solutions. Then, we designed different complex reasoning questions based on algorithmic problems and test samples. Finally, combining the intermediate variable outputs of the code solutions and the complex reasoning questions, we derived the reasoning process and the final answer. With this approach, we can construct a dataset that is sufficiently difficult (all models are ineffective), diverse (synthesized from 2,360 different algorithmic questions), and scalable (building different test samples and collecting more algorithmic questions). In addition, we obtain a high-quality reasoning process guided by the values of intermediate variables. As a result, our approach achieves significant improvements in multiple models for the BBH$^{27}$, GSM8K, HellSwag, Logicqa, Reclor, and RTE datasets, outperforming a wide range of existing reasoning datasets.

[Arxiv](https://arxiv.org/abs/2409.12929)