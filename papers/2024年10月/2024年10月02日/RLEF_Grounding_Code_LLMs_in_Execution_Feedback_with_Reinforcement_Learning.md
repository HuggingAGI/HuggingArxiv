# RLEF：通过强化学习，将代码大语言模型与执行反馈相结合

发布时间：2024年10月02日

`Agent` `软件开发` `人工智能`

> RLEF: Grounding Code LLMs in Execution Feedback with Reinforcement Learning

# 摘要

> 部署为代理的 LLM 在解决多步骤任务时，最大限度减少了手动干预。为了确保生成结果的可靠性，LLM 需要基于反馈进行调整。我们提出了一种端到端的强化学习方法，专门用于提升模型在代码合成中的反馈利用能力，这在当前最先进的 LLM 中是一个挑战。通过在竞争性编程任务上的测试，我们不仅在小型和大型模型上都取得了突破性成果，还将所需样本数量大幅减少。分析显示，我们的方法使 LLM 在多步骤任务中更有效地利用自动反馈。

> Large language models (LLMs) deployed as agents solve user-specified tasks over multiple steps while keeping the required manual engagement to a minimum. Crucially, such LLMs need to ground their generations in any feedback obtained to reliably achieve desired outcomes. We propose an end-to-end reinforcement learning method for teaching models to leverage execution feedback in the realm of code synthesis, where state-of-the-art LLMs struggle to improve code iteratively compared to independent sampling. We benchmark on competitive programming tasks, where we achieve new start-of-the art results with both small (8B parameters) and large (70B) models while reducing the amount of samples required by an order of magnitude. Our analysis of inference-time behavior demonstrates that our method produces LLMs that effectively leverage automatic feedback over multiple steps.

[Arxiv](https://arxiv.org/abs/2410.02089)