# 在多模态大型语言模型里，借助自主想象来强化视觉推理

发布时间：2024年11月27日

`LLM应用` `多模态` `视觉推理`

> Enhancing Visual Reasoning with Autonomous Imagination in Multimodal Large Language Models

# 摘要

> 近来，有人尝试将思维链（CoT）范式拓展至多模态大型语言模型（MLLMs），即在输入场景中找寻视觉线索，以增强 MLLMs 的视觉推理能力。然而，当下的方法专为线索找寻在整个推理过程中起关键作用的任务而设，这致使在应对复杂视觉场景时遭遇难题，因为在这类场景中，线索找寻实际上并未简化整个推理任务。为应对此挑战，我们提出了一种全新的视觉推理范式，让 MLLMs 能依据自身推理状态将输入场景自主修改为新场景，进而将 CoT 重新定义为在一系列想象的视觉场景中进行简单的闭环决策与推理步骤，达成自然且通用的 CoT 构建。为实现这一范式，我们引入了一个新颖的即插即用想象空间，MLLMs 基于其原生推理能力，通过聚焦、忽略和转换等操作进行视觉修改，无需专门训练。我们通过涵盖密集计数、简单拼图解决和对象放置的基准来验证我们的方法，挑战超越线索找寻的推理能力。结果表明，尽管现有技术存在短板，但我们的方法能让 MLLMs 通过自主想象有效地逐步推理。项目页面：https://future-item.github.io/autoimagine-site。

> There have been recent efforts to extend the Chain-of-Thought (CoT) paradigm to Multimodal Large Language Models (MLLMs) by finding visual clues in the input scene, advancing the visual reasoning ability of MLLMs. However, current approaches are specially designed for the tasks where clue finding plays a major role in the whole reasoning process, leading to the difficulty in handling complex visual scenes where clue finding does not actually simplify the whole reasoning task. To deal with this challenge, we propose a new visual reasoning paradigm enabling MLLMs to autonomously modify the input scene to new ones based on its reasoning status, such that CoT is reformulated as conducting simple closed-loop decision-making and reasoning steps under a sequence of imagined visual scenes, leading to natural and general CoT construction. To implement this paradigm, we introduce a novel plug-and-play imagination space, where MLLMs conduct visual modifications through operations like focus, ignore, and transform based on their native reasoning ability without specific training. We validate our approach through a benchmark spanning dense counting, simple jigsaw puzzle solving, and object placement, challenging the reasoning ability beyond clue finding. The results verify that while existing techniques fall short, our approach enables MLLMs to effectively reason step by step through autonomous imagination. Project page: https://future-item.github.io/autoimagine-site.

[Arxiv](https://arxiv.org/abs/2411.18142)