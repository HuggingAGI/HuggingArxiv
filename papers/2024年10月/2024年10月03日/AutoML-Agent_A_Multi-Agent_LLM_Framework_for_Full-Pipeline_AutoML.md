# AutoML-Agent：一个专为全流程 AutoML 设计的多智能体 LLM 框架

发布时间：2024年10月03日

`Agent` `人工智能` `软件开发`

> AutoML-Agent: A Multi-Agent LLM Framework for Full-Pipeline AutoML

# 摘要

> AutoML 通过自动化模型搜索和超参数调整等任务，加速了 AI 开发。然而，现有系统通常需要专业知识来设置复杂工具，耗时且费力。为此，近期研究开始利用 LLM 通过自然语言接口提升 AutoML 的易用性，使非专家也能构建数据驱动解决方案。但这些方法往往仅针对 AI 开发中的特定环节，未能充分挖掘 LLM 的潜力。本文提出 AutoML-Agent，一个专为全流程 AutoML 设计的多代理框架，从数据检索到模型部署。AutoML-Agent 接收用户任务描述，协调专门 LLM 代理，输出可部署模型。我们采用检索增强的规划策略，而非单一计划，以探索更优方案。同时，将计划分解为数据预处理、神经网络设计等子任务，由并行执行的专门代理解决，提升搜索效率。此外，我们设计了多阶段验证机制，确保执行结果准确，并指导 LLM 生成成功代码。实验表明，AutoML-Agent 在自动化全流程 AutoML 方面表现优异，适用于多样领域。

> Automated machine learning (AutoML) accelerates AI development by automating tasks in the development pipeline, such as optimal model search and hyperparameter tuning. Existing AutoML systems often require technical expertise to set up complex tools, which is in general time-consuming and requires a large amount of human effort. Therefore, recent works have started exploiting large language models (LLM) to lessen such burden and increase the usability of AutoML frameworks via a natural language interface, allowing non-expert users to build their data-driven solutions. These methods, however, are usually designed only for a particular process in the AI development pipeline and do not efficiently use the inherent capacity of the LLMs. This paper proposes AutoML-Agent, a novel multi-agent framework tailored for full-pipeline AutoML, i.e., from data retrieval to model deployment. AutoML-Agent takes user's task descriptions, facilitates collaboration between specialized LLM agents, and delivers deployment-ready models. Unlike existing work, instead of devising a single plan, we introduce a retrieval-augmented planning strategy to enhance exploration to search for more optimal plans. We also decompose each plan into sub-tasks (e.g., data preprocessing and neural network design) each of which is solved by a specialized agent we build via prompting executing in parallel, making the search process more efficient. Moreover, we propose a multi-stage verification to verify executed results and guide the code generation LLM in implementing successful solutions. Extensive experiments on seven downstream tasks using fourteen datasets show that AutoML-Agent achieves a higher success rate in automating the full AutoML process, yielding systems with good performance throughout the diverse domains.

[Arxiv](https://arxiv.org/abs/2410.02958)