# 聚焦 ReAct：通过反复迭代与早期停止提升 ReAct 性能

发布时间：2024年10月14日

`LLM应用` `人工智能` `软件开发`

> Focused ReAct: Improving ReAct through Reiterate and Early Stop

# 摘要

> LLM 的推理和决策能力在 ReAct 等方法中显著提升。然而，ReAct 虽有效，却易失焦和陷入循环。为此，我们推出 Focused ReAct，通过重复和早期停止机制，助模型保持专注，避免重复。实验显示，准确性提升 18% 至 530%，运行时间缩短达 34%。

> Large language models (LLMs) have significantly improved their reasoning and decision-making capabilities, as seen in methods like ReAct. However, despite its effectiveness in tackling complex tasks, ReAct faces two main challenges: losing focus on the original question and becoming stuck in action loops. To address these issues, we introduce Focused ReAct, an enhanced version of the ReAct paradigm that incorporates reiteration and early stop mechanisms. These improvements help the model stay focused on the original query and avoid repetitive behaviors. Experimental results show accuracy gains of 18% to 530% and a runtime reduction of up to 34% compared to the original ReAct method.

[Arxiv](https://arxiv.org/abs/2410.10779)