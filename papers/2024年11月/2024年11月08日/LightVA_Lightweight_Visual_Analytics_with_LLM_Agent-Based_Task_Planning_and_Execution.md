# LightVA：基于 LLM 代理的任务规划和执行的轻量级可视化分析

发布时间：2024年11月08日

`LLM应用` `视觉分析` `人机协作`

> LightVA: Lightweight Visual Analytics with LLM Agent-Based Task Planning and Execution

# 摘要

> 视觉分析（VA）要求分析师根据观察结果反复提出分析任务，并通过创建可视化和交互式探索来执行任务以获取见解。这个过程需要编程、数据处理和可视化工具方面的技能，突出了对更智能、更精简的 VA 方法的需求。大型语言模型（LLM）最近被开发为能够处理各种具有动态规划和工具使用能力的任务的代理，为提高 VA 的效率和多功能性提供了潜力。我们提出了 LightVA，这是一个轻量级的 VA 框架，通过人机协作支持任务分解、数据分析和交互式探索。我们的方法旨在帮助用户逐步将高级分析目标转化为低级任务，生成可视化并得出见解。具体来说，我们引入了基于 LLM 代理的任务规划和执行策略，采用了涉及规划器、执行器和控制器的递归过程。规划器负责推荐和分解任务，执行器处理任务执行，包括数据分析、可视化生成和多视图组合，控制器协调规划器和执行器之间的交互。基于该框架，我们开发了一个具有混合用户界面的系统，包括用于监视和管理任务规划过程的任务流程图、用于交互式数据探索的可视化面板以及用于通过自然语言指令引导模型的聊天视图。我们通过使用场景和专家研究来检验我们方法的有效性。

> Visual analytics (VA) requires analysts to iteratively propose analysis tasks based on observations and execute tasks by creating visualizations and interactive exploration to gain insights. This process demands skills in programming, data processing, and visualization tools, highlighting the need for a more intelligent, streamlined VA approach. Large language models (LLMs) have recently been developed as agents to handle various tasks with dynamic planning and tool-using capabilities, offering the potential to enhance the efficiency and versatility of VA. We propose LightVA, a lightweight VA framework that supports task decomposition, data analysis, and interactive exploration through human-agent collaboration. Our method is designed to help users progressively translate high-level analytical goals into low-level tasks, producing visualizations and deriving insights. Specifically, we introduce an LLM agent-based task planning and execution strategy, employing a recursive process involving a planner, executor, and controller. The planner is responsible for recommending and decomposing tasks, the executor handles task execution, including data analysis, visualization generation and multi-view composition, and the controller coordinates the interaction between the planner and executor. Building on the framework, we develop a system with a hybrid user interface that includes a task flow diagram for monitoring and managing the task planning process, a visualization panel for interactive data exploration, and a chat view for guiding the model through natural language instructions. We examine the effectiveness of our method through a usage scenario and an expert study.

[Arxiv](https://arxiv.org/abs/2411.05651)