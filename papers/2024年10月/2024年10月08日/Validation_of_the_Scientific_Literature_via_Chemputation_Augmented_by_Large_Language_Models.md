# 利用大型语言模型增强的化学计算，验证科学文献的准确性。

发布时间：2024年10月08日

`LLM应用` `机器人`

> Validation of the Scientific Literature via Chemputation Augmented by Large Language Models

# 摘要

> Chemputation 通过通用符号语言编程化学机器人进行实验，但文献中的歧义使其易错且难读。LLM 在 NLP、机器人控制和化学等领域表现出色。尽管合成化学数据标准化有进展，但合成再现仍费力。我们提出基于 LLM 的化学研究工作流程，自动验证合成文献。该流程自主提取、翻译、模拟并执行合成程序，展示 LLM 在 Chemputers 自主合成中的潜力。XDL 的抽象确保安全、可靠和可扩展。与以往方法不同，我们提供四个真实合成示例，预期将大幅提升机器人合成化学的自动化、数据提取效率和实验安全性。

> Chemputation is the process of programming chemical robots to do experiments using a universal symbolic language, but the literature can be error prone and hard to read due to ambiguities. Large Language Models (LLMs) have demonstrated remarkable capabilities in various domains, including natural language processing, robotic control, and more recently, chemistry. Despite significant advancements in standardizing the reporting and collection of synthetic chemistry data, the automatic reproduction of reported syntheses remains a labour-intensive task. In this work, we introduce an LLM-based chemical research agent workflow designed for the automatic validation of synthetic literature procedures. Our workflow can autonomously extract synthetic procedures and analytical data from extensive documents, translate these procedures into universal XDL code, simulate the execution of the procedure in a hardware-specific setup, and ultimately execute the procedure on an XDL-controlled robotic system for synthetic chemistry. This demonstrates the potential of LLM-based workflows for autonomous chemical synthesis with Chemputers. Due to the abstraction of XDL this approach is safe, secure, and scalable since hallucinations will not be chemputable and the XDL can be both verified and encrypted. Unlike previous efforts, which either addressed only a limited portion of the workflow, relied on inflexible hard-coded rules, or lacked validation in physical systems, our approach provides four realistic examples of syntheses directly executed from synthetic literature. We anticipate that our workflow will significantly enhance automation in robotically driven synthetic chemistry research, streamline data extraction, improve the reproducibility, scalability, and safety of synthetic and experimental chemistry.

[Arxiv](https://arxiv.org/abs/2410.06384)