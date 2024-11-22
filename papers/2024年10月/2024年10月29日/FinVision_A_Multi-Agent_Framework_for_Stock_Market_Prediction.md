# FinVision：一个用于股票市场预测的多智能体框架

发布时间：2024年10月29日

`Agent`

> FinVision: A Multi-Agent Framework for Stock Market Prediction

# 摘要

> 金融交易向来是颇具挑战性的任务，因其需要整合来自不同模式的海量数据。传统的深度学习和强化学习方法需要大量训练数据，还常常得把各种数据类型编码成数值格式作为模型输入，这就限制了模型行为的可解释性。近来，基于LLM的代理在处理多模态数据方面取得了显著进展，能够执行复杂的多步决策任务，同时还能让人了解其思考过程。本研究推出了一个专为金融交易任务打造的多模态多代理系统。我们的框架启用了一组专门的基于LLM的代理，每个代理都善于处理和解读各种形式的金融数据，像文本新闻报道、烛台图和交易信号图。我们方法的一大关键特点是融入了一个反思模块，用于对历史交易信号及其结果进行分析。这种反思过程有助于提升系统在未来交易场景中的决策能力。此外，消融研究显示，视觉反思模块在增强我们框架的决策能力方面发挥着关键作用。

> Financial trading has been a challenging task, as it requires the integration of vast amounts of data from various modalities. Traditional deep learning and reinforcement learning methods require large training data and often involve encoding various data types into numerical formats for model input, which limits the explainability of model behavior. Recently, LLM-based agents have demonstrated remarkable advancements in handling multi-modal data, enabling them to execute complex, multi-step decision-making tasks while providing insights into their thought processes. This research introduces a multi-modal multi-agent system designed specifically for financial trading tasks. Our framework employs a team of specialized LLM-based agents, each adept at processing and interpreting various forms of financial data, such as textual news reports, candlestick charts, and trading signal charts. A key feature of our approach is the integration of a reflection module, which conducts analyses of historical trading signals and their outcomes. This reflective process is instrumental in enhancing the decision-making capabilities of the system for future trading scenarios. Furthermore, the ablation studies indicate that the visual reflection module plays a crucial role in enhancing the decision-making capabilities of our framework.

[Arxiv](https://arxiv.org/abs/2411.08899)