# AMPO：自动多分支提示优化

发布时间：2024年10月11日

`LLM应用` `人工智能` `软件工程`

> AMPO: Automatic Multi-Branched Prompt Optimization

# 摘要

> 提示工程对提升LLM性能至关重要。面对复杂问题，提示工程师会从示例中提炼多种模式，并注入相关解决方案以优化提示，从而获得满意结果。然而，现有自动提示优化技术仅能生成单一指令，难以应对多样化模式。本文提出AMPO，一种利用失败案例反馈迭代开发多分支提示的自动优化方法。我们探索了多分支提示结构，以更好处理复杂任务中的多种模式，并引入模式识别、分支调整和分支修剪三个模块。实验结果显示，AMPO在五个任务中始终表现最佳，且因采用最小搜索策略，优化效率显著提升。

> Prompt engineering is very important to enhance the performance of large language models (LLMs). When dealing with complex issues, prompt engineers tend to distill multiple patterns from examples and inject relevant solutions to optimize the prompts, achieving satisfying results. However, existing automatic prompt optimization techniques are only limited to producing single flow instructions, struggling with handling diverse patterns. In this paper, we present AMPO, an automatic prompt optimization method that can iteratively develop a multi-branched prompt using failure cases as feedback. Our goal is to explore a novel way of structuring prompts with multi-branches to better handle multiple patterns in complex tasks, for which we introduce three modules: Pattern Recognition, Branch Adjustment, and Branch Pruning. In experiments across five tasks, AMPO consistently achieves the best results. Additionally, our approach demonstrates significant optimization efficiency due to our adoption of a minimal search strategy.

[Arxiv](https://arxiv.org/abs/2410.08696)