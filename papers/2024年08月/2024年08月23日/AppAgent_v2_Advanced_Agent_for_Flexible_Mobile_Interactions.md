# AppAgent v2：灵活移动交互的高级代理

发布时间：2024年08月23日

`Agent` `软件开发` `移动设备`

> AppAgent v2: Advanced Agent for Flexible Mobile Interactions

# 摘要

> 随着多模态大型语言模型的发展，LLM 驱动的视觉代理正日益影响着软件界面，尤其是图形用户界面。我们提出了一种创新的基于 LLM 的多模态移动设备代理框架，该框架能模拟人类交互并导航移动设备。代理通过构建灵活的动作空间，提升了在解析器、文本和视觉描述等多种应用中的适应性。其运作分为探索和部署两个阶段：探索阶段通过代理或手动方式，将用户界面元素功能记录于定制知识库；部署阶段则利用 RAG 技术高效检索和更新知识库，使代理能精准执行复杂多步骤操作，展现框架的适应性与精确性。实验结果表明，该框架在多个基准测试中表现卓越，证实了其在实际应用中的有效性。代码即将开源。

> With the advancement of Multimodal Large Language Models (MLLM), LLM-driven visual agents are increasingly impacting software interfaces, particularly those with graphical user interfaces. This work introduces a novel LLM-based multimodal agent framework for mobile devices. This framework, capable of navigating mobile devices, emulates human-like interactions. Our agent constructs a flexible action space that enhances adaptability across various applications including parser, text and vision descriptions. The agent operates through two main phases: exploration and deployment. During the exploration phase, functionalities of user interface elements are documented either through agent-driven or manual explorations into a customized structured knowledge base. In the deployment phase, RAG technology enables efficient retrieval and update from this knowledge base, thereby empowering the agent to perform tasks effectively and accurately. This includes performing complex, multi-step operations across various applications, thereby demonstrating the framework's adaptability and precision in handling customized task workflows. Our experimental results across various benchmarks demonstrate the framework's superior performance, confirming its effectiveness in real-world scenarios. Our code will be open source soon.

[Arxiv](https://arxiv.org/abs/2408.11824)