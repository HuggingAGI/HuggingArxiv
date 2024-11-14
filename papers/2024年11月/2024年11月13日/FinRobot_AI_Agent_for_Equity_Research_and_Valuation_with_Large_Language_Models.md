# FinRobot：使用大型语言模型进行股票研究和估值的人工智能代理

发布时间：2024年11月13日

`Agent` `股票研究`

> FinRobot: AI Agent for Equity Research and Valuation with Large Language Models

# 摘要

> 随着金融市场变得日益复杂，对于能够在股票研究中有效协助人类分析师的自动化工具的需求不断增加，特别是在卖方研究领域。虽然生成式人工智能（GenAI）在这个领域引起了极大的关注，但现有的人工智能解决方案往往由于其对技术因素的狭隘关注和自由裁量判断能力有限而表现不佳。这些限制阻碍了它们实时适应新数据和准确评估风险的能力，从而降低了它们对投资者的实用价值。

本文介绍了 FinRobot，这是第一个专门为股票研究设计的人工智能代理框架。FinRobot 采用了多代理的思维链（CoT）系统，将定量和定性分析相结合，以模拟人类分析师的综合推理。该系统围绕三个专门的代理构建：数据 - CoT 代理，它聚合了各种数据源以实现强大的金融整合；概念 - CoT 代理，它模仿分析师的推理以产生可行的见解；论文 - CoT 代理，它将这些见解综合成一个连贯的投资论文和报告。FinRobot 提供了由精确的数字数据、适合行业的估值指标和现实的风险评估支持的全面公司分析。其动态可更新的数据管道确保研究保持及时和相关，无缝适应新的金融信息。与现有的自动化研究工具（如 CapitalCube 和 Wright Reports）不同，FinRobot 提供的见解可与主要经纪公司和基础研究供应商的成果相媲美。我们在 url{https://github. com/AI4Finance-Foundation/FinRobot}开源了 FinRobot。

> As financial markets grow increasingly complex, there is a rising need for automated tools that can effectively assist human analysts in equity research, particularly within sell-side research. While Generative AI (GenAI) has attracted significant attention in this field, existing AI solutions often fall short due to their narrow focus on technical factors and limited capacity for discretionary judgment. These limitations hinder their ability to adapt to new data in real-time and accurately assess risks, which diminishes their practical value for investors.
  This paper presents FinRobot, the first AI agent framework specifically designed for equity research. FinRobot employs a multi-agent Chain of Thought (CoT) system, integrating both quantitative and qualitative analyses to emulate the comprehensive reasoning of a human analyst. The system is structured around three specialized agents: the Data-CoT Agent, which aggregates diverse data sources for robust financial integration; the Concept-CoT Agent, which mimics an analysts reasoning to generate actionable insights; and the Thesis-CoT Agent, which synthesizes these insights into a coherent investment thesis and report. FinRobot provides thorough company analysis supported by precise numerical data, industry-appropriate valuation metrics, and realistic risk assessments. Its dynamically updatable data pipeline ensures that research remains timely and relevant, adapting seamlessly to new financial information. Unlike existing automated research tools, such as CapitalCube and Wright Reports, FinRobot delivers insights comparable to those produced by major brokerage firms and fundamental research vendors. We open-source FinRobot at \url{https://github. com/AI4Finance-Foundation/FinRobot}.

[Arxiv](https://arxiv.org/abs/2411.08804)