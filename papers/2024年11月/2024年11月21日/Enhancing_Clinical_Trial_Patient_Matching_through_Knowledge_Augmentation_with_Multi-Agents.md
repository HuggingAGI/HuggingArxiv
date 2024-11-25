# 借助多智能体的知识增强来优化临床试验患者匹配

发布时间：2024年11月21日

`Agent` `临床试验`

> Enhancing Clinical Trial Patient Matching through Knowledge Augmentation with Multi-Agents

# 摘要

> 由于患者资料和试验标准复杂多变，为临床试验高效精准地匹配患者是个重大难题。本文呈现了一个全新的框架——用于知识增强的多智能体（MAKA），旨在通过动态地用外部特定领域知识补充匹配提示，来强化患者与试验的匹配。MAKA 架构包含五个关键部分：能检测领域知识缺口的知识探测智能体；管理多个专业知识增强智能体间交互的导航智能体；将相关信息融入患者-试验匹配提示的知识增强智能体；使其他智能体的输出与指令相符的监督智能体；以及做出最终选择决策的匹配智能体。该方法提升了患者匹配的精准度和情境丰富度，填补了试验标准和大型语言模型（LLMs）中固有的知识空白，增进了患者特征与标准的契合度。

> Matching patients effectively and efficiently for clinical trials is a significant challenge due to the complexity and variability of patient profiles and trial criteria. This paper presents a novel framework, Multi-Agents for Knowledge Augmentation (MAKA), designed to enhance patient-trial matching by dynamically supplementing matching prompts with external, domain-specific knowledge. The MAKA architecture consists of five key components: a knowledge probing agent that detects gaps in domain knowledge, a navigation agent that manages interactions among multiple specialized knowledge augmentation agents, a knowledge augmentation agent that incorporates relevant information into patient-trial matching prompts, a supervision agent aligning the outputs from other agents with the instructions and a matching agent making the final selection decision. This approach enhances the accuracy and contextual richness of patient matching, addresses inherent knowledge gaps in both trail criteria and large language models (LLMs), and improves the alignment between patient characteristics and the criteria.

[Arxiv](https://arxiv.org/abs/2411.14637)