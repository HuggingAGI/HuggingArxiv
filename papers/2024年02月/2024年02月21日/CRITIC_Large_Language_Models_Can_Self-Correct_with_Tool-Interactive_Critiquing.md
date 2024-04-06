# CRITIC 研究：大型语言模型能通过与工具的互动批评实现自我修正。

发布时间：2024年02月21日

`LLM应用` `人工智能` `自动化验证`

> CRITIC: Large Language Models Can Self-Correct with Tool-Interactive Critiquing

# 摘要

> 近期大型语言模型（LLMs）的进展令人瞩目。然而，这些模型偶尔会出现矛盾和问题行为，比如虚构事实、编写错误代码或产生攻击性内容。与人类不同，人类通常会借助外部工具来核实和优化他们的内容，例如利用搜索引擎核实事实，或使用代码解释器进行调试。基于这一发现，我们提出了一个名为CRITIC的框架，它使得本质上不透明的LLMs能够像人类使用工具那样，验证并逐步改进自己的输出。具体来说，CRITIC从初始输出出发，与相关工具互动，评估文本的特定方面，然后根据验证过程中收到的反馈进行调整。通过自由问答、数学程序合成和降低内容毒性的全面评估，我们发现CRITIC能够持续提升LLMs的表现。此外，研究还突显了外部反馈对于推动LLMs不断自我完善的至关重要性。

> Recent developments in large language models (LLMs) have been impressive. However, these models sometimes show inconsistencies and problematic behavior, such as hallucinating facts, generating flawed code, or creating offensive and toxic content. Unlike these models, humans typically utilize external tools to cross-check and refine their initial content, like using a search engine for fact-checking, or a code interpreter for debugging. Inspired by this observation, we introduce a framework called CRITIC that allows LLMs, which are essentially "black boxes" to validate and progressively amend their own outputs in a manner similar to human interaction with tools. More specifically, starting with an initial output, CRITIC interacts with appropriate tools to evaluate certain aspects of the text, and then revises the output based on the feedback obtained during this validation process. Comprehensive evaluations involving free-form question answering, mathematical program synthesis, and toxicity reduction demonstrate that CRITIC consistently enhances the performance of LLMs. Meanwhile, our research highlights the crucial importance of external feedback in promoting the ongoing self-improvement of LLMs.

[Arxiv](https://arxiv.org/abs/2305.11738)