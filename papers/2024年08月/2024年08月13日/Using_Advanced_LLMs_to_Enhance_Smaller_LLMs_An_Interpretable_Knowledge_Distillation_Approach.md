# 借助高级 LLM 提升小型 LLM 性能：探索可解释的知识蒸馏途径

发布时间：2024年08月13日

`LLM应用` `客户服务` `人工智能`

> Using Advanced LLMs to Enhance Smaller LLMs: An Interpretable Knowledge Distillation Approach

# 摘要

> GPT-4 或 LlaMa 3 等高级 LLM 在模拟人类复杂交互中表现卓越，但高成本和体积庞大使其不适用于智能手机等边缘设备，且自我托管难度大，引发安全和隐私问题。本文提出一种创新的可解释知识蒸馏法，旨在优化小型、经济的 LLM，便于企业自我托管。我们专注于通过目标导向对话提升客户满意度的客服代理构建。不同于传统蒸馏中“学生”模型直接从“教师”模型学习，我们的“策略”教学法让教师提供策略，提升学生在多场景中的表现。此方法通过交替的“场景生成”和“改进策略”步骤，定制场景库和优化策略，仅需黑箱访问模型，无需调整参数。在客服应用中，该方法不仅提升性能，学到的策略还可跨 LLM 和场景应用，其可解释性通过人工审计增强安全性。

> Advanced Large language models (LLMs) like GPT-4 or LlaMa 3 provide superior performance in complex human-like interactions. But they are costly, or too large for edge devices such as smartphones and harder to self-host, leading to security and privacy concerns. This paper introduces a novel interpretable knowledge distillation approach to enhance the performance of smaller, more economical LLMs that firms can self-host. We study this problem in the context of building a customer service agent aimed at achieving high customer satisfaction through goal-oriented dialogues. Unlike traditional knowledge distillation, where the "student" model learns directly from the "teacher" model's responses via fine-tuning, our interpretable "strategy" teaching approach involves the teacher providing strategies to improve the student's performance in various scenarios. This method alternates between a "scenario generation" step and a "strategies for improvement" step, creating a customized library of scenarios and optimized strategies for automated prompting. The method requires only black-box access to both student and teacher models; hence it can be used without manipulating model parameters. In our customer service application, the method improves performance, and the learned strategies are transferable to other LLMs and scenarios beyond the training set. The method's interpretabilty helps safeguard against potential harms through human audit.

[Arxiv](https://arxiv.org/abs/2408.07238)