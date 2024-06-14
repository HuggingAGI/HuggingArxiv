# StreamBench：助力语言代理持续优化的新基准

发布时间：2024年06月12日

`Agent

这篇论文主要关注的是大型语言模型（LLM）的自我提升能力，特别是在连续输入与反馈循环中的表现。通过引入StreamBench这一基准，研究旨在评估和优化LLM在动态环境中的适应性和学习能力。这种研究方向更偏向于Agent的范畴，因为它涉及到了模型在交互环境中的自主学习和优化行为，这与Agent的概念——即能够自主执行任务并根据环境反馈进行自我调整的智能体——相吻合。因此，将这篇论文归类为Agent是合适的。` `人工智能` `在线学习`

> StreamBench: Towards Benchmarking Continuous Improvement of Language Agents

# 摘要

> 最新研究表明，大型语言模型（LLM）能够通过经验自我提升，这对于部署后的持续优化至关重要。然而，现有评估标准主要关注其初始能力，忽视了它们随时间进化的潜力。为此，我们推出了StreamBench，这一创新基准旨在衡量LLM在连续输入与反馈循环中的自我提升能力。StreamBench构建了一个在线学习模拟环境，让LLM在不断接收反馈的同时，逐步优化性能。我们还设计了几种简明高效的策略，帮助LLM在StreamBench上取得进步。通过深入分析，我们揭示了影响流式策略成功的关键因素。本研究为开发LLM的在线学习策略奠定了基础，推动了流场景下更具适应性的AI系统的发展。

> Recent works have shown that large language model (LLM) agents are able to improve themselves from experience, which is an important ability for continuous enhancement post-deployment. However, existing benchmarks primarily evaluate their innate capabilities and do not assess their ability to improve over time. To address this gap, we introduce StreamBench, a pioneering benchmark designed to evaluate the continuous improvement of LLM agents over an input-feedback sequence. StreamBench simulates an online learning environment where LLMs receive a continuous flow of feedback stream and iteratively enhance their performance. In addition, we propose several simple yet effective baselines for improving LLMs on StreamBench, and provide a comprehensive analysis to identify critical components that contribute to successful streaming strategies. Our work serves as a stepping stone towards developing effective online learning strategies for LLMs, paving the way for more adaptive AI systems in streaming scenarios.

![StreamBench：助力语言代理持续优化的新基准](../../../paper_images/2406.08747/x1.png)

![StreamBench：助力语言代理持续优化的新基准](../../../paper_images/2406.08747/x2.png)

![StreamBench：助力语言代理持续优化的新基准](../../../paper_images/2406.08747/x3.png)

![StreamBench：助力语言代理持续优化的新基准](../../../paper_images/2406.08747/x4.png)

![StreamBench：助力语言代理持续优化的新基准](../../../paper_images/2406.08747/x5.png)

![StreamBench：助力语言代理持续优化的新基准](../../../paper_images/2406.08747/x6.png)

![StreamBench：助力语言代理持续优化的新基准](../../../paper_images/2406.08747/x7.png)

![StreamBench：助力语言代理持续优化的新基准](../../../paper_images/2406.08747/x8.png)

![StreamBench：助力语言代理持续优化的新基准](../../../paper_images/2406.08747/x9.png)

![StreamBench：助力语言代理持续优化的新基准](../../../paper_images/2406.08747/x10.png)

[Arxiv](https://arxiv.org/abs/2406.08747)