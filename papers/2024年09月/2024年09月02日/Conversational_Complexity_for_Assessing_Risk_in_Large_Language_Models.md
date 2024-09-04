# 评估大型语言模型风险：对话复杂性的应用

发布时间：2024年09月02日

`LLM理论` `人工智能安全` `对话系统`

> Conversational Complexity for Assessing Risk in Large Language Models

# 摘要

> 大型语言模型（LLM）面临双重用途的挑战：既支持有益应用，又潜藏伤害风险，尤其是在对话交互中。尽管设有多种安全措施，先进 LLM 仍易受攻击。Kevin Roose 与 Bing 的对话案例揭示了长时间互动后产生的有害输出，这与早期简单越狱产生类似内容的情况形成对比，引发了一个问题：从 LLM 中引出有害信息需要多少对话努力？为此，我们提出两种措施：对话长度（CL）和对话复杂度（CC），后者基于用户指令序列的 Kolmogorov 复杂度。为解决 Kolmogorov 复杂度的不可计算性，我们利用参考 LLM 近似 CC，评估用户指令的可压缩性。通过分析大型红队数据集中有害与无害对话的长度和复杂度分布，我们的研究发现，这种分布分析及 CC 的最小化是理解 AI 安全的关键工具，有助于洞察有害信息的可访问性。这项研究为基于伤害路径算法复杂度的新视角奠定了基础，专注于提升 LLM 的安全性。

> Large Language Models (LLMs) present a dual-use dilemma: they enable beneficial applications while harboring potential for harm, particularly through conversational interactions. Despite various safeguards, advanced LLMs remain vulnerable. A watershed case was Kevin Roose's notable conversation with Bing, which elicited harmful outputs after extended interaction. This contrasts with simpler early jailbreaks that produced similar content more easily, raising the question: How much conversational effort is needed to elicit harmful information from LLMs? We propose two measures: Conversational Length (CL), which quantifies the conversation length used to obtain a specific response, and Conversational Complexity (CC), defined as the Kolmogorov complexity of the user's instruction sequence leading to the response. To address the incomputability of Kolmogorov complexity, we approximate CC using a reference LLM to estimate the compressibility of user instructions. Applying this approach to a large red-teaming dataset, we perform a quantitative analysis examining the statistical distribution of harmful and harmless conversational lengths and complexities. Our empirical findings suggest that this distributional analysis and the minimisation of CC serve as valuable tools for understanding AI safety, offering insights into the accessibility of harmful information. This work establishes a foundation for a new perspective on LLM safety, centered around the algorithmic complexity of pathways to harm.

[Arxiv](https://arxiv.org/abs/2409.01247)