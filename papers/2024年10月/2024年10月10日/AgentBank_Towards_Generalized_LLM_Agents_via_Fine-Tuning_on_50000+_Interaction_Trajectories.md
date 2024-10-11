# AgentBank：通过微调 50000+ 交互轨迹，打造通用 LLM 代理

发布时间：2024年10月10日

`Agent` `人工智能` `数据集`

> AgentBank: Towards Generalized LLM Agents via Fine-Tuning on 50000+ Interaction Trajectories

# 摘要

> 通过在代理与环境的交互数据上进行微调，我们有望在开源大型语言模型（LLM）中发掘出更广泛的代理能力。我们推出的 AgentBank 是目前最大的轨迹调优数据集，包含超过 5 万条高质量、多样化的交互轨迹，覆盖 16 个任务和五个代理技能维度。借助创新的注释流程，我们成功构建了一个难度偏差极小的轨迹数据集。此外，我们基于 AgentBank 对 LLM 进行微调，开发出一系列名为 Samoyed 的代理模型。实验结果表明，扩展交互数据能有效提升代理的通用能力。进一步的研究还揭示了轨迹调优与代理技能泛化之间的关键联系。

> Fine-tuning on agent-environment interaction trajectory data holds significant promise for surfacing generalized agent capabilities in open-source large language models (LLMs). In this work, we introduce AgentBank, by far the largest trajectory tuning data collection featuring more than 50k diverse high-quality interaction trajectories which comprises 16 tasks covering five distinct agent skill dimensions. Leveraging a novel annotation pipeline, we are able to scale the annotated trajectories and generate a trajectory dataset with minimized difficulty bias. Furthermore, we fine-tune LLMs on AgentBank to get a series of agent models, Samoyed. Our comparative experiments demonstrate the effectiveness of scaling the interaction trajectory data to acquire generalized agent capabilities. Additional studies also reveal some key observations regarding trajectory tuning and agent skill generalization.

[Arxiv](https://arxiv.org/abs/2410.07706)