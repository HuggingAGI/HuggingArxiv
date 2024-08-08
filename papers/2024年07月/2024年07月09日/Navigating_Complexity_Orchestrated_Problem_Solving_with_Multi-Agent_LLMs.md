# 驾驭复杂性：协同多智能体大型语言模型（LLMs）的复杂问题解决策略。

发布时间：2024年07月09日

`分类：Agent` `人工智能`

> Navigating Complexity: Orchestrated Problem Solving with Multi-Agent LLMs

# 摘要

> 大型语言模型（LLMs）在处理多样化任务上展现了卓越性能，但在应对复杂和不明确问题时仍显不足。尽管现有的多代理LLM系统等方法为特定难题提供了解决方案，但它们往往需要人工配置，且扩展性不足。为了填补这一空白，我们提出了一种创新的解决方案，通过问题分解，使LLMs能够有效处理模糊问题。我们的方案包括一个协调型LLM，它首先与用户沟通以把握问题核心，随后将问题细化为具体的子问题。我们训练LLM不是一次性解决整个问题，而是通过追问来深化对用户需求的理解。问题充分理解后，协调型LLM将其拆分为更小、更易处理的子问题，并将这些子问题分配给专门的LLM代理或非LLM功能进行解决。这些代理并行处理各自的子问题，而协调型LLM则负责监控整个过程，并将解决方案整合成一份全面的答复。采用这种分解策略，我们克服了LLM输出令牌限制的束缚，使其能够为复杂和不明确的问题提供精细的解决方案。通过这种方法，我们期望LLMs能够更接近人类的思考和行动方式，将复杂问题拆解为可处理的部分，并通过协作解决它们。这不仅提升了LLMs的问题解决能力，也为解决现实世界中的广泛挑战提供了一种可扩展且高效的新途径。

> Large Language Models (LLMs) have demonstrated remarkable capabilities in solving various tasks, yet they often struggle with comprehensively addressing complex and vague problems. Existing approaches, including multi-agent LLM systems, offer solutions to certain challenges but still require manual setup and lack scalability. To address this gap, we propose a novel approach leveraging decomposition to enable LLMs to tackle vague problems effectively.
  Our approach involves an orchestrating LLM that interacts with users to understand the problem and then decomposes it into tangible sub-problems. Instead of expecting the LLM to solve the entire problem in one go, we train it to ask follow-up questions to gain a deeper understanding of the user's requirements. Once the problem is adequately understood, the orchestrating LLM divides it into smaller, manageable sub-problems. Each sub-problem is then assigned to specialized LLM agents or non-LLM functions for resolution. These agents work in parallel to solve their respective sub-problems, with the orchestrating LLM overseeing the process and compiling the solutions into a comprehensive answer for the user. By adopting this decomposition approach, we alleviate the constraints imposed by token limitations on LLM outputs and empower them to provide nuanced solutions to complex and ambiguous problems.
  Through our approach, we aim to enable LLMs to think and operate more like humans, breaking down complex problems into manageable parts and collaboratively solving them. This not only enhances the problem-solving capabilities of LLMs but also offers a scalable and efficient method for addressing a wide range of real-world challenges.

[Arxiv](https://arxiv.org/abs/2402.16713)