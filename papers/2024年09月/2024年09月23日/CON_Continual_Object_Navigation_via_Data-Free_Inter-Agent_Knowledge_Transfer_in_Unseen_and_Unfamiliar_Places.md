# 在未知且陌生的环境中，通过无需数据的代理间知识传递实现持续对象导航

发布时间：2024年09月23日

`Agent` `机器人` `人工智能`

> CON: Continual Object Navigation via Data-Free Inter-Agent Knowledge Transfer in Unseen and Unfamiliar Places

# 摘要

> 本研究探索了简短的代理间知识转移 (KT) 如何增强机器人在陌生环境中的目标导航 (ON) 能力。借鉴人类旅行者获取当地知识的类比，我们设计了一个框架，旅行者机器人 (学生) 通过与当地机器人 (教师) 的简短互动获取 ON 知识。我们将此过程视为无数据持续学习 (CL) 挑战，旨在将知识从黑箱模型 (教师) 转移到新模型 (学生)。与依赖大型语言模型 (LLM) 的零-shot ON 方法不同，后者使用自然语言进行知识表示，其他两种 ON 方法——使用对象特征图的前沿驱动方法和使用神经状态-动作图的学习型 ON——面临复杂挑战，无数据 KT 仍未被充分探索。为此，我们提出了一种轻量级、即插即用的 KT 模块，专门针对开放世界中的非合作黑箱教师。基于每个教师机器人都有视觉和移动能力的假设，我们将状态-动作历史作为主要知识库。这一设计催生了一种基于查询的占用图，动态表示目标对象位置，既高效又适合通信。通过在 Habitat 环境中的实验，我们验证了该方法的有效性。

> This work explores the potential of brief inter-agent knowledge transfer (KT) to enhance the robotic object goal navigation (ON) in unseen and unfamiliar environments. Drawing on the analogy of human travelers acquiring local knowledge, we propose a framework in which a traveler robot (student) communicates with local robots (teachers) to obtain ON knowledge through minimal interactions. We frame this process as a data-free continual learning (CL) challenge, aiming to transfer knowledge from a black-box model (teacher) to a new model (student). In contrast to approaches like zero-shot ON using large language models (LLMs), which utilize inherently communication-friendly natural language for knowledge representation, the other two major ON approaches -- frontier-driven methods using object feature maps and learning-based ON using neural state-action maps -- present complex challenges where data-free KT remains largely uncharted. To address this gap, we propose a lightweight, plug-and-play KT module targeting non-cooperative black-box teachers in open-world settings. Using the universal assumption that every teacher robot has vision and mobility capabilities, we define state-action history as the primary knowledge base. Our formulation leads to the development of a query-based occupancy map that dynamically represents target object locations, serving as an effective and communication-friendly knowledge representation. We validate the effectiveness of our method through experiments conducted in the Habitat environment.

[Arxiv](https://arxiv.org/abs/2409.14899)