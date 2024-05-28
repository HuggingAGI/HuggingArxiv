# 高效成本的大型语言模型知识问答

发布时间：2024年05月27日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在基于知识的问答（KBQA）中的应用，特别是在成本效益和推理准确性方面的优化。通过提出Coke策略，该论文展示了如何在保持成本效益的同时提高KBQA的性能。这与LLM的应用紧密相关，因为它专注于如何有效地利用LLMs来解决实际问题，而不是深入探讨LLM的理论基础或Agent的设计与实现。因此，它属于LLM应用分类。` `问答系统` `成本效益分析`

> Cost-efficient Knowledge-based Question Answering with Large Language Models

# 摘要

> 基于知识的问答（KBQA）在众多领域知识驱动的场景中得到广泛应用。大型语言模型（LLMs）为KBQA开辟了新机遇，但高昂的成本和预训练中缺乏特定领域知识是其短板。我们探索将LLMs与知识图谱上的小型模型（KGMs）融合，旨在提升推理准确性同时降低成本。然而，将这两个目标融合在优化过程中颇具挑战，且模型选择因知识多样性而变得复杂。为此，我们创新性地提出了Coke策略，一种专为KBQA设计的成本效益方案，通过定制的多臂老虎机模型，在预算限制下最小化对LLMs的依赖。我们采用集群级Thompson采样设定准确性预期，并通过上下文感知策略优化，根据问题语义精准选择模型。决策过程受历史失败成本的约束，确保成本效益。实验结果表明，Coke不仅在基准数据集上提升了2.74%的准确性，还节省了高达20.89%的GPT-4费用，显著推动了性能与成本的平衡。

> Knowledge-based question answering (KBQA) is widely used in many scenarios that necessitate domain knowledge. Large language models (LLMs) bring opportunities to KBQA, while their costs are significantly higher and absence of domain-specific knowledge during pre-training. We are motivated to combine LLMs and prior small models on knowledge graphs (KGMs) for both inferential accuracy and cost saving. However, it remains challenging since accuracy and cost are not readily combined in the optimization as two distinct metrics. It is also laborious for model selection since different models excel in diverse knowledge. To this end, we propose Coke, a novel cost-efficient strategy for KBQA with LLMs, modeled as a tailored multi-armed bandit problem to minimize calls to LLMs within limited budgets. We first formulate the accuracy expectation with a cluster-level Thompson Sampling for either KGMs or LLMs. A context-aware policy is optimized to further distinguish the expert model subject to the question semantics. The overall decision is bounded by the cost regret according to historical expenditure on failures. Extensive experiments showcase the superior performance of Coke, which moves the Pareto frontier with up to 20.89% saving of GPT-4 fees while achieving a 2.74% higher accuracy on the benchmark datasets.

![高效成本的大型语言模型知识问答](../../../paper_images/2405.17337/x1.png)

![高效成本的大型语言模型知识问答](../../../paper_images/2405.17337/x2.png)

![高效成本的大型语言模型知识问答](../../../paper_images/2405.17337/x3.png)

![高效成本的大型语言模型知识问答](../../../paper_images/2405.17337/x4.png)

![高效成本的大型语言模型知识问答](../../../paper_images/2405.17337/x5.png)

[Arxiv](https://arxiv.org/abs/2405.17337)