# 大型语言模型与人类价值观的对齐程度有强有弱。

发布时间：2024年08月12日

`LLM理论` `人工智能伦理` `社会影响`

> Strong and weak alignment of large language models with human values

# 摘要

> 在无人监督的情况下，要减少AI系统对人类社会的负面影响，关键在于确保它们与人类价值观相符。当前研究多聚焦于技术改进，如优化基于人类反馈的强化学习，却忽略了实现这一目标的深层含义和必要条件。我们提出区分强弱价值一致性：强一致性要求AI具备理解与推理能力，以识别并避免可能违背人类价值观的情境。通过一系列案例，我们展示了ChatGPT等模型在这方面的不足。进一步分析词嵌入发现，LLMs中的人类价值观表达与人类实际语义存在差异。为此，我们设计了一个新的思想实验——“带有词转换字典的中文房间”，以探讨这一问题。同时，我们也关注到当前研究正朝着实现弱一致性方向发展，虽能在常见情境中提供满意答案，但尚未确保其真实性。

> Minimizing negative impacts of Artificial Intelligent (AI) systems on human societies without human supervision requires them to be able to align with human values. However, most current work only addresses this issue from a technical point of view, e.g., improving current methods relying on reinforcement learning from human feedback, neglecting what it means and is required for alignment to occur. Here, we propose to distinguish strong and weak value alignment. Strong alignment requires cognitive abilities (either human-like or different from humans) such as understanding and reasoning about agents' intentions and their ability to causally produce desired effects. We argue that this is required for AI systems like large language models (LLMs) to be able to recognize situations presenting a risk that human values may be flouted. To illustrate this distinction, we present a series of prompts showing ChatGPT's, Gemini's and Copilot's failures to recognize some of these situations. We moreover analyze word embeddings to show that the nearest neighbors of some human values in LLMs differ from humans' semantic representations. We then propose a new thought experiment that we call "the Chinese room with a word transition dictionary", in extension of John Searle's famous proposal. We finally mention current promising research directions towards a weak alignment, which could produce statistically satisfying answers in a number of common situations, however so far without ensuring any truth value.

[Arxiv](https://arxiv.org/abs/2408.04655)