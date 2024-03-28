# 在“想象工坊”场景下，LLMs 通过模拟试验与错误的方式习得工具使用技巧。

发布时间：2024年03月07日

`Agent`

> LLMs in the Imaginarium: Tool Learning through Simulated Trial and Error

# 摘要

> 对于LLMs而言，工具是其获取实时信息并对外部环境做出有效反应不可或缺的帮手。尽管当前对强化LLMs工具的研究主要集中于工具库的全面性和新增工具的灵活性上，但有一个意外却鲜有深入探讨的重要问题是：LLM在运用经过训练的工具时，准确度究竟如何？研究发现，即使是GPT-4这样的尖端模型或专为工具使用优化的开源LLMs，其工具使用正确率也仅徘徊在30%至60%之间，距离实际可靠应用尚有较大差距。为此，我们创新性地引入了一种基于生物系统的模拟试错（STE）方法，巧妙融合了试错、想象与记忆这三种生物体系中成功使用工具的核心机制。STE特别借助LLM的“想象力”模拟各种可能的工具应用场景，并通过与工具互动及汲取执行反馈来学习改进。同时，利用短期记忆和长期记忆分别深化和拓宽探索边界。综合实验结果显示，在上下文学习和微调两种设置下，STE显著提升了LLMs对工具的学习效果，其中Mistral-Instruct-7B的表现跃升了46.7%，甚至优于GPT-4。此外，我们还验证了一种简洁实用的经验回放策略，能够有效地支持LLMs持续学习和掌握更多工具技能。

> Tools are essential for large language models (LLMs) to acquire up-to-date information and take consequential actions in external environments. Existing work on tool-augmented LLMs primarily focuses on the broad coverage of tools and the flexibility of adding new tools. However, a critical aspect that has surprisingly been understudied is simply how accurately an LLM uses tools for which it has been trained. We find that existing LLMs, including GPT-4 and open-source LLMs specifically fine-tuned for tool use, only reach a correctness rate in the range of 30% to 60%, far from reliable use in practice. We propose a biologically inspired method for tool-augmented LLMs, simulated trial and error (STE), that orchestrates three key mechanisms for successful tool use behaviors in the biological system: trial and error, imagination, and memory. Specifically, STE leverages an LLM's 'imagination' to simulate plausible scenarios for using a tool, after which the LLM interacts with the tool to learn from its execution feedback. Both short-term and long-term memory are employed to improve the depth and breadth of the exploration, respectively. Comprehensive experiments on ToolBench show that STE substantially improves tool learning for LLMs under both in-context learning and fine-tuning settings, bringing a boost of 46.7% to Mistral-Instruct-7B and enabling it to outperform GPT-4. We also show effective continual learning of tools via a simple experience replay strategy.

[Arxiv](https://arxiv.org/abs/2403.04746)