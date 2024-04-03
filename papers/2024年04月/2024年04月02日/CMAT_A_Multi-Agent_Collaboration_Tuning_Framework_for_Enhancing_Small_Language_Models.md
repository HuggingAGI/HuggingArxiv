# CMAT：专为提升小型语言模型性能而设计的多智能体协同优化框架

发布时间：2024年04月02日

`Agent` `通信代理` `人工智能`

> CMAT: A Multi-Agent Collaboration Tuning Framework for Enhancing Small Language Models

# 摘要

> 开放的大型语言模型（LLMs）极大地推动了自然语言处理技术的进步，在众多任务中展现出非凡的性能。然而，LLMs的有效运行仍然离不开人类的精细引导，代理调整作为一项关键技术，通过人工调整模型以更好地响应引导，发挥着至关重要的作用。为了克服这种依赖，我们提出了TinyAgent模型，该模型基于精心筛选的高质量数据集进行训练。同时，我们还推出了协作多代理调整（CMAT）框架，这一创新系统通过环境反馈驱动的权重自适应更新，旨在提升语言代理的综合能力。该框架促进了智能代理间的协同学习和即时适应，提高了它们的情境感知能力和长期记忆保持能力。在本研究中，我们提出了一种融合多代理系统和环境反馈机制的新通信代理框架，为探索协作行为提供了一种可扩展的方法。特别值得一提的是，我们的TinyAgent-7B模型在参数更少的情况下，性能与GPT-3.5不相上下，这表明LLMs在效率和效能上实现了重大飞跃。

> Open large language models (LLMs) have significantly advanced the field of natural language processing, showcasing impressive performance across various tasks.Despite the significant advancements in LLMs, their effective operation still relies heavily on human input to accurately guide the dialogue flow, with agent tuning being a crucial optimization technique that involves human adjustments to the model for better response to such guidance.Addressing this dependency, our work introduces the TinyAgent model, trained on a meticulously curated high-quality dataset. We also present the Collaborative Multi-Agent Tuning (CMAT) framework, an innovative system designed to augment language agent capabilities through adaptive weight updates based on environmental feedback. This framework fosters collaborative learning and real-time adaptation among multiple intelligent agents, enhancing their context-awareness and long-term memory. In this research, we propose a new communication agent framework that integrates multi-agent systems with environmental feedback mechanisms, offering a scalable method to explore cooperative behaviors. Notably, our TinyAgent-7B model exhibits performance on par with GPT-3.5, despite having fewer parameters, signifying a substantial improvement in the efficiency and effectiveness of LLMs.

[Arxiv](https://arxiv.org/abs/2404.01663)