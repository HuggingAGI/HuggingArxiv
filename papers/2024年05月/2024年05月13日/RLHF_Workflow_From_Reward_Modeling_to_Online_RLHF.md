# 强化学习与人类反馈（RLHF）的工作流程：从奖励模型构建到在线RLHF应用，这一流程展示了如何将人类偏好融入机器学习模型中，以优化其行为。

发布时间：2024年05月13日

`LLM应用

这篇论文摘要描述了一个在线迭代人类反馈强化学习（RLHF）的流程，并展示了其在大型语言模型（LLM）中的应用效果。它提供了一个易于复制的方案，并详细讨论了RLHF的理论基础、算法设计以及实际操作指南。此外，论文还展示了其LLM模型在多个测试中的卓越表现，并公开了模型、数据集和代码指南。这些内容表明该论文主要关注的是LLM的应用层面，特别是通过RLHF方法提升LLM性能的实际应用。因此，它属于LLM应用分类。` `人工智能`

> RLHF Workflow: From Reward Modeling to Online RLHF

# 摘要

> 本报告详述了在线迭代人类反馈强化学习（RLHF）的流程，该方法在大型语言模型（LLM）领域中，其性能显著超越离线版本。尽管如此，开源的RLHF项目仍多局限于离线学习。为此，我们提供了一套易于复制的在线迭代RLHF方案，特别针对资源有限的开源社区，我们利用多样化的开源数据集构建偏好模型，以此模拟人类反馈。报告深入探讨了RLHF的理论基础和算法设计，并提供了实际操作指南。我们的LLM模型SFR-Iterative-DPO-LLaMA-3-8B-R在多个LLM聊天机器人测试中表现卓越，包括AlpacaEval-2、Arena-Hard、MT-Bench等，以及学术测试如HumanEval和TruthfulQA。我们证明了通过监督微调和迭代RLHF，可以利用全开源数据集达到业界顶尖水平。此外，我们已将模型、数据集和详尽的代码指南公开，详情请访问https://github.com/RLHFlow/RLHF-Reward-Modeling和https://github.com/RLHFlow/Online-RLHF。

> We present the workflow of Online Iterative Reinforcement Learning from Human Feedback (RLHF) in this technical report, which is widely reported to outperform its offline counterpart by a large margin in the recent large language model (LLM) literature. However, existing open-source RLHF projects are still largely confined to the offline learning setting. In this technical report, we aim to fill in this gap and provide a detailed recipe that is easy to reproduce for online iterative RLHF. In particular, since online human feedback is usually infeasible for open-source communities with limited resources, we start by constructing preference models using a diverse set of open-source datasets and use the constructed proxy preference model to approximate human feedback. Then, we discuss the theoretical insights and algorithmic principles behind online iterative RLHF, followed by a detailed practical implementation. Our trained LLM, SFR-Iterative-DPO-LLaMA-3-8B-R, achieves impressive performance on LLM chatbot benchmarks, including AlpacaEval-2, Arena-Hard, and MT-Bench, as well as other academic benchmarks such as HumanEval and TruthfulQA. We have shown that supervised fine-tuning (SFT) and iterative RLHF can obtain state-of-the-art performance with fully open-source datasets. Further, we have made our models, curated datasets, and comprehensive step-by-step code guidebooks publicly available. Please refer to https://github.com/RLHFlow/RLHF-Reward-Modeling and https://github.com/RLHFlow/Online-RLHF for more detailed information.

[Arxiv](https://arxiv.org/abs/2405.07863)