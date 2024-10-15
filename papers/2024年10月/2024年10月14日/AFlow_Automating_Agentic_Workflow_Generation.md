# AFlow：智能自动化工作流生成

发布时间：2024年10月14日

`LLM应用` `人工智能` `软件工程`

> AFlow: Automating Agentic Workflow Generation

# 摘要

> 大型语言模型（LLM）在跨领域复杂任务中展现了巨大潜力，但构建其工作流程需大量人力，限制了扩展性和通用性。近期研究虽尝试自动化生成与优化，仍依赖初始手动设置，未能实现全自动化。为此，我们将工作流程优化视为代码表示的搜索问题，并推出 AFlow 框架，利用蒙特卡洛树搜索高效探索，通过代码修改、树结构经验及执行反馈迭代优化。实证评估显示，AFlow 在六个基准数据集上平均提升 5.7%，且使小模型以 GPT-4o 4.55% 的成本在特定任务上超越 GPT-4o。代码即将在 https://github.com/geekan/MetaGPT 发布。

> Large language models (LLMs) have demonstrated remarkable potential in solving complex tasks across diverse domains, typically by employing agentic workflows that follow detailed instructions and operational sequences. However, constructing these workflows requires significant human effort, limiting scalability and generalizability. Recent research has sought to automate the generation and optimization of these workflows, but existing methods still rely on initial manual setup and fall short of achieving fully automated and effective workflow generation. To address this challenge, we reformulate workflow optimization as a search problem over code-represented workflows, where LLM-invoking nodes are connected by edges. We introduce AFlow, an automated framework that efficiently explores this space using Monte Carlo Tree Search, iteratively refining workflows through code modification, tree-structured experience, and execution feedback. Empirical evaluations across six benchmark datasets demonstrate AFlow's efficacy, yielding a 5.7% average improvement over state-of-the-art baselines. Furthermore, AFlow enables smaller models to outperform GPT-4o on specific tasks at 4.55% of its inference cost in dollars. The code will be available at https://github.com/geekan/MetaGPT.

[Arxiv](https://arxiv.org/abs/2410.10762)