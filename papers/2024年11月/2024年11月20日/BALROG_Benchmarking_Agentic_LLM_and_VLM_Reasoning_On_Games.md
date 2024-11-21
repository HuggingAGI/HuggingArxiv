# BALROG：针对游戏中的智能体语言模型和视觉语言模型推理展开基准测试

发布时间：2024年11月20日

`LLM应用`

> BALROG: Benchmarking Agentic LLM and VLM Reasoning On Games

# 摘要

> 大型语言模型（LLMs）和视觉语言模型（VLMs）知识丰富，推理能力可期，但在复杂动态的环境中表现欠佳。现实任务需要应对复杂交互、高级空间推理、长期规划以及对新策略的持续探索，而在这些方面，我们缺少全面评估这些能力的有效方法。为此，我们推出了 BALROG 这一新基准，通过一系列富有挑战性的游戏来评估 LLMs 和 VLMs 的智能能力。该基准融合了各种不同难度的现有强化学习环境，涵盖了非专业人员几秒内就能搞定的任务，以及可能需要数年才能攻克的超高难度任务（比如 NetHack 学习环境）。我们制定了精细的指标来衡量性能，并对几款热门的开源和闭源 LLMs 及 VLMs 展开了广泛评估。研究发现，当前模型在较简单的游戏中能取得一定成绩，但面对更具挑战的任务就力不从心了。尤其值得注意的是，基于视觉的决策存在严重不足，当提供环境的视觉呈现时，模型表现更糟。我们将 BALROG 作为一个开放且易用的基准发布，以推动智能领域未来的研究与发展。

> Large Language Models (LLMs) and Vision Language Models (VLMs) possess extensive knowledge and exhibit promising reasoning abilities; however, they still struggle to perform well in complex, dynamic environments. Real-world tasks require handling intricate interactions, advanced spatial reasoning, long-term planning, and continuous exploration of new strategies-areas in which we lack effective methodologies for comprehensively evaluating these capabilities. To address this gap, we introduce BALROG, a novel benchmark designed to assess the agentic capabilities of LLMs and VLMs through a diverse set of challenging games. Our benchmark incorporates a range of existing reinforcement learning environments with varying levels of difficulty, including tasks that are solvable by non-expert humans in seconds to extremely challenging ones that may take years to master (e.g., the NetHack Learning Environment). We devise fine-grained metrics to measure performance and conduct an extensive evaluation of several popular open-source and closed-source LLMs and VLMs. Our findings indicate that while current models achieve partial success in the easier games, they struggle significantly with more challenging tasks. Notably, we observe severe deficiencies in vision-based decision-making, as models perform worse when visual representations of the environments are provided. We release BALROG as an open and user-friendly benchmark to facilitate future research and development in the agentic community.

[Arxiv](https://arxiv.org/abs/2411.13543)