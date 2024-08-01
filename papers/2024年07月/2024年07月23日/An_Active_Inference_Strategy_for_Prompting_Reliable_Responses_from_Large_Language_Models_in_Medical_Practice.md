# 在医疗实践中，采用主动推理策略，以确保大型语言模型提供可靠的响应。

发布时间：2024年07月23日

`LLM应用` `人工智能`

> An Active Inference Strategy for Prompting Reliable Responses from Large Language Models in Medical Practice

# 摘要

> 随着人工智能领域大型语言模型（LLM）的不断进步，其在医学教育和治疗等多个场景中直观获取和应用知识的能力日益增强。然而，早期的文献多指出LLM因非确定性、可能提供错误信息且难以监管，不适合医学应用。若能解决这些问题，优化后的LLM技术将通过提供即时且经济的医学知识，惠及医患双方。我们提出的框架通过限定LLM的知识库为经过验证的医学数据集，优化其回答。同时，我们创新性地引入了基于人类认知主动推理的actor-critic提示协议，其中Therapist代理先回应患者，Supervisor代理随后评估并修正回答，确保准确可靠。在一项盲测研究中，经验丰富的CBT-I治疗师对LLM的回答给予了高度评价，甚至超过了一些专业治疗师的回答。这一结构化方法旨在将LLM技术安全有效地融入医学实践，满足监管要求。

> Continuing advances in Large Language Models (LLMs) in artificial intelligence offer important capacities in intuitively accessing and using medical knowledge in many contexts, including education and training as well as assessment and treatment. Most of the initial literature on LLMs in medicine has emphasized that LLMs are unsuitable for medical use because they are non-deterministic, may provide incorrect or harmful responses, and cannot be regulated to assure quality control. If these issues could be corrected, optimizing LLM technology could benefit patients and physicians by providing affordable, point-of-care medical knowledge. Our proposed framework refines LLM responses by restricting their primary knowledge base to domain-specific datasets containing validated medical information. Additionally, we introduce an actor-critic LLM prompting protocol based on active inference principles of human cognition, where a Therapist agent initially responds to patient queries, and a Supervisor agent evaluates and adjusts responses to ensure accuracy and reliability. We conducted a validation study where expert cognitive behaviour therapy for insomnia (CBT-I) therapists evaluated responses from the LLM in a blind format. Experienced human CBT-I therapists assessed responses to 100 patient queries, comparing LLM-generated responses with appropriate and inappropriate responses crafted by experienced CBT-I therapists. Results showed that LLM responses received high ratings from the CBT-I therapists, often exceeding those of therapist-generated appropriate responses. This structured approach aims to integrate advanced LLM technology into medical applications, meeting regulatory requirements for establishing the safe and effective use of special purpose validated LLMs in medicine.

[Arxiv](https://arxiv.org/abs/2407.21051)