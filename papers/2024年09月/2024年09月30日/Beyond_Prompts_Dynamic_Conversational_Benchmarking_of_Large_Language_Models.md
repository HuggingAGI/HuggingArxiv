# 不仅仅是提示：大型语言模型的动态对话性能评估

发布时间：2024年09月30日

`Agent` `人工智能` `对话系统`

> Beyond Prompts: Dynamic Conversational Benchmarking of Large Language Models

# 摘要

> 我们设计了一个动态基准系统，通过模拟长对话来评估对话代理的表现。在对话中，多个任务交替进行，以测试代理的长期记忆、持续学习和信息整合能力。结果显示，LLM在单一任务中表现出色，但在任务交错时则显得力不从心。有趣的是，配备LTM系统的短上下文LLM表现甚至优于长上下文LLM。这表明，面对更自然的交互，LLM还需克服当代基准测试尚未触及的挑战。

> We introduce a dynamic benchmarking system for conversational agents that evaluates their performance through a single, simulated, and lengthy user$\leftrightarrow$agent interaction. The interaction is a conversation between the user and agent, where multiple tasks are introduced and then undertaken concurrently. We context switch regularly to interleave the tasks, which constructs a realistic testing scenario in which we assess the Long-Term Memory, Continual Learning, and Information Integration capabilities of the agents. Results from both proprietary and open-source Large-Language Models show that LLMs in general perform well on single-task interactions, but they struggle on the same tasks when they are interleaved. Notably, short-context LLMs supplemented with an LTM system perform as well as or better than those with larger contexts. Our benchmark suggests that there are other challenges for LLMs responding to more natural interactions that contemporary benchmarks have heretofore not been able to capture.

[Arxiv](https://arxiv.org/abs/2409.20222)