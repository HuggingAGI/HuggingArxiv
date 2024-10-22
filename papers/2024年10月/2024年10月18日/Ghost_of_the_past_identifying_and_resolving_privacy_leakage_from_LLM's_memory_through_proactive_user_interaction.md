# “过去的幽灵”：通过主动用户交互，识别并解决 LLM 内存中的隐私泄露问题。

发布时间：2024年10月18日

`LLM应用` `隐私保护` `人工智能`

> "Ghost of the past": identifying and resolving privacy leakage from LLM's memory through proactive user interaction

# 摘要

> 在人类与大型语言模型（LLM）的互动中，记忆（包括上下文窗口中的过去输入和检索增强生成）频繁出现，但用户往往忽视了这些记忆及其潜在的隐私风险。为此，我们推出了 MemoAnalyzer，一个专门用于识别、可视化和管理记忆中私人信息的系统。通过半结构化访谈（40 名参与者），我们发现隐私意识不足是主要问题，而主动隐私控制成为用户最迫切的需求。MemoAnalyzer 采用基于提示的方法，从过往输入中推断并识别敏感信息，使用户能轻松修改敏感内容。系统通过背景颜色温度和透明度来反映推理的置信度和敏感度，简化了隐私调整过程。为期五天的评估（36 名参与者）显示，与默认 GPT 设置和手动修改基线相比，MemoAnalyzer 在不影响交互速度的前提下，显著提升了隐私意识和保护。我们的研究为注重隐私的 LLM 设计提供了宝贵见解，助力于人类与 AI 交互中的隐私保护。

> Memories, encompassing past inputs in context window and retrieval-augmented generation (RAG), frequently surface during human-LLM interactions, yet users are often unaware of their presence and the associated privacy risks. To address this, we propose MemoAnalyzer, a system for identifying, visualizing, and managing private information within memories. A semi-structured interview (N=40) revealed that low privacy awareness was the primary challenge, while proactive privacy control emerged as the most common user need. MemoAnalyzer uses a prompt-based method to infer and identify sensitive information from aggregated past inputs, allowing users to easily modify sensitive content. Background color temperature and transparency are mapped to inference confidence and sensitivity, streamlining privacy adjustments. A 5-day evaluation (N=36) comparing MemoAnalyzer with the default GPT setting and a manual modification baseline showed MemoAnalyzer significantly improved privacy awareness and protection without compromising interaction speed. Our study contributes to privacy-conscious LLM design, offering insights into privacy protection for Human-AI interactions.

[Arxiv](https://arxiv.org/abs/2410.14931)