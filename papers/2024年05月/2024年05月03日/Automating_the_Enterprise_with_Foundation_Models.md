# 借助基础模型，企业自动化之旅启航在人工智能的浪潮中，基础模型如同一座灯塔，引领着企业迈向自动化的未来。它们不仅简化了复杂的业务流程，还开启了创新的大门，让企业在竞争的海洋中乘风破浪。

发布时间：2024年05月03日

`Agent

这篇论文讨论了自动化企业工作流程的挑战，并提出了一个基于多模态基础模型（如GPT-4）的系统（ECLAIR）来实现端到端自动化。它强调了该系统在减少人工干预、提高准确性和降低技术门槛方面的潜力。由于论文主要关注的是一个具体的系统实现，该系统利用了先进的模型（如GPT-4）来作为智能代理执行任务，因此它属于Agent分类。这个分类通常指的是那些能够代表用户执行任务的智能系统或代理。` `企业自动化` `数据管理`

> Automating the Enterprise with Foundation Models

# 摘要

> 自动化企业工作流程有望每年提升4万亿美元的生产力，然而，尽管数据管理界对此关注已久，实现完全自动化的愿景仍未成真。现有的自动化方案依赖于流程挖掘和机器人流程自动化（RPA），这些方案通过硬编码的机器人遵循固定规则来执行任务。我们的案例研究发现，RPA的推广受限于高昂的初始成本、不稳定的执行准确性以及繁琐的维护需求。多模态基础模型（如GPT-4）因其强大的推理和规划能力，为实现端到端自动化提供了新希望。我们提出的ECLAIR系统，能在最小化人工干预的情况下自动化企业流程。初步实验表明，多模态FMs在理解工作流程方面几乎达到人类水平（准确率达93%），并且设置迅速，技术门槛低（仅凭自然语言描述，ECLAIR即能实现40%的端到端任务完成率）。我们认识到人机协作、验证和自我提升是当前的挑战，并提出利用数据管理技术来应对这些挑战。相关代码已公开：https://github.com/HazyResearch/eclair-agents。

> Automating enterprise workflows could unlock $4 trillion/year in productivity gains. Despite being of interest to the data management community for decades, the ultimate vision of end-to-end workflow automation has remained elusive. Current solutions rely on process mining and robotic process automation (RPA), in which a bot is hard-coded to follow a set of predefined rules for completing a workflow. Through case studies of a hospital and large B2B enterprise, we find that the adoption of RPA has been inhibited by high set-up costs (12-18 months), unreliable execution (60% initial accuracy), and burdensome maintenance (requiring multiple FTEs). Multimodal foundation models (FMs) such as GPT-4 offer a promising new approach for end-to-end workflow automation given their generalized reasoning and planning abilities. To study these capabilities we propose ECLAIR, a system to automate enterprise workflows with minimal human supervision. We conduct initial experiments showing that multimodal FMs can address the limitations of traditional RPA with (1) near-human-level understanding of workflows (93% accuracy on a workflow understanding task) and (2) instant set-up with minimal technical barrier (based solely on a natural language description of a workflow, ECLAIR achieves end-to-end completion rates of 40%). We identify human-AI collaboration, validation, and self-improvement as open challenges, and suggest ways they can be solved with data management techniques. Code is available at: https://github.com/HazyResearch/eclair-agents

![借助基础模型，企业自动化之旅启航在人工智能的浪潮中，基础模型如同一座灯塔，引领着企业迈向自动化的未来。它们不仅简化了复杂的业务流程，还开启了创新的大门，让企业在竞争的海洋中乘风破浪。](../../../paper_images/2405.03710/x1.png)

![借助基础模型，企业自动化之旅启航在人工智能的浪潮中，基础模型如同一座灯塔，引领着企业迈向自动化的未来。它们不仅简化了复杂的业务流程，还开启了创新的大门，让企业在竞争的海洋中乘风破浪。](../../../paper_images/2405.03710/Figure_2.png)

[Arxiv](https://arxiv.org/abs/2405.03710)