# ToolGen：通过生成技术实现工具的统一检索与调用

发布时间：2024年10月04日

`Agent` `人工智能` `软件开发`

> ToolGen: Unified Tool Retrieval and Calling via Generation

# 摘要

> 随着 LLM 的发展，它们无法直接与外部工具交互自主执行任务的问题依然存在。传统方法通过将工具描述作为上下文输入，但受限于上下文长度，且需要额外的检索机制。我们提出的 ToolGen 通过将工具知识融入 LLM 的参数中，每个工具被表示为一个独特令牌，使 LLM 能在生成语言的同时调用工具。这不仅消除了额外检索步骤，还大幅提升了性能和可扩展性。实验显示，ToolGen 在工具检索和任务自主完成方面表现优异，为跨领域适应工具的新一代 AI 代理铺平了道路。通过将工具检索转变为生成过程，ToolGen 推动了更高效、自主的 AI 系统发展，并开启了与思维链、强化学习等技术集成的可能性，进一步增强了 LLM 的实际应用能力。

> As large language models (LLMs) advance, their inability to autonomously execute tasks by directly interacting with external tools remains a critical limitation. Traditional methods rely on inputting tool descriptions as context, which is constrained by context length and requires separate, often inefficient, retrieval mechanisms. We introduce ToolGen, a paradigm shift that integrates tool knowledge directly into the LLM's parameters by representing each tool as a unique token. This enables the LLM to generate tool calls and arguments as part of its next token prediction capabilities, seamlessly blending tool invocation with language generation. Our framework allows the LLM to access and utilize a vast amount of tools with no additional retrieval step, significantly enhancing both performance and scalability. Experimental results with over 47,000 tools show that ToolGen not only achieves superior results in both tool retrieval and autonomous task completion but also sets the stage for a new era of AI agents that can adapt to tools across diverse domains. By fundamentally transforming tool retrieval into a generative process, ToolGen paves the way for more versatile, efficient, and autonomous AI systems. ToolGen enables end-to-end tool learning and opens opportunities for integration with other advanced techniques such as chain-of-thought and reinforcement learning, thereby expanding the practical capabilities of LLMs.

[Arxiv](https://arxiv.org/abs/2410.03439)