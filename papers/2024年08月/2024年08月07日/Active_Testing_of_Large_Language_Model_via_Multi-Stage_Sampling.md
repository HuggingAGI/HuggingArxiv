# 采用多阶段采样方法对大型语言模型实施主动测试

发布时间：2024年08月07日

`LLM应用` `人工智能` `软件开发`

> Active Testing of Large Language Model via Multi-Stage Sampling

# 摘要

> 性能评估在大型语言模型（LLM）的研发过程中至关重要，它不仅衡量模型能力，揭示行为特性，还能帮助发现潜在问题，推动持续改进。由于LLM的多样化任务处理能力源于海量训练数据，全面评估同样需要大量高质量、标注精细且具有代表性的测试数据。然而，获取这些数据往往耗时费力，有时甚至难以实现高效评估。为此，研究者提出主动测试策略，通过精选测试数据子集来估算整体性能。但现有方法在应对LLM的新挑战时显得力不从心，如任务类型多样、模型复杂度提升及训练数据缺失等。为解决这些问题，我们推出了AcTracer框架，它专为LLM量身定制，能精准选取少量关键测试数据，实现性能的近最优估计。AcTracer融合LLM的内外部信息，采用多阶段池化主动选择机制降低方差。实验显示，AcTracer在多项任务中超越现有方法，性能提升高达38.83%，树立了新的行业标杆。

> Performance evaluation plays a crucial role in the development life cycle of large language models (LLMs). It estimates the model's capability, elucidates behavior characteristics, and facilitates the identification of potential issues and limitations, thereby guiding further improvement. Given that LLMs' diverse task-handling abilities stem from large volumes of training data, a comprehensive evaluation also necessitates abundant, well-annotated, and representative test data to assess LLM performance across various downstream tasks. However, the demand for high-quality test data often entails substantial time, computational resources, and manual efforts, sometimes causing the evaluation to be inefficient or impractical. To address these challenges, researchers propose active testing, which estimates the overall performance by selecting a subset of test data. Nevertheless, the existing active testing methods tend to be inefficient, even inapplicable, given the unique new challenges of LLMs (e.g., diverse task types, increased model complexity, and unavailability of training data). To mitigate such limitations and expedite the development cycle of LLMs, in this work, we introduce AcTracer, an active testing framework tailored for LLMs that strategically selects a small subset of test data to achieve a nearly optimal performance estimation for LLMs. AcTracer utilizes both internal and external information from LLMs to guide the test sampling process, reducing variance through a multi-stage pool-based active selection. Our experiment results demonstrate that AcTracer achieves state-of-the-art performance compared to existing methods across various tasks, with up to 38.83% improvement over previous SOTA.

[Arxiv](https://arxiv.org/abs/2408.03573)