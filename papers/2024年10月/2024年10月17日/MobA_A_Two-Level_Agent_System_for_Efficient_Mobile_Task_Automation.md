# MobA：一款高效移动任务自动化的双层代理系统

发布时间：2024年10月17日

`Agent` `移动设备` `人工智能助手`

> MobA: A Two-Level Agent System for Efficient Mobile Task Automation

# 摘要

> 现有的移动助手因依赖系统API或受限于理解和决策能力，难以应对复杂指令和多样界面。为此，我们推出了MobA，一款由多模态大型语言模型驱动的创新手机助手。通过精妙的两级代理架构，MobA大幅提升了理解和规划能力。全局代理（GA）负责解读用户指令、管理历史记忆并规划任务，而本地代理（LA）则在GA的指导下，以函数调用的形式执行具体操作。此外，反思模块的加入使任务完成更高效，并赋予系统处理新奇复杂任务的能力。实际测试中，MobA在任务执行效率和完成率上均有显著提升，展现了MLLM赋能移动助手的巨大潜力。

> Current mobile assistants are limited by dependence on system APIs or struggle with complex user instructions and diverse interfaces due to restricted comprehension and decision-making abilities. To address these challenges, we propose MobA, a novel Mobile phone Agent powered by multimodal large language models that enhances comprehension and planning capabilities through a sophisticated two-level agent architecture. The high-level Global Agent (GA) is responsible for understanding user commands, tracking history memories, and planning tasks. The low-level Local Agent (LA) predicts detailed actions in the form of function calls, guided by sub-tasks and memory from the GA. Integrating a Reflection Module allows for efficient task completion and enables the system to handle previously unseen complex tasks. MobA demonstrates significant improvements in task execution efficiency and completion rate in real-life evaluations, underscoring the potential of MLLM-empowered mobile assistants.

[Arxiv](https://arxiv.org/abs/2410.13757)