# 工具链：大型语言模型，自动掌握多工具的学习者

发布时间：2024年05月26日

`Agent

这篇论文主要讨论了如何通过自动工具链（ATC）框架和黑盒探测技术，使大型语言模型（LLMs）能够更灵活地使用多种工具，并能够主动学习和适应新工具。这种方法增强了LLMs的自主性和适应性，使其更像一个能够自主决策和执行任务的智能代理（Agent）。因此，这篇论文更适合归类到Agent分类中。` `自动化` `人工智能`

> Chain of Tools: Large Language Model is an Automatic Multi-tool Learner

# 摘要

> 通过整合外部工具，大型语言模型（LLMs）的实用性得以扩展，使其能够解决实际问题。现有研究通常让LLMs遵循预设的工作流程，逐步选择并执行工具以获取结果。但这种方法存在两大问题：一是控制流程过于定制化，限制了LLM的规划视野；二是LLM只能使用预设或训练过的工具，缺乏对新工具的适应性。为此，我们提出了自动工具链（ATC）框架，让LLM能够编程式地使用多种工具。我们还开发了一种黑盒探测技术，使LLM能够主动学习和记录新工具的使用方法。为了全面评估，我们创建了ToolFlow基准，专注于长期规划和复杂工具使用。实验结果显示，我们的框架在多个数据集上表现出色，证明了黑盒探测算法的有效性和实用性。

> Augmenting large language models (LLMs) with external tools has emerged as a promising approach to extend their utility, empowering them to solve practical tasks. Existing work typically empowers LLMs as tool users with a manually designed workflow, where the LLM plans a series of tools in a step-by-step manner, and sequentially executes each tool to obtain intermediate results until deriving the final answer. However, they suffer from two challenges in realistic scenarios: (1) The handcrafted control flow is often ad-hoc and constraints the LLM to local planning; (2) The LLM is instructed to use only manually demonstrated tools or well-trained Python functions, which limits its generalization to new tools. In this work, we first propose Automatic Tool Chain (ATC), a framework that enables the LLM to act as a multi-tool user, which directly utilizes a chain of tools through programming. To scale up the scope of the tools, we next propose a black-box probing method. This further empowers the LLM as a tool learner that can actively discover and document tool usages, teaching themselves to properly master new tools. For a comprehensive evaluation, we build a challenging benchmark named ToolFlow, which diverges from previous benchmarks by its long-term planning scenarios and complex toolset. Experiments on both existing datasets and ToolFlow illustrate the superiority of our framework. Analysis on different settings also validates the effectiveness and the utility of our black-box probing algorithm.

![工具链：大型语言模型，自动掌握多工具的学习者](../../../paper_images/2405.16533/x1.png)

![工具链：大型语言模型，自动掌握多工具的学习者](../../../paper_images/2405.16533/x2.png)

![工具链：大型语言模型，自动掌握多工具的学习者](../../../paper_images/2405.16533/x3.png)

[Arxiv](https://arxiv.org/abs/2405.16533)