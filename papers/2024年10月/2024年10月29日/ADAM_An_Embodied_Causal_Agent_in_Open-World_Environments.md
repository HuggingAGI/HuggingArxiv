# ADAM：开放世界环境中的具身式因果智能体

发布时间：2024年10月29日

`Agent` `智能体`

> ADAM: An Embodied Causal Agent in Open-World Environments

# 摘要

> 在诸如《我的世界》这类开放世界环境中，现有的智能体在持续学习结构化知识，尤其是因果关系时面临诸多挑战。这些挑战源自黑箱模型固有的不透明性以及训练时对先验知识的过度依赖，这削弱了它们的可解释性与泛化能力。为此，我们推出了 ADAM，即《我的世界》里的一个具身因果智能体，它能够自主探索开放世界，感知多模态情境，学习因果世界知识，并通过终身学习来应对复杂任务。ADAM 由四个关键部分提供支持：1）一个交互模块，能让智能体执行动作的同时记录交互过程；2）一个因果模型模块，负责从零开始构建不断扩展的因果图，增强了可解释性，降低了对先验知识的依赖；3）一个控制器模块，涵盖一个规划器、一个执行者和一个内存池，利用学到的因果图来完成任务；4）一个感知模块，由多模态大型语言模型驱动，使 ADAM 能够像人类玩家一样进行感知。大量实验显示，ADAM 从零开始构建出近乎完美的因果图，能够高效地进行任务分解与执行，具有极强的可解释性。值得一提的是，在我们修改的《我的世界》游戏中，在没有先验知识的情况下，ADAM 依然保持性能，并展现出显著的稳健性和泛化能力。ADAM 开创了一种将因果方法与具身智能体协同整合的全新范式。我们的项目页面为 https://opencausalab.github.io/ADAM。

> In open-world environments like Minecraft, existing agents face challenges in continuously learning structured knowledge, particularly causality. These challenges stem from the opacity inherent in black-box models and an excessive reliance on prior knowledge during training, which impair their interpretability and generalization capability. To this end, we introduce ADAM, An emboDied causal Agent in Minecraft, that can autonomously navigate the open world, perceive multimodal contexts, learn causal world knowledge, and tackle complex tasks through lifelong learning. ADAM is empowered by four key components: 1) an interaction module, enabling the agent to execute actions while documenting the interaction processes; 2) a causal model module, tasked with constructing an ever-growing causal graph from scratch, which enhances interpretability and diminishes reliance on prior knowledge; 3) a controller module, comprising a planner, an actor, and a memory pool, which uses the learned causal graph to accomplish tasks; 4) a perception module, powered by multimodal large language models, which enables ADAM to perceive like a human player. Extensive experiments show that ADAM constructs an almost perfect causal graph from scratch, enabling efficient task decomposition and execution with strong interpretability. Notably, in our modified Minecraft games where no prior knowledge is available, ADAM maintains its performance and shows remarkable robustness and generalization capability. ADAM pioneers a novel paradigm that integrates causal methods and embodied agents in a synergistic manner. Our project page is at https://opencausalab.github.io/ADAM.

[Arxiv](https://arxiv.org/abs/2410.22194)