# DART-LLM：借助大型语言模型实现依赖感知的多机器人任务分解与执行

发布时间：2024年11月13日

`LLM应用` `机器人` `多机器人系统`

> DART-LLM: Dependency-Aware Multi-Robot Task Decomposition and Execution using Large Language Models

# 摘要

> 大型语言模型（LLMs）在机器人系统中展现出了强大的推理能力。但在多机器人系统中的应用仍较为分散，难以应对复杂的任务依赖关系和并行执行问题。本研究推出了 DART-LLM（基于大型语言模型的依赖感知多机器人任务分解与执行）系统，以应对这些挑战。DART-LLM 借助 LLMs 解析自然语言指令，将其分解为具有依赖关系的多个子任务，构建复杂任务序列，从而提升多机器人系统的高效协调和并行执行能力。该系统涵盖 QA LLM 模块、分解功能模块、驱动模块以及基于视觉语言模型（VLM）的对象检测模块，可实现从自然语言指令到机器人动作的任务分解与执行。实验结果显示，DART-LLM 在处理长时程任务和具有复杂依赖关系的协作任务时表现卓越。即便使用像 Llama 3.1 8B 这类较小的模型，系统也能有出色表现，凸显了 DART-LLM 在模型规模方面的稳健性。如需视频和代码，请访问项目网站 url{https://wyd0817.github.io/project-dart-llm/}。

> Large Language Models (LLMs) have demonstrated significant reasoning capabilities in robotic systems. However, their deployment in multi-robot systems remains fragmented and struggles to handle complex task dependencies and parallel execution. This study introduces the DART-LLM (Dependency-Aware Multi-Robot Task Decomposition and Execution using Large Language Models) system, designed to address these challenges. DART-LLM utilizes LLMs to parse natural language instructions, decomposing them into multiple subtasks with dependencies to establish complex task sequences, thereby enhancing efficient coordination and parallel execution in multi-robot systems. The system includes the QA LLM module, Breakdown Function modules, Actuation module, and a Vision-Language Model (VLM)-based object detection module, enabling task decomposition and execution from natural language instructions to robotic actions. Experimental results demonstrate that DART-LLM excels in handling long-horizon tasks and collaborative tasks with complex dependencies. Even when using smaller models like Llama 3.1 8B, the system achieves good performance, highlighting DART-LLM's robustness in terms of model size. Please refer to the project website url{https://wyd0817.github.io/project-dart-llm/} for videos and code.

[Arxiv](https://arxiv.org/abs/2411.09022)