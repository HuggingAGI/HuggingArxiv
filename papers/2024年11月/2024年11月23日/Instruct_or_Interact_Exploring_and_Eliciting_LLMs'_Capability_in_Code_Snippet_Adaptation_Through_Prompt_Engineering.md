# 是指导还是交互？借助提示工程探索并激发大型语言模型在代码片段适应中的能力

发布时间：2024年11月23日

`LLM应用` `软件开发` `代码适配`

> Instruct or Interact? Exploring and Eliciting LLMs' Capability in Code Snippet Adaptation Through Prompt Engineering

# 摘要

> 代码片段适配乃是软件开发流程中的一项基础活动。和代码生成不同，代码片段适配并非“自由创作”，它需要开发者对给定的代码片段加以调整，以契合特定需求和代码语境。近来，大型语言模型（LLMs）在代码生成任务中已彰显出有效性，成果斐然。然而，它们在适配（一个面向复用且依赖上下文的代码变更预测任务）方面的表现尚不明确。为填补这一空缺，我们展开了一项实证研究，以探究LLMs在适配任务中的性能与问题。我们先是评估了三个热门LLMs的适配性能，并将其与代码生成任务作对比。结果显示，它们的适配能力逊于生成能力，pass@1近乎降低15%，且存在更多与上下文相关的错误。通过人工检查200个案例，我们进一步探究了LLMs表现欠佳的原因，可归为三类，即需求不明、需求错位和上下文运用不当。基于上述实证研究，我们提出了一种交互式提示方法来激发LLMs的适配能力。实验结果表明，我们的方法大幅提升了LLMs的适配性能。表现最优的人类-LLM交互成功解决了202个已识别缺陷中的159个，pass@1和pass@5较初始基于指令的提示提升了40%以上。考虑到人力投入，我们建议采用多智能体交互作为平衡之选，其能够达成相当的性能，且具备出色的泛化能力。我们认为，我们的方法能够为借助LLMs实现自主代码片段的复用和适配提供方法上的助力。

> Code snippet adaptation is a fundamental activity in the software development process. Unlike code generation, code snippet adaptation is not a "free creation", which requires developers to tailor a given code snippet in order to fit specific requirements and the code context. Recently, large language models (LLMs) have confirmed their effectiveness in the code generation task with promising results. However, their performance on adaptation, a reuse-oriented and context-dependent code change prediction task, is still unclear. To bridge this gap, we conduct an empirical study to investigate the performance and issues of LLMs on the adaptation task. We first evaluate the adaptation performances of three popular LLMs and compare them to the code generation task. Our result indicates that their adaptation ability is weaker than generation, with a nearly 15% decrease on pass@1 and more context-related errors. By manually inspecting 200 cases, we further investigate the causes of LLMs' sub-optimal performance, which can be classified into three categories, i.e., Unclear Requirement, Requirement Misalignment and Context Misapplication. Based on the above empirical research, we propose an interactive prompting approach to eliciting LLMs' adaptation ability. Experimental result reveals that our approach greatly improve LLMs' adaptation performance. The best-performing Human-LLM interaction successfully solves 159 out of the 202 identified defects and improves the pass@1 and pass@5 by over 40% compared to the initial instruction-based prompt. Considering human efforts, we suggest multi-agent interaction as a trade-off, which can achieve comparable performance with excellent generalization ability. We deem that our approach could provide methodological assistance for autonomous code snippet reuse and adaptation with LLMs.

[Arxiv](https://arxiv.org/abs/2411.15501)