# LLM 助力行为树规划：在机器人任务规划中，借助 LLM 生成行为树

发布时间：2024年09月16日

`Agent` `机器人` `自动化`

> LLM as BT-Planner: Leveraging LLMs for Behavior Tree Generation in Robot Task Planning

# 摘要

> 机器人装配任务因时间长和零件关系复杂而充满挑战。行为树 (BT) 因其模块化和灵活性在机器人任务规划中日益流行，但手动设计费时费力。大型语言模型 (LLM) 虽已用于生成动作序列，但其生成 BT 的能力尚待探索。为此，我们提出 LLM 作为 BT-planner 框架，利用 LLM 的自然语言处理和推理能力，通过四种 in-context learning 方法生成 BT 格式的任务计划，减少人工干预，确保鲁棒性和可理解性。实验表明，该框架通过 in-context learning 和监督微调，显著提升了 LLM 在 BT 生成中的成功率。

> Robotic assembly tasks are open challenges due to the long task horizon and complex part relations. Behavior trees (BTs) are increasingly used in robot task planning for their modularity and flexibility, but manually designing them can be effort-intensive. Large language models (LLMs) have recently been applied in robotic task planning for generating action sequences, but their ability to generate BTs has not been fully investigated. To this end, We propose LLM as BT-planner, a novel framework to leverage LLMs for BT generation in robotic assembly task planning and execution. Four in-context learning methods are introduced to utilize the natural language processing and inference capabilities of LLMs to produce task plans in BT format, reducing manual effort and ensuring robustness and comprehensibility. We also evaluate the performance of fine-tuned, fewer-parameter LLMs on the same tasks. Experiments in simulated and real-world settings show that our framework enhances LLMs' performance in BT generation, improving success rates in BT generation through in-context learning and supervised fine-tuning.

[Arxiv](https://arxiv.org/abs/2409.10444)