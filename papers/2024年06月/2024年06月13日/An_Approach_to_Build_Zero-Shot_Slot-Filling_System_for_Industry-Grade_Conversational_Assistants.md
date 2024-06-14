# 打造工业级对话助手零-shot槽填充系统的策略

发布时间：2024年06月13日

`Agent

理由：该论文描述了一个基于大型语言模型（LLM）的槽填充系统，该系统旨在提升对话助手中的对话状态跟踪能力。这个系统被设计为能够适应多行业的广泛应用，并且具备零-shot学习能力，以适应多样化的领域和对话情境。这种系统可以被视为一个智能代理（Agent），因为它能够处理和响应对话中的信息，以实现特定的任务（如槽填充）。此外，论文中提到的系统设计和实验结果分析，都是围绕如何构建和优化这样一个智能代理进行的。因此，这篇论文更适合归类为Agent。` `对话系统`

> An Approach to Build Zero-Shot Slot-Filling System for Industry-Grade Conversational Assistants

# 摘要

> 我们开发了一种基于LLM的槽填充系统，旨在提升对话助手中的对话状态跟踪能力，适用于多行业的广泛应用。该系统需满足两个关键条件：一是采用小型模型以确保低延迟和高效部署；二是具备零-shot学习能力，以适应多样化的领域和对话情境。我们通过特定任务数据对预训练的LLM进行微调，构建了槽填充模型，并精心设计了涵盖多领域槽填充场景的训练数据。详细阐述了数据处理和模型构建的步骤，并对实验结果进行了深入分析。实验表明，我们的方法在实际测试中F1分数提升了6.9%，同时延迟减少了57%，且在不同槽类型上平均F1分数提高了4.2%。

> We present an approach to build Large Language Model (LLM) based slot-filling system to perform Dialogue State Tracking in conversational assistants serving across a wide variety of industry-grade applications. Key requirements of this system include: 1) usage of smaller-sized models to meet low latency requirements and to enable convenient and cost-effective cloud and customer premise deployments, and 2) zero-shot capabilities to serve across a wide variety of domains, slot types and conversational scenarios. We adopt a fine-tuning approach where a pre-trained LLM is fine-tuned into a slot-filling model using task specific data. The fine-tuning data is prepared carefully to cover a wide variety of slot-filling task scenarios that the model is expected to face across various domains. We give details of the data preparation and model building process. We also give a detailed analysis of the results of our experimental evaluations. Results show that our prescribed approach for slot-filling model building has resulted in 6.9% relative improvement of F1 metric over the best baseline on a realistic benchmark, while at the same time reducing the latency by 57%. More over, the data we prepared has helped improve F1 on an average by 4.2% relative across various slot-types.

![打造工业级对话助手零-shot槽填充系统的策略](../../../paper_images/2406.08848/slot-filling-illustration.png)

[Arxiv](https://arxiv.org/abs/2406.08848)