# 你支持哪一方？一款专为端到端论证摘要与评估打造的多任务数据集

发布时间：2024年06月05日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）技术来构建一个自动化辩论系统，并介绍了一个专门为此目的设计的辩论论据挖掘数据集。论文中提到的任务（如论点与证据的识别、证据说服力的排序等）都是具体的应用场景，旨在通过LLMs技术解决实际问题，而不是探讨LLMs的理论基础或Agent的设计与实现。因此，这篇论文更适合归类于LLM应用。`

> Which Side Are You On? A Multi-task Dataset for End-to-End Argument Summarisation and Evaluation

# 摘要

> 随着大型语言模型（LLMs）技术的飞跃，打造一个助力人们构建有力论点的自动化辩论系统已触手可及。以往的研究通过多组件整合尝试攻克此难题。我们团队推出了一款辩论论据挖掘数据集，它详尽记录了辩论议论文的筹备全程，包括论点与证据的识别（任务1 ED）、证据说服力的排序（任务2 ECR）、议论文摘要与人类偏好排序（任务3 ASR），以及基于论据质量反馈的自动化评估指标学习（任务4 SQE）。该数据集囊括了14,000个论点示例，每个示例均精细标注了支持各项任务的属性。我们对多个生成式模型进行了评估，包括顶尖的LLMs，发现尽管它们在单项任务上表现出色，但连续完成四项任务时，整体性能却大幅下滑，无论是机器评分还是人类评估均如此。这一挑战激发了未来对端到端论据挖掘与摘要技术的深入研究。项目代码库已开放，地址为：https://github.com/HarrywillDr/ArgSum-Datatset。

> With the recent advances of large language models (LLMs), it is no longer infeasible to build an automated debate system that helps people to synthesise persuasive arguments. Previous work attempted this task by integrating multiple components. In our work, we introduce an argument mining dataset that captures the end-to-end process of preparing an argumentative essay for a debate, which covers the tasks of claim and evidence identification (Task 1 ED), evidence convincingness ranking (Task 2 ECR), argumentative essay summarisation and human preference ranking (Task 3 ASR) and metric learning for automated evaluation of resulting essays, based on human feedback along argument quality dimensions (Task 4 SQE). Our dataset contains 14k examples of claims that are fully annotated with the various properties supporting the aforementioned tasks. We evaluate multiple generative baselines for each of these tasks, including representative LLMs. We find, that while they show promising results on individual tasks in our benchmark, their end-to-end performance on all four tasks in succession deteriorates significantly, both in automated measures as well as in human-centred evaluation. This challenge presented by our proposed dataset motivates future research on end-to-end argument mining and summarisation. The repository of this project is available at https://github.com/HarrywillDr/ArgSum-Datatset

![你支持哪一方？一款专为端到端论证摘要与评估打造的多任务数据集](../../../paper_images/2406.03151/x1.png)

![你支持哪一方？一款专为端到端论证摘要与评估打造的多任务数据集](../../../paper_images/2406.03151/projectdebater_summary.png)

[Arxiv](https://arxiv.org/abs/2406.03151)