# SELP：借助大型语言模型，为机器人代理打造既安全又高效的任务计划。

发布时间：2024年09月28日

`LLM应用` `机器人` `无人机`

> SELP: Generating Safe and Efficient Task Plans for Robot Agents with Large Language Models

# 摘要

> 尽管 LLM 在提升机器人对自然语言命令的理解和执行方面取得了显著进展，但确保机器人严格遵循用户指定的约束仍面临挑战，尤其是在处理复杂命令和长期任务时。为此，我们提出了三大关键策略：等价投票、约束解码和领域特定微调，这些策略显著提升了 LLM 在复杂任务中的规划能力。等价投票通过生成和采样多个 LTL 公式，确保从自然语言命令中提取的逻辑一致性；约束解码则利用这些 LTL 公式，确保生成的计划严格符合逻辑要求；领域特定微调则进一步优化 LLM，使其在特定任务领域内生成更安全和高效的计划。我们的 SELP 方法整合了这些策略，创建了能够高度准确执行用户命令的 LLM 规划器。实验表明，SELP 在无人机导航和机器人操作等多项任务中表现优异，显著提升了安全性和效率。相关数据集即将在 github.com/lt-asset/selp 发布。

> Despite significant advancements in large language models (LLMs) that enhance robot agents' understanding and execution of natural language (NL) commands, ensuring the agents adhere to user-specified constraints remains challenging, particularly for complex commands and long-horizon tasks. To address this challenge, we present three key insights, equivalence voting, constrained decoding, and domain-specific fine-tuning, which significantly enhance LLM planners' capability in handling complex tasks. Equivalence voting ensures consistency by generating and sampling multiple Linear Temporal Logic (LTL) formulas from NL commands, grouping equivalent LTL formulas, and selecting the majority group of formulas as the final LTL formula. Constrained decoding then uses the generated LTL formula to enforce the autoregressive inference of plans, ensuring the generated plans conform to the LTL. Domain-specific fine-tuning customizes LLMs to produce safe and efficient plans within specific task domains. Our approach, Safe Efficient LLM Planner (SELP), combines these insights to create LLM planners to generate plans adhering to user commands with high confidence. We demonstrate the effectiveness and generalizability of SELP across different robot agents and tasks, including drone navigation and robot manipulation. For drone navigation tasks, SELP outperforms state-of-the-art planners by 10.8% in safety rate (i.e., finishing tasks conforming to NL commands) and by 19.8% in plan efficiency. For robot manipulation tasks, SELP achieves 20.4% improvement in safety rate. Our datasets for evaluating NL-to-LTL and robot task planning will be released in github.com/lt-asset/selp.

[Arxiv](https://arxiv.org/abs/2409.19471)