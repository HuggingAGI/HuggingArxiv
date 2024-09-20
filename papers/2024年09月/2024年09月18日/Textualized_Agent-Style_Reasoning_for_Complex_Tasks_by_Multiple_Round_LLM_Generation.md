# 多轮 LLM 生成助力复杂任务的文本化代理风格推理

发布时间：2024年09月18日

`Agent` `人工智能` `软件开发`

> Textualized Agent-Style Reasoning for Complex Tasks by Multiple Round LLM Generation

# 摘要

> 思维链提示虽大幅提升 LLM 的推理能力，但仍存在幻觉、解释性差和生成不可控三大难题。为此，我们推出 AgentCOT，一个基于 LLM 的自主代理框架，通过多轮生成以代理风格解决复杂问题。每一步，AgentCOT 选择并执行动作，生成附带证据的中间结果。我们还引入步骤索引，构建复杂推理逻辑的图结构。通过两种新策略，AgentCOT 性能显著提升。实验证明，在六大基准上，我们的方法超越了现有竞争方案。

> Chain-of-thought prompting significantly boosts the reasoning ability of large language models but still faces three issues: hallucination problem, restricted interpretability, and uncontrollable generation. To address these challenges, we present AgentCOT, a llm-based autonomous agent framework, which can solve complex problems in an agent-style manner by multiple round LLM generation. At each step, AgentCOT selects an action and executes it to yield an intermediate result with supporting evidence. In addition, we integrate the step's index into the reasoning process to form a graph structure for complex inference logic. We introduce two new strategies to enhance the performance of AgentCOT.We conduct extensive experiments to verify the effectiveness of our method on six common benchmarks. Results exhibit that our method brings in substantial improvements over current competitive approaches.

[Arxiv](https://arxiv.org/abs/2409.12411)