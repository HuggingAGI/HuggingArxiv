# IntellBot：用于网络威胁知识传递的检索增强型大型语言模型聊天机器人

发布时间：2024年11月08日

`LLM应用` `网络安全` `聊天机器人`

> IntellBot: Retrieval Augmented LLM Chatbot for Cyber Threat Knowledge Delivery

# 摘要

> 在网络安全迅速发展的格局中，智能聊天机器人正变得突出。人工智能、机器学习和自然语言处理使这些聊天机器人能够处理用户的询问并提供威胁情报。这有助于网络安全知识容易地为专业人员和公众所获取。传统的基于规则的聊天机器人往往缺乏灵活性，难以适应用户互动。相比之下，基于大型语言模型的聊天机器人能够在多个领域提供与上下文相关的信息，并适应不断变化的对话情境。在这项工作中，我们开发了 IntellBot，这是一个先进的网络安全聊天机器人，建立在大型语言模型和 Langchain 等前沿技术以及检索增强生成模型之上，以提供卓越的能力。这个聊天机器人从各种数据源收集信息，创建一个涵盖已知漏洞、近期网络攻击和新兴威胁的综合知识库。它提供量身定制的响应，作为网络安全见解的主要枢纽。通过提供对相关信息和资源的即时访问，这个 IntellBot 增强了威胁情报、事件响应和整体安全态势，节省了时间，并为用户提供了网络安全最佳实践的知识。此外，我们使用两阶段评估策略分析了我们的副驾驶的性能。我们通过间接方法实现了 BERT 分数高于 0.8，余弦相似度分数在 0.8 到 1 之间，这肯定了我们的副驾驶的准确性。此外，我们利用 RAGAS 来评估 RAG 模型，所有评估指标始终产生高于 0.77 的分数，突出了我们系统的有效性。

> In the rapidly evolving landscape of cyber security, intelligent chatbots are gaining prominence. Artificial Intelligence, Machine Learning, and Natural Language Processing empower these chatbots to handle user inquiries and deliver threat intelligence. This helps cyber security knowledge readily available to both professionals and the public. Traditional rule-based chatbots often lack flexibility and struggle to adapt to user interactions. In contrast, Large Language Model-based chatbots offer contextually relevant information across multiple domains and adapt to evolving conversational contexts. In this work, we develop IntellBot, an advanced cyber security Chatbot built on top of cutting-edge technologies like Large Language Models and Langchain alongside a Retrieval-Augmented Generation model to deliver superior capabilities. This chatbot gathers information from diverse data sources to create a comprehensive knowledge base covering known vulnerabilities, recent cyber attacks, and emerging threats. It delivers tailored responses, serving as a primary hub for cyber security insights. By providing instant access to relevant information and resources, this IntellBot enhances threat intelligence, incident response, and overall security posture, saving time and empowering users with knowledge of cyber security best practices. Moreover, we analyzed the performance of our copilot using a two-stage evaluation strategy. We achieved BERT score above 0.8 by indirect approach and a cosine similarity score ranging from 0.8 to 1, which affirms the accuracy of our copilot. Additionally, we utilized RAGAS to evaluate the RAG model, and all evaluation metrics consistently produced scores above 0.77, highlighting the efficacy of our system.

[Arxiv](https://arxiv.org/abs/2411.05442)