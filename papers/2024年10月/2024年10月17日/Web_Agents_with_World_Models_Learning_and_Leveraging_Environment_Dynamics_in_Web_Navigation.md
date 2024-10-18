# 网络代理通过世界模型学习并利用环境动态，以优化网络导航。

发布时间：2024年10月17日

`Agent` `人工智能` `软件开发`

> Web Agents with World Models: Learning and Leveraging Environment Dynamics in Web Navigation

# 摘要

> 大型语言模型 (LLM) 在构建自主代理方面备受瞩目，但其在长期任务中的表现仍不尽如人意，常犯下如反复购买不可退机票的错误。人类则能避免此类失误，因为我们具备对行动后果的预见能力，即“世界模型”。本研究首先确认当前 LLM（如 GPT-4o、Claude-3.5-Sonnet 等）缺乏此模型。随后，我们设计了世界模型增强 (WMA) 网络代理，通过模拟行动结果优化决策。为应对训练 LLM 预测观察结果的挑战，如重复元素和长 HTML 输入，我们提出了一种专注于状态变化的观察抽象方法。实验显示，我们的世界模型无需额外训练即可提升代理策略选择，并在成本和时间效率上优于基于树搜索的代理。

> Large language models (LLMs) have recently gained much attention in building autonomous agents. However, the performance of current LLM-based web agents in long-horizon tasks is far from optimal, often yielding errors such as repeatedly buying a non-refundable flight ticket. By contrast, humans can avoid such an irreversible mistake, as we have an awareness of the potential outcomes (e.g., losing money) of our actions, also known as the "world model". Motivated by this, our study first starts with preliminary analyses, confirming the absence of world models in current LLMs (e.g., GPT-4o, Claude-3.5-Sonnet, etc.). Then, we present a World-model-augmented (WMA) web agent, which simulates the outcomes of its actions for better decision-making. To overcome the challenges in training LLMs as world models predicting next observations, such as repeated elements across observations and long HTML inputs, we propose a transition-focused observation abstraction, where the prediction objectives are free-form natural language descriptions exclusively highlighting important state differences between time steps. Experiments on WebArena and Mind2Web show that our world models improve agents' policy selection without training and demonstrate our agents' cost- and time-efficiency compared to recent tree-search-based agents.

[Arxiv](https://arxiv.org/abs/2410.13232)