# 迈向交互式与可学习协作驾驶自动化：基于大型语言模型的决策框架

发布时间：2024年09月19日

`Agent` `自动驾驶`

> Towards Interactive and Learnable Cooperative Driving Automation: a Large Language Model-Driven Decision-Making Framework

# 摘要

> 当前，互联自动驾驶车辆（CAVs）已在全球展开道路测试，但其复杂场景下的安全与效率仍待提升。协同驾驶通过利用CAVs的互联能力，有望实现超越单车的协同效应，提升复杂场景中的表现。然而，现有协同驾驶因缺乏交互与持续学习，仅适用于单一场景和特定自动化。为此，本文提出CoDrivingLLM，一个交互且可学习的LLM驱动框架，旨在实现全场景与全自动化协同驾驶。首先，为避免LLM直接控制车辆位置带来的计算错误，引入环境模块，基于语义决策更新车辆位置。其次，基于SAE J3216标准，设计了包含状态感知、意图共享、协商与决策的思维链推理模块，提升LLM在多步骤推理中的稳定性。通过冲突协调器进行集中冲突解决。最后，引入记忆模块与检索增强生成，使CAVs具备从经验中学习的能力。通过消融实验、不同经验推理及与其他方法的比较，验证了CoDrivingLLM的有效性。

> At present, Connected Autonomous Vehicles (CAVs) have begun to open road testing around the world, but their safety and efficiency performance in complex scenarios is still not satisfactory. Cooperative driving leverages the connectivity ability of CAVs to achieve synergies greater than the sum of their parts, making it a promising approach to improving CAV performance in complex scenarios. However, the lack of interaction and continuous learning ability limits current cooperative driving to single-scenario applications and specific Cooperative Driving Automation (CDA). To address these challenges, this paper proposes CoDrivingLLM, an interactive and learnable LLM-driven cooperative driving framework, to achieve all-scenario and all-CDA. First, since Large Language Models(LLMs) are not adept at handling mathematical calculations, an environment module is introduced to update vehicle positions based on semantic decisions, thus avoiding potential errors from direct LLM control of vehicle positions. Second, based on the four levels of CDA defined by the SAE J3216 standard, we propose a Chain-of-Thought (COT) based reasoning module that includes state perception, intent sharing, negotiation, and decision-making, enhancing the stability of LLMs in multi-step reasoning tasks. Centralized conflict resolution is then managed through a conflict coordinator in the reasoning process. Finally, by introducing a memory module and employing retrieval-augmented generation, CAVs are endowed with the ability to learn from their past experiences. We validate the proposed CoDrivingLLM through ablation experiments on the negotiation module, reasoning with different shots experience, and comparison with other cooperative driving methods.

[Arxiv](https://arxiv.org/abs/2409.12812)