# 通过组合指令调优，助力 LLM 实现多轮功能调用

发布时间：2024年10月16日

`LLM应用` `人工智能` `软件开发`

> Facilitating Multi-turn Function Calling for LLMs via Compositional Instruction Tuning

# 摘要

> 大型语言模型 (LLM) 在执行多样任务方面展示了显著潜力，包括调用函数或使用外部工具以增强其性能的能力。然而，当前研究主要集中在单轮函数调用上，忽略了多轮函数调用的必要性——这对于处理需要函数规划但不仅限于使用函数的组合性、现实世界查询至关重要。为此，我们引入了 BUTTON 方法，通过自底向上的指令构建和自顶向下的轨迹生成来生成合成组合指令调优数据。在自底向上阶段，我们基于现实世界场景生成简单的原子任务，并使用基于原子任务的启发式策略构建组合任务，并开发相应的函数。自顶向下阶段则通过多代理环境中的交互，收集多轮函数调用轨迹。这种方法确保了任务的组合性，并通过检查组合任务中的原子任务来实现有效的函数和轨迹生成。我们生成了包含 8k 数据点的 BUTTONInstruct 数据集，并通过在各种 LLM 上的广泛实验展示了其有效性。

> Large Language Models (LLMs) have exhibited significant potential in performing diverse tasks, including the ability to call functions or use external tools to enhance their performance. While current research on function calling by LLMs primarily focuses on single-turn interactions, this paper addresses the overlooked necessity for LLMs to engage in multi-turn function calling--critical for handling compositional, real-world queries that require planning with functions but not only use functions. To facilitate this, we introduce an approach, BUTTON, which generates synthetic compositional instruction tuning data via bottom-up instruction construction and top-down trajectory generation. In the bottom-up phase, we generate simple atomic tasks based on real-world scenarios and build compositional tasks using heuristic strategies based on atomic tasks. Corresponding functions are then developed for these compositional tasks. The top-down phase features a multi-agent environment where interactions among simulated humans, assistants, and tools are utilized to gather multi-turn function calling trajectories. This approach ensures task compositionality and allows for effective function and trajectory generation by examining atomic tasks within compositional tasks. We produce a dataset BUTTONInstruct comprising 8k data points and demonstrate its effectiveness through extensive experiments across various LLMs.

[Arxiv](https://arxiv.org/abs/2410.12952)