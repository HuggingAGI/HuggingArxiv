# 语言模型作为因果效应生成器

发布时间：2024年11月12日

`LLM应用` `数据生成` `因果推断`

> Language Models as Causal Effect Generators

# 摘要

> 我们提出了一个基于大型语言模型（LLM）的具有可控因果结构的数据生成框架。特别是，我们定义了一个将任何语言模型和任何有向无环图（DAG）转换为序列驱动的结构因果模型（SD-SCM）的过程。一般来说，SD-SCM 是具有用户定义结构和 LLM 定义的结构方程的因果模型。我们描述了 SD-SCM 如何根据所需的因果结构从观察、干预和反事实分布中进行采样。然后，我们利用此过程提出了一种用于因果推断方法的新型基准，无需手动指定变量之间的函数关系即可生成个体级别的反事实数据。我们创建了一个由数千个数据集组成的示例基准，并在这些数据集上测试了一套流行的估计方法，用于平均、条件平均和个体治疗效果估计，包括有和没有隐藏混淆的情况。除了生成数据外，相同的过程还允许我们测试 LLM 中可能编码的因果效应的存在。此过程可以支持审核 LLM 中的错误信息、歧视或其他不良行为。我们相信 SD-SCM 在任何受益于具有可控因果结构的顺序数据的应用中都可以作为有用的工具。

> We present a framework for large language model (LLM) based data generation with controllable causal structure. In particular, we define a procedure for turning any language model and any directed acyclic graph (DAG) into a sequence-driven structural causal model (SD-SCM). Broadly speaking, an SD-SCM is a causal model with user-defined structure and LLM-defined structural equations. We characterize how an SD-SCM allows sampling from observational, interventional, and counterfactual distributions according to the desired causal structure. We then leverage this procedure to propose a new type of benchmark for causal inference methods, generating individual-level counterfactual data without needing to manually specify functional relationships between variables. We create an example benchmark consisting of thousands of datasets, and test a suite of popular estimation methods on these datasets for average, conditional average, and individual treatment effect estimation, both with and without hidden confounding. Apart from generating data, the same procedure also allows us to test for the presence of a causal effect that might be encoded in an LLM. This procedure can underpin auditing LLMs for misinformation, discrimination, or otherwise undesirable behavior. We believe SD-SCMs can serve as a useful tool in any application that would benefit from sequential data with controllable causal structure.

[Arxiv](https://arxiv.org/abs/2411.08019)