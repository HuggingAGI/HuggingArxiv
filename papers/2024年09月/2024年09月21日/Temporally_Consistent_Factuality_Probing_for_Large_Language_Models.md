# 大型语言模型的时间一致性事实探测

发布时间：2024年09月21日

`LLM应用` `人工智能` `知识库`

> Temporally Consistent Factuality Probing for Large Language Models

# 摘要

> LLM 作为知识库的广泛应用要求其在事实性上保持一致，这需要重述查询的正确性和一致性。尽管已有基准测试数据集和指标来评估这些特征，但其查询结构的简单性和当代关联性限制了事实性和一致性的定义。为此，我们引入了 TeCFaP 任务，扩展了时间维度上的事实性探测。我们构建了 TEMP-COFAC 数据集，并扩展了现有指标的定义。实验显示，大多数 LLM 在 TeCFaP 上表现不佳。为此，我们提出了 CoTSeLF 框架，结合多任务指令调优和时间敏感强化学习，显著提升了 LLM 的时间一致事实性。

> The prolific use of Large Language Models (LLMs) as an alternate knowledge base requires them to be factually consistent, necessitating both correctness and consistency traits for paraphrased queries. Recently, significant attempts have been made to benchmark datasets and metrics to evaluate LLMs for these traits. However, structural simplicity (subject-relation-object) and contemporary association in their query formulation limit the broader definition of factuality and consistency. In this study, we introduce TeCFaP, a novel Temporally Consistent Factuality Probe task to expand the consistent factuality probe in the temporal dimension. To this end, we propose TEMP-COFAC, a high-quality dataset of prefix-style English query paraphrases. Subsequently, we extend the definitions of existing metrics to represent consistent factuality across temporal dimension. We experiment with a diverse set of LLMs and find most of them performing poorly on TeCFaP. Next, we propose a novel solution CoTSeLF (Consistent-Time-Sensitive Learning Framework) combining multi-task instruction tuning (MT-IT) with consistent-time-sensitive reinforcement learning (CTSRL) to improve temporally consistent factuality in LLMs. Our experiments demonstrate the efficacy of CoTSeLF over several baselines.

[Arxiv](https://arxiv.org/abs/2409.14065)