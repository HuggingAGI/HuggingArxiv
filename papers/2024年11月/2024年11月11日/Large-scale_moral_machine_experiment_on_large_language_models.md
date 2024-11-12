# 大规模语言模型的大规模道德机器实验

发布时间：2024年11月11日

`LLM应用` `自动驾驶` `道德决策`

> Large-scale moral machine experiment on large language models

# 摘要

> 大型语言模型（LLMs）的快速发展及其可能融入自动驾驶系统，这就需要了解它们的道德决策能力。虽然我们之前的研究使用道德机器实验框架对四个著名的 LLMs 进行了检查，但 LLM 发展的动态格局需要更全面的分析。在这里，我们评估了 51 个不同的 LLMs 的道德判断，包括专有模型（GPT、Claude、Gemini）的多个版本和开源替代品（Llama、Gemma），以评估它们在自动驾驶场景中与人类道德偏好的一致性。使用联合分析框架，我们评估了 LLMs 的响应在道德困境中与人类偏好的契合程度，并研究了模型大小、更新和架构的影响。结果表明，超过 100 亿参数的专有模型和开源模型与人类判断表现出相对紧密的一致性，在开源模型中，模型大小与与人类判断的距离之间存在显著的负相关。然而，模型更新并没有始终如一地提高与人类偏好的一致性，许多 LLMs 对特定的道德原则表现出过度强调。这些发现表明，虽然增加模型大小可能自然会导致更像人类的道德判断，但在自动驾驶系统中的实际实施需要仔细考虑判断质量和计算效率之间的权衡。我们的综合分析为自主系统的道德设计提供了关键的见解，并强调了在 AI 道德决策中考虑文化背景的重要性。

> The rapid advancement of Large Language Models (LLMs) and their potential integration into autonomous driving systems necessitates understanding their moral decision-making capabilities. While our previous study examined four prominent LLMs using the Moral Machine experimental framework, the dynamic landscape of LLM development demands a more comprehensive analysis. Here, we evaluate moral judgments across 51 different LLMs, including multiple versions of proprietary models (GPT, Claude, Gemini) and open-source alternatives (Llama, Gemma), to assess their alignment with human moral preferences in autonomous driving scenarios. Using a conjoint analysis framework, we evaluated how closely LLM responses aligned with human preferences in ethical dilemmas and examined the effects of model size, updates, and architecture. Results showed that proprietary models and open-source models exceeding 10 billion parameters demonstrated relatively close alignment with human judgments, with a significant negative correlation between model size and distance from human judgments in open-source models. However, model updates did not consistently improve alignment with human preferences, and many LLMs showed excessive emphasis on specific ethical principles. These findings suggest that while increasing model size may naturally lead to more human-like moral judgments, practical implementation in autonomous driving systems requires careful consideration of the trade-off between judgment quality and computational efficiency. Our comprehensive analysis provides crucial insights for the ethical design of autonomous systems and highlights the importance of considering cultural contexts in AI moral decision-making.

[Arxiv](https://arxiv.org/abs/2411.06790)