# 反转思维：借助偏好引导的反向推理预热，提升大型语言模型的性能

发布时间：2024年10月16日

`LLM理论` `人工智能`

> Reversal of Thought: Enhancing Large Language Models with Preference-Guided Reverse Reasoning Warm-up

# 摘要

> 大型语言模型（LLM）在推理任务中表现优异，但在数学和复杂逻辑推理上仍有不足。现有方法要么通过构建逻辑结构提高可靠性但增加计算成本，要么引入刚性规则降低灵活性。本文提出“思维反转”（RoT）框架，旨在提升LLM的逻辑推理能力。RoT采用偏好引导的反向推理策略，通过元认知机制整合逻辑符号，生成任务特定提示，与RLHF塑造的认知偏好相符。通过反向推理，RoT评估知识边界，聚合已知任务的解决方案逻辑和未知任务的风格模板，进一步扩展LLM的推理能力。实验证明，RoT在推理准确性和效率上均优于现有方法。

> Large language models (LLMs) have shown remarkable performance in reasoning tasks but face limitations in mathematical and complex logical reasoning. Existing methods to improve LLMs' logical capabilities either involve traceable or verifiable logical sequences that generate more reliable responses by constructing logical structures yet increase computational costs, or introduces rigid logic template rules, reducing flexibility. In this paper, we propose Reversal of Thought (RoT), a novel framework aimed at enhancing the logical reasoning abilities of LLMs. RoT utilizes a Preference-Guided Reverse Reasoning warm-up strategy, which integrates logical symbols for pseudocode planning through meta-cognitive mechanisms and pairwise preference self-evaluation to generate task-specific prompts solely through demonstrations, aligning with LLMs' cognitive preferences shaped by Reinforcement Learning with Human Feedback (RLHF). Through reverse reasoning, we ultilize a Cognitive Preference Manager to assess knowledge boundaries and further expand LLMs' reasoning capabilities by aggregating solution logic for known tasks and stylistic templates for unknown tasks. Experiments across various tasks demonstrate that RoT surpasses existing baselines in both reasoning accuracy and efficiency.

[Arxiv](https://arxiv.org/abs/2410.12323)