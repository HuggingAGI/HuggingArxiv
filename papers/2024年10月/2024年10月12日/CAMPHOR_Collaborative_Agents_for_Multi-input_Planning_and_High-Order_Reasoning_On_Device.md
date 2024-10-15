# CAMPHOR：设备上多输入规划与高阶推理的协作代理

发布时间：2024年10月12日

`Agent` `移动设备` `隐私保护`

> CAMPHOR: Collaborative Agents for Multi-input Planning and High-Order Reasoning On Device

# 摘要

> 尽管服务器端 LLM 在函数调用和复杂推理方面表现出色，但直接在设备上部署 SLM 不仅能提升延迟和隐私，也带来了准确性和内存的挑战。为此，我们推出了 CAMPHOR，一个创新的设备上 SLM 多代理框架，专门处理多用户输入并在本地推理个人上下文，确保隐私无虞。CAMPHOR 采用分层架构，高阶推理代理分解复杂任务，并协调负责个人上下文检索、工具交互和动态计划生成的专家代理。通过参数共享和提示压缩，我们大幅减少了模型大小、延迟和内存使用。我们还展示了一个新的数据集，聚焦个性化移动助手用例的多代理任务轨迹。实验结果显示，微调后的 SLM 代理在任务完成 F1 上超越了闭源 LLM 约 35%，同时消除了服务器-设备通信，进一步强化了隐私保护。

> While server-side Large Language Models (LLMs) demonstrate proficiency in function calling and complex reasoning, deploying Small Language Models (SLMs) directly on devices brings opportunities to improve latency and privacy but also introduces unique challenges for accuracy and memory. We introduce CAMPHOR, an innovative on-device SLM multi-agent framework designed to handle multiple user inputs and reason over personal context locally, ensuring privacy is maintained. CAMPHOR employs a hierarchical architecture where a high-order reasoning agent decomposes complex tasks and coordinates expert agents responsible for personal context retrieval, tool interaction, and dynamic plan generation. By implementing parameter sharing across agents and leveraging prompt compression, we significantly reduce model size, latency, and memory usage. To validate our approach, we present a novel dataset capturing multi-agent task trajectories centered on personalized mobile assistant use-cases. Our experiments reveal that fine-tuned SLM agents not only surpass closed-source LLMs in task completion F1 by~35\% but also eliminate the need for server-device communication, all while enhancing privacy.

[Arxiv](https://arxiv.org/abs/2410.09407)