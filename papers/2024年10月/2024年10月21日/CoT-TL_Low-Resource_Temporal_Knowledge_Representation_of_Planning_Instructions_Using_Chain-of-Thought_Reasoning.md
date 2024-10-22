# CoT-TL：借助链式思维推理，实现规划指令的低资源时间知识表示。

发布时间：2024年10月21日

`Agent` `机器人` `无人机`

> CoT-TL: Low-Resource Temporal Knowledge Representation of Planning Instructions Using Chain-of-Thought Reasoning

# 摘要

> 自主代理在处理含糊的自然语言指令时，常遇到规划难题。将这些指令转换为线性时序逻辑（LTL），能让规划者制定出可行的计划。我们推出了CoT-TL，一个高效的数据驱动框架，能将自然语言规范转化为LTL形式。CoT-TL通过强化思维链推理和语义角色，克服了大型模型依赖大量微调数据的局限，更贴合形式逻辑的需求。这不仅提升了LTL生成的透明度，也增强了用户的信任感。在数据稀缺的情况下，CoT-TL在三个不同数据集上表现卓越，无需微调或中间转换，超越了现有方法。为确保可靠性并减少误差，我们引入了模型检查，以验证LTL输出的语法正确性。通过消融研究和在新数据集上的评估，我们验证了CoT-TL在处理未见过的LTL结构和公式时的有效性。最终，我们将CoT-TL应用于QuadCopter，实现了基于自然语言指令的多步骤无人机规划，证明了其实际应用价值。

> Autonomous agents often face the challenge of interpreting uncertain natural language instructions for planning tasks. Representing these instructions as Linear Temporal Logic (LTL) enables planners to synthesize actionable plans. We introduce CoT-TL, a data-efficient in-context learning framework for translating natural language specifications into LTL representations. CoT-TL addresses the limitations of large language models, which typically rely on extensive fine-tuning data, by extending chain-of-thought reasoning and semantic roles to align with the requirements of formal logic creation. This approach enhances the transparency and rationale behind LTL generation, fostering user trust. CoT-TL achieves state-of-the-art accuracy across three diverse datasets in low-data scenarios, outperforming existing methods without fine-tuning or intermediate translations. To improve reliability and minimize hallucinations, we incorporate model checking to validate the syntax of the generated LTL output. We further demonstrate CoT-TL's effectiveness through ablation studies and evaluations on unseen LTL structures and formulas in a new dataset. Finally, we validate CoT-TL's practicality by integrating it into a QuadCopter for multi-step drone planning based on natural language instructions.

[Arxiv](https://arxiv.org/abs/2410.16207)