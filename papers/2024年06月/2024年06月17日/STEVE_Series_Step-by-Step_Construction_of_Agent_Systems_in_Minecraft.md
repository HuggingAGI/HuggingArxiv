# STEVE系列：手把手教你如何在Minecraft中打造智能代理系统

发布时间：2024年06月17日

`Agent

这篇论文主要描述了以大型语言模型（LLM）为核心的具身代理系统在Minecraft环境中的应用和改进。论文详细介绍了STEVE系列代理的设计、训练和性能提升，以及如何通过引入批评家与记忆机制和构建分层多代理体系来增强代理的能力。此外，论文还提到了未来将探索这些代理在现实世界中的应用潜力。这些内容主要集中在代理系统的构建和应用上，因此最合适的分类是Agent。` `人工智能`

> STEVE Series: Step-by-Step Construction of Agent Systems in Minecraft

# 摘要

> 以大型语言模型（LLM）为核心的具身代理系统构建前景广阔。鉴于现实世界中部署和训练此类代理的高成本与不确定性，我们选择在Minecraft环境中启动探索。我们的STEVE系列代理不仅能在虚拟环境中高效完成基础任务，还能应对导航等挑战性任务，甚至展现创造力，效率较之前的最先进技术提升了2.5至7.3倍。我们从基础LLM出发，融合视觉编码器与动作库，均基于优质数据集STEVE-21K训练。接着，引入批评家与记忆机制，将其打造成复杂系统。最终，我们构建了分层多代理体系。最近，我们研究了通过知识蒸馏精简代理系统的方法。展望未来，我们将探索STEVE代理在现实世界中的更多应用潜力。

> Building an embodied agent system with a large language model (LLM) as its core is a promising direction. Due to the significant costs and uncontrollable factors associated with deploying and training such agents in the real world, we have decided to begin our exploration within the Minecraft environment. Our STEVE Series agents can complete basic tasks in a virtual environment and more challenging tasks such as navigation and even creative tasks, with an efficiency far exceeding previous state-of-the-art methods by a factor of $2.5\times$ to $7.3\times$. We begin our exploration with a vanilla large language model, augmenting it with a vision encoder and an action codebase trained on our collected high-quality dataset STEVE-21K. Subsequently, we enhanced it with a Critic and memory to transform it into a complex system. Finally, we constructed a hierarchical multi-agent system. Our recent work explored how to prune the agent system through knowledge distillation. In the future, we will explore more potential applications of STEVE agents in the real world.

[Arxiv](https://arxiv.org/abs/2406.11247)