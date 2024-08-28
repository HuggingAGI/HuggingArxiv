# 面向对象编程领域，大型语言模型的战略优化及其所面临的挑战

发布时间：2024年08月27日

`LLM应用` `软件开发` `人工智能`

> Strategic Optimization and Challenges of Large Language Models in Object-Oriented Programming

# 摘要

> 在代码生成研究中，焦点已从单个函数转向集成上下文信息的类级方法代码，引入了ClassEval和CoderEval等基准。然而，方法级特定上下文因素的影响仍有待深入探索。  本研究专注于OOP框架中的方法级代码生成，基于CoderEval设计实验，调整提示中上下文信息的广度，从方法细节到项目全局。我们创新性地提出了“提示-令牌成本效益”指标，评估增加上下文层的经济性。研究发现，包含方法调用细节的提示最具成本效益。同时，不同LLM在错误分布和辅助开发者方面存在差异，且更大的模型并非总是更优。任务的耦合度越高，挑战越大，选择LLM应考虑任务的耦合特性。例如，GPT-4在低耦合任务中表现更佳，而GPT-3.5更适合高耦合任务。通过精心设计提示和选择合适的LLM，开发者能优化代码质量，实现开发过程中的成本效益最大化。

> In the area of code generation research, the emphasis has transitioned from crafting individual functions to developing class-level method code that integrates contextual information. This shift has brought several benchmarks such as ClassEval and CoderEval, which consider class-level contexts. Nevertheless, the influence of specific contextual factors at the method level remains less explored.
  This research focused on method-level code generation within the Object-Oriented Programming (OOP) framework. Based on CoderEval, we devised experiments that varied the extent of contextual information in the prompts, ranging from method-specific to project-wide details. We introduced the innovative metric of "Prompt-Token Cost-Effectiveness" to evaluate the economic viability of incorporating additional contextual layers. Our findings indicate that prompts enriched with method invocation details yield the highest cost-effectiveness. Additionally, our study revealed disparities among Large Language Models (LLMs) regarding error type distributions and the level of assistance they provide to developers. Notably, larger LLMs do not invariably perform better. We also observed that tasks with higher degrees of coupling present more substantial challenges, suggesting that the choice of LLM should be tailored to the task's coupling degree. For example, GPT-4 exhibited improved performance in low-coupling scenarios, whereas GPT-3.5 seemed better suited for tasks with high coupling. By meticulously curating prompt content and selecting the appropriate LLM, developers can optimize code quality while maximizing cost-efficiency during the development process.

[Arxiv](https://arxiv.org/abs/2408.14834)