# Ferret：为大型语言模型实现的大规模联合全参数调优

发布时间：2024年09月10日

`LLM理论` `人工智能` `数据隐私`

> Ferret: Federated Full-Parameter Tuning at Scale for Large Language Models

# 摘要

> 大型语言模型 (LLM) 在实际应用中不可或缺，但在联邦设置中大规模微调它们面临挑战，尤其是在数据隐私和通信效率方面。现有方法通过参数高效微调 (PEFT) 减轻通信负担，但常牺牲模型精度。为此，我们提出 Ferret，首个具备共享随机性的第一阶方法，实现跨分散数据源的 LLM 全参数微调，同时保持高精度。Ferret 通过三方面实现：高效本地更新、低维投影减少通信开销、共享随机性重建更新以加速全局聚合。理论分析和实验表明，Ferret 显著提升现有方法的可扩展性，实现高效计算、低通信开销和快速收敛，同时保持竞争性精度。代码见 https://github.com/allen4747/Ferret。

> Large Language Models (LLMs) have become indispensable in numerous real-world applications. Unfortunately, fine-tuning these models at scale, especially in federated settings where data privacy and communication efficiency are critical, presents significant challenges. Existing methods often resort to parameter-efficient fine-tuning (PEFT) to mitigate communication overhead, but this typically comes at the cost of model accuracy. To address these limitations, we propose federated full-parameter tuning at scale for LLMs (Ferret), the first first-order method with shared randomness to enable scalable full-parameter tuning of LLMs across decentralized data sources while maintaining competitive model accuracy. Ferret accomplishes this through three aspects: (1) it employs widely applied first-order methods for efficient local updates; (2) it projects these updates into a low-dimensional space to considerably reduce communication overhead; and (3) it reconstructs local updates from this low-dimensional space with shared randomness to facilitate effective full-parameter global aggregation, ensuring fast convergence and competitive final performance. Our rigorous theoretical analyses and insights along with extensive experiments, show that Ferret significantly enhances the scalability of existing federated full-parameter tuning approaches by achieving high computational efficiency, reduced communication overhead, and fast convergence, all while maintaining competitive model accuracy. Our implementation is available at https://github.com/allen4747/Ferret.

[Arxiv](https://arxiv.org/abs/2409.06277)