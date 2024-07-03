# MMedAgent：掌握医疗工具的多模态学习代理

发布时间：2024年07月02日

`Agent` `人工智能`

> MMedAgent: Learning to Use Medical Tools with Multi-modal Agent

# 摘要

> 尽管多模态大型语言模型 (MLLMs) 取得了成功，但其通用性有限，与专业模型相比常显不足。为此，基于 LLM 的代理应运而生，它们能根据用户输入选择合适的专业模型作为工具。然而，这一进步在医学领域尚未深入探索。为此，本文首次推出了专为医学领域设计的代理——**M**ulti-modal **Med**ical **Agent** (MMedAgent)。我们构建了一个包含六种医疗工具解决七项任务的指令调优数据集，使 MMedAgent 能精准选择工具。实验证明，MMedAgent 在多种医疗任务中的表现超越了顶尖的开源方法和 GPT-4o 等闭源模型，且在更新和集成新工具方面极为高效。

> Multi-Modal Large Language Models (MLLMs), despite being successful, exhibit limited generality and often fall short when compared to specialized models. Recently, LLM-based agents have been developed to address these challenges by selecting appropriate specialized models as tools based on user inputs. However, such advancements have not been extensively explored within the medical domain. To bridge this gap, this paper introduces the first agent explicitly designed for the medical field, named \textbf{M}ulti-modal \textbf{Med}ical \textbf{Agent} (MMedAgent). We curate an instruction-tuning dataset comprising six medical tools solving seven tasks, enabling the agent to choose the most suitable tools for a given task. Comprehensive experiments demonstrate that MMedAgent achieves superior performance across a variety of medical tasks compared to state-of-the-art open-source methods and even the closed-source model, GPT-4o. Furthermore, MMedAgent exhibits efficiency in updating and integrating new medical tools.

[Arxiv](https://arxiv.org/abs/2407.02483)