# MOSS：赋能 AI 代理的代码驱动进化与上下文管理

发布时间：2024年09月24日

`Agent` `软件开发` `人工智能`

> MOSS: Enabling Code-Driven Evolution and Context Management for AI Agents

# 摘要

> 开发基于 LLM 的 AI 代理，实现真正的图灵完备性和代码驱动的进化，面临巨大挑战。现有方法常独立生成代码，严重依赖 LLM 内存，效率低下且适应性受限。沙盒环境中的手动协议开发进一步限制了代理的自主性。保持多轮交互中的代码和上下文一致性，以及确保局部变量隔离，仍是未解难题。为此，我们推出 MOSS 框架，集成代码生成与动态上下文管理，解决上述问题。MOSS 通过维护 Python 上下文，确保交互间的一致性和适应性，包括局部变量隔离和运行时完整性。核心上，MOSS 结合 IoC 容器与装饰器，强制最少知识原则，使代理专注于抽象接口而非具体实现。这促进新工具和库的无缝集成，实现运行时实例替换，简化提示复杂性，为代理提供“所见即所得”环境。通过案例研究，我们展示 MOSS 如何提升代理开发的效率和能力，并强调其在实现图灵完备、代码进化代理方面的优势。

> Developing AI agents powered by large language models (LLMs) faces significant challenges in achieving true Turing completeness and adaptive, code-driven evolution. Current approaches often generate code independently of its runtime context, relying heavily on the LLM's memory, which results in inefficiencies and limits adaptability. Manual protocol development in sandbox environments further constrains the agent's autonomous adaptability. Crucially, achieving consistency in code and context across multi-turn interactions and ensuring isolation of local variables within each interaction remains an unsolved problem.
  We introduce MOSS (llM-oriented Operating System Simulation), a novel framework that addresses these challenges by integrating code generation with a dynamic context management system. MOSS ensures consistency and adaptability by using a mechanism that maintains the Python context across interactions, including isolation of local variables and preservation of runtime integrity. At its core, the framework employs an Inversion of Control (IoC) container in conjunction with decorators to enforce the least knowledge principle, allowing agents to focus on abstract interfaces rather than concrete implementations. This facilitates seamless integration of new tools and libraries, enables runtime instance replacement, and reduces prompt complexity, providing a "what you see is what you get" environment for the agent.
  Through a series of case studies, we show how this framework can enhance the efficiency and capabilities of agent development and highlight its advantages in moving towards Turing-complete agents capable of evolving through code.

[Arxiv](https://arxiv.org/abs/2409.16120)