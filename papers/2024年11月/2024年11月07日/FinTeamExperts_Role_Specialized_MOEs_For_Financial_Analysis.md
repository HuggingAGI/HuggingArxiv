# FinTeamExperts：专为金融分析打造的角色专业化的 MOEs

发布时间：2024年11月07日

`LLM应用` `人工智能`

> FinTeamExperts: Role Specialized MOEs For Financial Analysis

# 摘要

> 像 ChatGPT、Phi3 以及 Llama-3 这样的大型语言模型（LLMs）正在引领人工智能的重大跨越，因为它们无需微调就能将训练所得知识推广应用到新任务中。然而，它们在金融领域的应用相对有限。金融领域本就复杂，从宏观、微观经济趋势到定量分析等各方面都需要深入理解。鉴于这种复杂性，针对特定金融领域定制的专家 LLMs 组合能够为复杂的金融任务提供更全面的认知。在本文中，我们提出了 FinTeamExperts，这是一个用于金融分析的、采用专家混合体（MOEs）结构的角色专业化 LLM 框架。该框架通过训练每个模型专注于不同角色来模拟协作团队环境，即宏观分析师、微观分析师和定量分析师。这种角色专属的专业化提升了模型整合其特定领域专业知识的能力。我们通过在不同语料库上训练三个 80 亿参数的模型来达成此目的，每个模型都致力于在特定金融相关角色中表现卓越。随后，我们针对下游任务对 FinTeamExperts 进行指令微调，使其与实际金融任务相适配。实验结果显示，FinTeamExperts 在四个数据集中的三个上优于所有同规模及更大规模的模型。在第四个更复杂的任务数据集中，FinTeamExperts 依然超越了所有同规模的模型。这彰显了我们基于角色的专业化方法以及 FinTeamExperts 持续训练方法的成功。

> Large Language Models (LLMs), such as ChatGPT, Phi3 and Llama-3, are leading a significant leap in AI, as they can generalize knowledge from their training to new tasks without fine-tuning. However, their application in the financial domain remains relatively limited. The financial field is inherently complex, requiring a deep understanding across various perspectives, from macro, micro economic trend to quantitative analysis. Motivated by this complexity, a mixture of expert LLMs tailored to specific financial domains could offer a more comprehensive understanding for intricate financial tasks. In this paper, we present the FinTeamExperts, a role-specialized LLM framework structured as a Mixture of Experts (MOEs) for financial analysis. The framework simulates a collaborative team setting by training each model to specialize in distinct roles: Macro Analysts, Micro analysts, and Quantitative Analysts. This role-specific specialization enhances the model's ability to integrate their domain-specific expertise. We achieve this by training three 8-billion parameter models on different corpus, each dedicated to excelling in specific finance-related roles. We then instruct-tune FinTeamExperts on downstream tasks to align with practical financial tasks. The experimental results show that FinTeamExperts outperform all models of the same size and larger on three out of four datasets. On the fourth dataset, which presents a more complex task, FinTeamExperts still surpass all models of the same size. This highlights the success of our role-based specialization approach and the continued training approach for FinTeamExperts.

[Arxiv](https://arxiv.org/abs/2410.21338)