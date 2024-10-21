# LoGU：长篇生成中的不确定性表达

发布时间：2024年10月18日

`LLM应用` `人工智能`

> LoGU: Long-form Generation with Uncertainty Expressions

# 摘要

> 尽管 LLM 表现出色，但在生成事实错误内容（幻觉）方面仍有不足。让模型在不确定时表达不确定性是一个有前景的解决方案。以往研究多聚焦于短问答，而现实应用常需更长回答。我们提出了长形式生成不确定性 (LoGU) 任务，并识别了两个关键挑战：不确定性抑制和错位。为此，我们设计了基于细化的数据收集框架和两阶段训练管道，采用分而治之策略细化不确定性，并通过 SFT 和 DPO 增强表达。实验表明，该方法显著提升准确性，减少幻觉，并保持回答的全面性。

> While Large Language Models (LLMs) demonstrate impressive capabilities, they still struggle with generating factually incorrect content (i.e., hallucinations). A promising approach to mitigate this issue is enabling models to express uncertainty when unsure. Previous research on uncertainty modeling has primarily focused on short-form QA, but realworld applications often require much longer responses. In this work, we introduce the task of Long-form Generation with Uncertainty(LoGU). We identify two key challenges: Uncertainty Suppression, where models hesitate to express uncertainty, and Uncertainty Misalignment, where models convey uncertainty inaccurately. To tackle these challenges, we propose a refinement-based data collection framework and a two-stage training pipeline. Our framework adopts a divide-and-conquer strategy, refining uncertainty based on atomic claims. The collected data are then used in training through supervised fine-tuning (SFT) and direct preference optimization (DPO) to enhance uncertainty expression. Extensive experiments on three long-form instruction following datasets show that our method significantly improves accuracy, reduces hallucinations, and maintains the comprehensiveness of responses.

[Arxiv](https://arxiv.org/abs/2410.14309)