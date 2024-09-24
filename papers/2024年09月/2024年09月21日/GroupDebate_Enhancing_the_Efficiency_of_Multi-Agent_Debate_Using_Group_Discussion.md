# GroupDebate：通过小组讨论增强多智能体辩论的效率

发布时间：2024年09月21日

`Agent` `人工智能`

> GroupDebate: Enhancing the Efficiency of Multi-Agent Debate Using Group Discussion

# 摘要

> 近年来，大型语言模型 (LLM) 在 NLP 任务中表现出色。研究者们致力于提升逻辑推理能力，如思维链、自我一致性思维链、思维树和多代理辩论。在多代理辩论中，增加代理数量和辩论轮次可显著提升性能，但也会大幅增加令牌成本，限制了技术的扩展性。为此，本文提出了一种降低多代理辩论令牌成本的方法，通过将代理分组辩论并共享中间结果，实验表明，该方法可减少高达 51.7% 的令牌消耗，并可能提高 25% 的准确性。这一创新显著提升了多代理辩论的效率和效果。

> In recent years, Large Language Models (LLMs) have demonstrated remarkable capabilities across diverse NLP tasks. Extensive research has explored how to enhance the logical reasoning abilities such as Chain-of-Thought, Chain-of-Thought with Self-Consistency, Tree-Of-Thoughts, and multi-agent debates. In the context of multi-agent debates, significant performance improvements can be achieved with an increasing number of agents and debate rounds. However, the escalation in the number of agents and debate rounds can drastically raise the tokens cost of debates, thereby limiting the scalability of the multi-agent debate technique. To better harness the advantages of multi-agent debates in logical reasoning tasks, this paper proposes a method to significantly reduce token cost in multi-agent debates. This approach involves dividing all agents into multiple debate groups, with agents engaging in debates within their respective groups and sharing interim debate results between groups. Comparative experiments across multiple datasets have demonstrated that this method can reduce the total tokens by up to 51.7% during debates and while potentially enhancing accuracy by as much as 25%. Our method significantly enhances the performance and efficiency of interactions in the multi-agent debate.

[Arxiv](https://arxiv.org/abs/2409.14051)