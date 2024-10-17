# 探究语言代理在规划过程中面临的挑战

发布时间：2024年10月16日

`Agent` `人工智能` `规划系统`

> Revealing the Barriers of Language Agents in Planning

# 摘要

> 自主规划自人工智能诞生以来一直是研究热点。早期规划系统虽能精准解决特定问题，但缺乏泛化能力。随着大型语言模型（LLM）的崛起，其强大的推理能力为自主规划带来了新希望，能够自动生成合理解决方案。然而，现有研究表明，即便是顶尖的推理模型如 OpenAI o1，在复杂规划任务上的表现也仅达到 15.6%。这引发了一个核心问题：是什么阻碍了语言代理实现人类水平的规划能力？尽管已有研究指出了代理规划的不足，但背后的深层原因及其解决方案的局限性仍未被充分探讨。通过特征归因研究，我们发现了两个关键障碍：约束作用的局限和问题影响力的减弱。虽然现有策略在一定程度上缓解了这些问题，但并未彻底解决，表明语言代理在迈向人类智能的道路上仍任重道远。

> Autonomous planning has been an ongoing pursuit since the inception of artificial intelligence. Based on curated problem solvers, early planning agents could deliver precise solutions for specific tasks but lacked generalization. The emergence of large language models (LLMs) and their powerful reasoning capabilities has reignited interest in autonomous planning by automatically generating reasonable solutions for given tasks. However, prior research and our experiments show that current language agents still lack human-level planning abilities. Even the state-of-the-art reasoning model, OpenAI o1, achieves only 15.6% on one of the complex real-world planning benchmarks. This highlights a critical question: What hinders language agents from achieving human-level planning? Although existing studies have highlighted weak performance in agent planning, the deeper underlying issues and the mechanisms and limitations of the strategies proposed to address them remain insufficiently understood. In this work, we apply the feature attribution study and identify two key factors that hinder agent planning: the limited role of constraints and the diminishing influence of questions. We also find that although current strategies help mitigate these challenges, they do not fully resolve them, indicating that agents still have a long way to go before reaching human-level intelligence.

[Arxiv](https://arxiv.org/abs/2410.12409)