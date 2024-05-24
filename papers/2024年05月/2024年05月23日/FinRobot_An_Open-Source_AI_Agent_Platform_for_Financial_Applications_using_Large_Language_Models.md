# FinRobot：金融领域的开源AI代理平台，依托大型语言模型，助力智能金融应用。

发布时间：2024年05月23日

`Agent

这篇论文介绍了一个名为FinRobot的开源平台，该平台支持多种金融专用AI代理，每个代理均由大型语言模型（LLM）驱动。平台的设计包括多个层次，旨在通过AI技术提升金融分析的能力，并促进AI在金融决策中的应用。由于论文主要关注的是开发和应用基于LLM的AI代理来解决金融领域的具体问题，因此将其归类为Agent。` `人工智能`

> FinRobot: An Open-Source AI Agent Platform for Financial Applications using Large Language Models

# 摘要

> 金融机构和专业人士正越来越多地采用大型语言模型（LLMs），但专有数据和专业知识等障碍仍横亘在金融界与AI社区之间，限制了AI在金融任务上的有效提升。认识到金融分析的重要性，我们致力于开发基于LLM的金融专用工具链，并通过开源方式推广，以促进AI在金融决策中的广泛应用。本文介绍了FinRobot，一个支持多种金融专用AI代理的开源平台，每个代理均由LLM驱动。平台架构包括：金融AI代理层，将复杂问题逻辑分解以形成金融思维链；金融LLM算法层，为任务定制模型策略；LLMOps和DataOps层，利用相关数据进行模型训练和微调；以及多源LLM基础模型层，整合各类LLM资源。FinRobot不仅服务于专业分析师，也让普通用户能够利用AI技术进行深入的金融分析。项目已开源，地址为\url{https://github.com/AI4Finance-Foundation/FinRobot}。

> As financial institutions and professionals increasingly incorporate Large Language Models (LLMs) into their workflows, substantial barriers, including proprietary data and specialized knowledge, persist between the finance sector and the AI community. These challenges impede the AI community's ability to enhance financial tasks effectively. Acknowledging financial analysis's critical role, we aim to devise financial-specialized LLM-based toolchains and democratize access to them through open-source initiatives, promoting wider AI adoption in financial decision-making.
  In this paper, we introduce FinRobot, a novel open-source AI agent platform supporting multiple financially specialized AI agents, each powered by LLM. Specifically, the platform consists of four major layers: 1) the Financial AI Agents layer that formulates Financial Chain-of-Thought (CoT) by breaking sophisticated financial problems down into logical sequences; 2) the Financial LLM Algorithms layer dynamically configures appropriate model application strategies for specific tasks; 3) the LLMOps and DataOps layer produces accurate models by applying training/fine-tuning techniques and using task-relevant data; 4) the Multi-source LLM Foundation Models layer that integrates various LLMs and enables the above layers to access them directly. Finally, FinRobot provides hands-on for both professional-grade analysts and laypersons to utilize powerful AI techniques for advanced financial analysis. We open-source FinRobot at \url{https://github.com/AI4Finance-Foundation/FinRobot}.

[Arxiv](https://arxiv.org/abs/2405.14767)