# 大型语言模型的理性元推理

发布时间：2024年10月07日

`LLM理论` `人工智能` `认知科学`

> Rational Metareasoning for Large Language Models

# 摘要

> 推理已成为 LLM 的核心技术，通过增加计算来提升任务性能。但随着 LLM 的规模和应用扩大，推理成本也日益沉重。如何优化推理的成本效益？我们提出了一种基于认知科学元推理模型的新方法，训练 LLM 仅在必要时使用中间推理步骤。首先，我们设计了一个奖励函数，通过惩罚不必要的推理来优化计算价值，然后结合专家迭代训练 LLM。与少样本链式思维提示和 STaR 相比，我们的方法在保持任务性能的同时，显著降低了推理成本（令牌生成减少 20-37%）。

> Being prompted to engage in reasoning has emerged as a core technique for using large language models (LLMs), deploying additional inference-time compute to improve task performance. However, as LLMs increase in both size and adoption, inference costs are correspondingly becoming increasingly burdensome. How, then, might we optimize reasoning's cost-performance tradeoff? This work introduces a novel approach based on computational models of metareasoning used in cognitive science, training LLMs to selectively use intermediate reasoning steps only when necessary. We first develop a reward function that incorporates the Value of Computation by penalizing unnecessary reasoning, then use this reward function with Expert Iteration to train the LLM. Compared to few-shot chain-of-thought prompting and STaR, our method significantly reduces inference costs (20-37\% fewer tokens generated across three models) while maintaining task performance across diverse datasets.

[Arxiv](https://arxiv.org/abs/2410.05563)