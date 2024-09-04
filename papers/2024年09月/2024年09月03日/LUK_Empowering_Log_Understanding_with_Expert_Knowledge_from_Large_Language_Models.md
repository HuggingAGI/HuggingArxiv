# LUK：借助大型语言模型中的专家知识，提升日志理解效能

发布时间：2024年09月03日

`LLM应用` `信息技术` `系统监控`

> LUK: Empowering Log Understanding with Expert Knowledge from Large Language Models

# 摘要

> 日志在系统监控和故障排查中至关重要。随着预训练语言模型（如 BERT）和大型模型（如 ChatGPT）在 NLP 领域的成功，它们已成为日志分析的主流。尽管 LLM 知识丰富，但其高成本和不稳定使其不适用于直接日志分析。相比之下，小型 PLM 虽能在有限资源下微调，但因知识有限，全面理解日志有难度。为此，本文提出 LUK 框架，从 LLM 汲取专家知识，增强小型 PLM 的日志理解能力。我们设计了多专家协作框架，并提出两项新预训练任务，以专家知识强化日志预训练。LUK 在多项日志分析任务中表现卓越，实验证明 LLM 的专家知识能更有效地助力日志理解。

> Logs play a critical role in providing essential information for system monitoring and troubleshooting. Recently, with the success of pre-trained language models (PLMs) and large language models (LLMs) in natural language processing (NLP), smaller PLMs (such as BERT) and LLMs (like ChatGPT) have become the current mainstream approaches for log analysis. While LLMs possess rich knowledge, their high computational costs and unstable performance make LLMs impractical for analyzing logs directly. In contrast, smaller PLMs can be fine-tuned for specific tasks even with limited computational resources, making them more practical. However, these smaller PLMs face challenges in understanding logs comprehensively due to their limited expert knowledge. To better utilize the knowledge embedded within LLMs for log understanding, this paper introduces a novel knowledge enhancement framework, called LUK, which acquires expert knowledge from LLMs to empower log understanding on a smaller PLM. Specifically, we design a multi-expert collaboration framework based on LLMs consisting of different roles to acquire expert knowledge. In addition, we propose two novel pre-training tasks to enhance the log pre-training with expert knowledge. LUK achieves state-of-the-art results on different log analysis tasks and extensive experiments demonstrate expert knowledge from LLMs can be utilized more effectively to understand logs.

[Arxiv](https://arxiv.org/abs/2409.01909)