# AgentOccam：一款简洁却不失强大的 LLM 基础 Web 代理基线

发布时间：2024年10月17日

`Agent` `自动化` `智能代理`

> AgentOccam: A Simple Yet Strong Baseline for LLM-Based Web Agents

# 摘要

> 通过使用大型语言模型 (LLM) 的智能代理，自主完成个性化、标准化的任务，极大地提升了人类的工作效率。自动化网络任务，如在预算内预订酒店，正变得越来越受欢迎。这些网络代理不仅满足了实际需求，还为各种智能代理的应用场景提供了重要的概念验证。然而，先前的研究往往手工设计代理策略，如提示模板、多代理系统、搜索方法等，这些策略在所有现实场景中的泛化能力有限。此外，关于代理的观察/动作表示与 LLM 预训练数据之间的错位研究较少，这在 LLM 主要用于语言完成而非实体导航和符号操作任务时尤为明显。我们的研究通过优化代理的观察和动作空间，使其更好地与 LLM 的能力对齐，从而显著提升了代理在各种网络任务中的表现。在 WebArena 基准测试中，我们的代理 AgentOccam 分别以 9.8 (+29.4%) 和 5.9 (+15.8%) 的绝对分数超越了之前的最先进水平和同期工作，并将类似普通网络代理的成功率提高了 26.6 点 (+161%)。这一成就无需使用上下文示例、新代理角色、在线反馈或搜索策略。AgentOccam 的简单设计突显了 LLM 在网络任务上的惊人零-shot 性能，并强调了仔细调整观察和动作空间对于基于 LLM 的代理的关键作用。

> Autonomy via agents using large language models (LLMs) for personalized, standardized tasks boosts human efficiency. Automating web tasks (like booking hotels within a budget) is increasingly sought after. Fulfilling practical needs, the web agent also serves as an important proof-of-concept example for various agent grounding scenarios, with its success promising advancements in many future applications. Prior research often handcrafts web agent strategies (e.g., prompting templates, multi-agent systems, search methods, etc.) and the corresponding in-context examples, which may not generalize well across all real-world scenarios. On the other hand, there has been limited study on the misalignment between a web agent's observation/action representation and the pre-training data of the LLM it's based on. This discrepancy is especially notable when LLMs are primarily trained for language completion rather than tasks involving embodied navigation actions and symbolic web elements. Our study enhances an LLM-based web agent by simply refining its observation and action space to better align with the LLM's capabilities. This approach enables our base agent to significantly outperform previous methods on a wide variety of web tasks. Specifically, on WebArena, a benchmark featuring general-purpose web interaction tasks, our agent AgentOccam surpasses the previous state-of-the-art and concurrent work by 9.8 (+29.4%) and 5.9 (+15.8%) absolute points respectively, and boosts the success rate by 26.6 points (+161%) over similar plain web agents with its observation and action space alignment. We achieve this without using in-context examples, new agent roles, online feedback or search strategies. AgentOccam's simple design highlights LLMs' impressive zero-shot performance on web tasks, and underlines the critical role of carefully tuning observation and action spaces for LLM-based agents.

[Arxiv](https://arxiv.org/abs/2410.13825)