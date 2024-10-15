# 在大型语言模型中，如何巧妙地引出、筛选并整合知识，以提升常识推理能力，是我们探讨的核心。

发布时间：2024年10月12日

`LLM应用` `人工智能` `知识图谱`

> LINKED: Eliciting, Filtering and Integrating Knowledge in Large Language Model for Commonsense Reasoning

# 摘要

> 大型语言模型（LLM）在知识密集型任务上有时表现不佳，尤其是常识推理。为解决这一问题，研究人员通常从知识图谱中提取相关知识或通过自我增强方法激发 LLM 中的知识。然而，噪声知识和无效推理问题仍限制了其准确性。为此，我们提出了 LINKED 方法，通过设计奖励模型过滤噪声知识，并引入边际一致推理模块减少无效推理。实验表明，LINKED 在两个复杂常识推理基准上超越了现有最佳方法，准确率提升高达 9.0%。此外，我们提出了一种新的“有效性保留分数”指标，用于评估知识注入的影响。通过深入实验分析，我们揭示了 LLM 在常识推理任务中的诸多有意义结论。

> Large language models (LLMs) sometimes demonstrate poor performance on knowledge-intensive tasks, commonsense reasoning is one of them. Researchers typically address these issues by retrieving related knowledge from knowledge graphs or employing self-enhancement methods to elicit knowledge in LLMs. However, noisy knowledge and invalid reasoning issues hamper their ability to answer questions accurately. To this end, we propose a novel method named eliciting, filtering and integrating knowledge in large language model (LINKED). In it, we design a reward model to filter out the noisy knowledge and take the marginal consistent reasoning module to reduce invalid reasoning. With our comprehensive experiments on two complex commonsense reasoning benchmarks, our method outperforms SOTA baselines (up to 9.0% improvement of accuracy). Besides, to measure the positive and negative impact of the injected knowledge, we propose a new metric called effectiveness-preservation score for the knowledge enhancement works. Finally, through extensive experiments, we conduct an in-depth analysis and find many meaningful conclusions about LLMs in commonsense reasoning tasks.

[Arxiv](https://arxiv.org/abs/2410.09541)