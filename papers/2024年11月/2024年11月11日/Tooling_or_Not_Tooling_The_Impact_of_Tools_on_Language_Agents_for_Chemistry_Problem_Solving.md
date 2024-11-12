# 工具化还是不工具化？工具对解决化学问题的语言代理的影响

发布时间：2024年11月11日

`Agent` `语言模型`

> Tooling or Not Tooling? The Impact of Tools on Language Agents for Chemistry Problem Solving

# 摘要

> 为了增强用于解决化学问题的大型语言模型（LLM），已经提出了几个基于 LLM 并配备工具的代理，例如 ChemCrow 和 Coscientist。然而，它们的评估范围狭窄，在理解工具在各种化学任务中的益处方面存在很大差距。为了弥补这一差距，我们开发了 ChemAgent，这是在 ChemCrow 基础上增强的化学代理，并对其在专业化学任务和一般化学问题上的性能进行了全面评估。令人惊讶的是，ChemAgent 并非始终优于没有工具的基础 LLM。我们与化学专家进行的错误分析表明：对于诸如合成预测之类的专业化学任务，我们应该为代理配备专门的工具；然而，对于像考试中的一般化学问题，代理凭借化学知识正确推理的能力更重要，工具增强并不总是有帮助。

> To enhance large language models (LLMs) for chemistry problem solving, several LLM-based agents augmented with tools have been proposed, such as ChemCrow and Coscientist. However, their evaluations are narrow in scope, leaving a large gap in understanding the benefits of tools across diverse chemistry tasks. To bridge this gap, we develop ChemAgent, an enhanced chemistry agent over ChemCrow, and conduct a comprehensive evaluation of its performance on both specialized chemistry tasks and general chemistry questions. Surprisingly, ChemAgent does not consistently outperform its base LLMs without tools. Our error analysis with a chemistry expert suggests that: For specialized chemistry tasks, such as synthesis prediction, we should augment agents with specialized tools; however, for general chemistry questions like those in exams, agents' ability to reason correctly with chemistry knowledge matters more, and tool augmentation does not always help.

[Arxiv](https://arxiv.org/abs/2411.07228)