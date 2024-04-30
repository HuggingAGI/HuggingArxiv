# 通过合成的用户输入，我们对大型语言模型（LLM）代理中的错误规划进行了测试与理解。

发布时间：2024年04月27日

`Agent` `自动化测试` `人工智能`

> Testing and Understanding Erroneous Planning in LLM Agents through Synthesized User Inputs

# 摘要

> 大型语言模型（LLM）驱动的智能代理通过融合规划、记忆和工具使用等核心组件，在多样化任务解决中展现了卓越效能。客户日益青睐此类代理，广泛应用于心理健康支持、化学合成和软件开发等关键商业场景。尽管如此，我们对LLM代理的日常应用和观察发现，在面对复杂任务和长期规划需求时，它们容易出现计划失误。本文提出了PDoctor，一个创新的自动化测试框架，旨在检测和理解LLM代理的规划缺陷。作为该领域的开创性研究，我们将错误规划的识别问题转化为约束满足问题：若代理的执行计划与用户输入的约束相违背，则被视为有误。PDoctor首先创建了一个针对用户查询的特定领域语言（DSL），并借助Z3约束求解器生成多样化的输入。这些输入是描述任务完成需求的自然语言段落。随后，PDoctor根据这些需求提炼出约束，构建测试用例。我们对PDoctor进行了评估，涉及三种主流代理框架和两种先进的LLM（GPT-3.5和GPT-4）。评估结果显示，PDoctor能够高效发现代理规划中的多种错误，并为开发者和用户提供了宝贵的错误特征和见解。文末，我们探讨了PDoctor的潜在设计替代方案和未来发展方向。

> Agents based on large language models (LLMs) have demonstrated effectiveness in solving a wide range of tasks by integrating LLMs with key modules such as planning, memory, and tool usage. Increasingly, customers are adopting LLM agents across a variety of commercial applications critical to reliability, including support for mental well-being, chemical synthesis, and software development. Nevertheless, our observations and daily use of LLM agents indicate that they are prone to making erroneous plans, especially when the tasks are complex and require long-term planning.
  In this paper, we propose PDoctor, a novel and automated approach to testing LLM agents and understanding their erroneous planning. As the first work in this direction, we formulate the detection of erroneous planning as a constraint satisfiability problem: an LLM agent's plan is considered erroneous if its execution violates the constraints derived from the user inputs. To this end, PDoctor first defines a domain-specific language (DSL) for user queries and synthesizes varying inputs with the assistance of the Z3 constraint solver. These synthesized inputs are natural language paragraphs that specify the requirements for completing a series of tasks. Then, PDoctor derives constraints from these requirements to form a testing oracle. We evaluate PDoctor with three mainstream agent frameworks and two powerful LLMs (GPT-3.5 and GPT-4). The results show that PDoctor can effectively detect diverse errors in agent planning and provide insights and error characteristics that are valuable to both agent developers and users. We conclude by discussing potential alternative designs and directions to extend PDoctor.

[Arxiv](https://arxiv.org/abs/2404.17833)