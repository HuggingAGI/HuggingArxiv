# 大型语言模型是否在对错误基准进行记忆？

发布时间：2024年11月20日

`LLM应用` `软件工程` `数据评估`

> Are Large Language Models Memorizing Bug Benchmarks?

# 摘要

> 大型语言模型（LLMs）已融入各类软件工程任务，涵盖代码生成、错误检测与修复等。为评估这些领域的模型表现，众多包含软件项目真实错误的错误基准应运而生。然而，软件工程领域日益担忧的是，鉴于数据泄漏风险，这些基准或许难以如实反映 LLM 的真实性能。尽管存在此忧虑，但针对潜在泄漏影响的量化研究却颇为有限。
    在本文中，我们对热门 LLMs 进行了系统评估，以衡量它们在广泛使用的错误基准中受数据泄漏影响的程度。为识别潜在泄漏，我们运用了多种指标，包括对常用训练数据集中基准成员资格的研究，以及对负对数似然和 n-gram 准确率的分析。我们的发现表明，某些模型，尤其是 codegen-multi，在诸如 Defects4J 等广泛运用的基准中呈现出显著的记忆痕迹，而基于更大数据集（如 LLaMa 3.1）训练的较新模型则显示出有限的数据泄漏迹象。这些结果凸显出，需谨慎选择基准，并采用稳健指标来充分评估模型的能力。

> Large Language Models (LLMs) have become integral to various software engineering tasks, including code generation, bug detection, and repair. To evaluate model performance in these domains, numerous bug benchmarks containing real-world bugs from software projects have been developed. However, a growing concern within the software engineering community is that these benchmarks may not reliably reflect true LLM performance due to the risk of data leakage. Despite this concern, limited research has been conducted to quantify the impact of potential leakage.
  In this paper, we systematically evaluate popular LLMs to assess their susceptibility to data leakage from widely used bug benchmarks. To identify potential leakage, we use multiple metrics, including a study of benchmark membership within commonly used training datasets, as well as analyses of negative log-likelihood and n-gram accuracy. Our findings show that certain models, in particular codegen-multi, exhibit significant evidence of memorization in widely used benchmarks like Defects4J, while newer models trained on larger datasets like LLaMa 3.1 exhibit limited signs of leakage. These results highlight the need for careful benchmark selection and the adoption of robust metrics to adequately assess models capabilities.

[Arxiv](https://arxiv.org/abs/2411.13323)