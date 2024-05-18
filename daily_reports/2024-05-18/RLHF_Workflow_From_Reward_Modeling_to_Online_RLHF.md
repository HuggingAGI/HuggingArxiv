# 强化学习与人类反馈（RLHF）的工作流程：从奖励模型构建到在线RLHF应用，这一流程展示了如何将人类偏好融入机器学习模型中，以优化其行为。
发布时间：2024年05月13日

`动手训练`
> RLHF Workflow: From Reward Modeling to Online RLHF
>
> 本报告详述了在线迭代人类反馈强化学习（RLHF）的流程，该方法在大型语言模型（LLM）领域中，其性能显著超越离线版本。尽管如此，开源的RLHF项目仍多局限于离线学习。为此，我们提供了一套易于复制的在线迭代RLHF方案，特别针对资源有限的开源社区，我们利用多样化的开源数据集构建偏好模型，以此模拟人类反馈。报告深入探讨了RLHF的理论基础和算法设计，并提供了实际操作指南。我们的LLM模型SFR-Iterative-DPO-LLaMA-3-8B-R在多个LLM聊天机器人测试中表现卓越，包括AlpacaEval-2、Arena-Hard、MT-Bench等，以及学术测试如HumanEval和TruthfulQA。我们证明了通过监督微调和迭代RLHF，可以利用全开源数据集达到业界顶尖水平。此外，我们已将模型、数据集和详尽的代码指南公开，详情请访问https://github.com/RLHFlow/RLHF-Reward-Modeling和https://github.com/RLHFlow/Online-RLHF。
>
> https://arxiv.org/abs/2405.07863


<hr />

- 论文原文: [https://arxiv.org/abs/2405.07863](https://arxiv.org/abs/2405.07863)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886