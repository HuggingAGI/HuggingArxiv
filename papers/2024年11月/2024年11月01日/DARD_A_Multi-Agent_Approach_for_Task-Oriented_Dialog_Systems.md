# DARD：一种用于任务导向型对话系统的多智能体方法

发布时间：2024年11月01日

`Agent` `客户服务` `个人助理`

> DARD: A Multi-Agent Approach for Task-Oriented Dialog Systems

# 摘要

> 任务导向的对话系统在诸如客户服务、个人助理等应用中不可或缺，在各行业广泛运用。然而，因要处理多个领域中各异的用户意图、实体类型和特定领域知识，开发有效的多领域系统仍是重大挑战。在此工作中，我们提出了 DARD（领域分配响应委托），这是一个能成功处理多领域对话的多智能体对话系统。DARD 借助由中央对话管理器智能体协调的特定领域智能体。我们大量的实验对比并运用了各类智能体建模方式，把较小的微调模型（Flan-T5-large 与 Mistral-7B）的长处和大型语言模型（LLMs）（Claude Sonnet 3.0）相结合。我们给出了每种方式的优劣见解，突显了我们的多智能体框架在灵活性和可组合性方面的优势。我们用成熟的 MultiWOZ 基准来评估 DARD，将对话信息率提升 6.6%，成功率提高 4.1%，超越了现有最佳方法，达成了顶尖性能。另外，我们还探讨了 MultiWOZ 数据集中及其评估系统里的各种注释者差异和问题。

> Task-oriented dialogue systems are essential for applications ranging from customer service to personal assistants and are widely used across various industries. However, developing effective multi-domain systems remains a significant challenge due to the complexity of handling diverse user intents, entity types, and domain-specific knowledge across several domains. In this work, we propose DARD (Domain Assigned Response Delegation), a multi-agent conversational system capable of successfully handling multi-domain dialogs. DARD leverages domain-specific agents, orchestrated by a central dialog manager agent. Our extensive experiments compare and utilize various agent modeling approaches, combining the strengths of smaller fine-tuned models (Flan-T5-large & Mistral-7B) with their larger counterparts, Large Language Models (LLMs) (Claude Sonnet 3.0). We provide insights into the strengths and limitations of each approach, highlighting the benefits of our multi-agent framework in terms of flexibility and composability. We evaluate DARD using the well-established MultiWOZ benchmark, achieving state-of-the-art performance by improving the dialogue inform rate by 6.6% and the success rate by 4.1% over the best-performing existing approaches. Additionally, we discuss various annotator discrepancies and issues within the MultiWOZ dataset and its evaluation system.

[Arxiv](https://arxiv.org/abs/2411.00427)