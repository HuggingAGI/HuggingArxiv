# 自动学习动态系统的混合式数字孪生

发布时间：2024年10月31日

`LLM应用` `数字孪生`

> Automatically Learning Hybrid Digital Twins of Dynamical Systems

# 摘要

> 数字孪生（DTs）乃是模拟现实世界系统状态与时间动态的计算模型，在众多领域的预测、理解及决策方面发挥着关键作用。然而，现有的数字孪生方法在数据稀缺的情形下，往往难以推广至未曾见过的状况，这是此类模型的重要需求。为应对这些局限，我们的工作从确立有效数字孪生的基本必要条件入手。混合数字孪生（$	extbf{HDTwins}$）是满足这些需求的一种颇具前景的途径，它通过机械和神经组件的组合来对系统进行建模。这种混合架构既能借助（部分）领域知识，又能发挥神经网络的表现力来增强泛化能力，其模块化设计有利于提升可进化性。尽管现有的混合模型依赖于专家指定的架构，仅在数据上对参数进行优化，但由于复杂的搜索空间以及灵活整合领域先验知识的需求，$	extit{自动}$指定和优化混合数字孪生仍颇具难度。为攻克这一复杂性，我们提出了一种进化算法（$	extbf{HDTwinGen}$），它借助大型语言模型（LLMs）自主地提出、评估和优化混合数字孪生。具体而言，LLMs 迭代生成新颖的模型规范，同时运用离线工具优化输出的参数。相应地，依据针对性的反馈对所提出的模型进行评估和进化，从而能够发现愈发有效的混合模型。我们的实证结果显示，HDTwinGen 生成了可泛化、样本高效且可进化的模型，极大地提升了数字孪生在实际应用中的效果。

> Digital Twins (DTs) are computational models that simulate the states and temporal dynamics of real-world systems, playing a crucial role in prediction, understanding, and decision-making across diverse domains. However, existing approaches to DTs often struggle to generalize to unseen conditions in data-scarce settings, a crucial requirement for such models. To address these limitations, our work begins by establishing the essential desiderata for effective DTs. Hybrid Digital Twins ($\textbf{HDTwins}$) represent a promising approach to address these requirements, modeling systems using a composition of both mechanistic and neural components. This hybrid architecture simultaneously leverages (partial) domain knowledge and neural network expressiveness to enhance generalization, with its modular design facilitating improved evolvability. While existing hybrid models rely on expert-specified architectures with only parameters optimized on data, $\textit{automatically}$ specifying and optimizing HDTwins remains intractable due to the complex search space and the need for flexible integration of domain priors. To overcome this complexity, we propose an evolutionary algorithm ($\textbf{HDTwinGen}$) that employs Large Language Models (LLMs) to autonomously propose, evaluate, and optimize HDTwins. Specifically, LLMs iteratively generate novel model specifications, while offline tools are employed to optimize emitted parameters. Correspondingly, proposed models are evaluated and evolved based on targeted feedback, enabling the discovery of increasingly effective hybrid models. Our empirical results reveal that HDTwinGen produces generalizable, sample-efficient, and evolvable models, significantly advancing DTs' efficacy in real-world applications.

[Arxiv](https://arxiv.org/abs/2410.23691)