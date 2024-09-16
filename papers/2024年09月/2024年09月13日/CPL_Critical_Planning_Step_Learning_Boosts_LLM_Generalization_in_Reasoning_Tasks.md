# CPL：通过关键规划步骤学习，LLM 在推理任务中的泛化能力得到显著提升。

发布时间：2024年09月13日

`LLM理论` `人工智能`

> CPL: Critical Planning Step Learning Boosts LLM Generalization in Reasoning Tasks

# 摘要

> 训练大型语言模型 (LLM) 以提升推理能力，已在数学推理和代码生成等多个领域取得显著成效。然而，现有方法多聚焦于特定任务的推理优化，而忽视了模型在更广泛推理任务中的泛化能力。为此，我们创新性地提出了关键规划步骤学习 (CPL)，借助蒙特卡洛树搜索 (MCTS) 在多步骤推理任务中探索多样化的规划策略。CPL 通过学习步骤级别的规划偏好，有效提升模型的长期规划能力，进而增强其整体推理能力。此外，尽管直接偏好优化 (DPO) 在许多场景中表现出色，但在处理复杂的多步骤推理任务时，其细粒度监督的不足成为瓶颈。为此，我们进一步提出了步骤级别优势偏好优化 (Step-APO)，将 MCTS 的优势估计融入 DPO，使模型更精准地学习关键的中间规划步骤，从而大幅提升其在推理任务中的泛化能力。实验结果显示，我们的方法在 GSM8K 和 MATH 上的训练，不仅显著提升了这两项任务的性能 (+10.5% 和 +6.5%)，还在 ARC-C、BBH、MMLU-STEM 和 MMLU 等域外推理基准上取得了显著进步 (+4.0%、+1.8%、+2.2% 和 +0.9%)。

> Post-training large language models (LLMs) to develop reasoning capabilities has proven effective across diverse domains, such as mathematical reasoning and code generation. However, existing methods primarily focus on improving task-specific reasoning but have not adequately addressed the model's generalization capabilities across a broader range of reasoning tasks. To tackle this challenge, we introduce Critical Planning Step Learning (CPL), which leverages Monte Carlo Tree Search (MCTS) to explore diverse planning steps in multi-step reasoning tasks. Based on long-term outcomes, CPL learns step-level planning preferences to improve the model's planning capabilities and, consequently, its general reasoning capabilities. Furthermore, while effective in many scenarios for aligning LLMs, existing preference learning approaches like Direct Preference Optimization (DPO) struggle with complex multi-step reasoning tasks due to their inability to capture fine-grained supervision at each step. We propose Step-level Advantage Preference Optimization (Step-APO), which integrates an advantage estimate for step-level preference pairs obtained via MCTS into the DPO. This enables the model to more effectively learn critical intermediate planning steps, thereby further improving its generalization in reasoning tasks. Experimental results demonstrate that our method, trained exclusively on GSM8K and MATH, not only significantly improves performance on GSM8K (+10.5%) and MATH (+6.5%), but also enhances out-of-domain reasoning benchmarks, such as ARC-C (+4.0%), BBH (+1.8%), MMLU-STEM (+2.2%), and MMLU (+0.9%).

[Arxiv](https://arxiv.org/abs/2409.08642)