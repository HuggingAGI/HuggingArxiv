# AnalogCoder：模拟电路设计新方法——无需训练的代码生成技术

发布时间：2024年05月23日

`Agent

理由：这篇论文介绍了一个名为 AnalogCoder 的 LLM 代理，它专门用于模拟电路设计，并且能够通过 Python 代码生成设计方案。这个代理的特点在于它不需要训练，而是通过定制的领域特定提示和反馈增强流程来实现自动化设计。此外，AnalogCoder 还能够自我修正，并创建了一个电路工具库，这些功能都体现了它作为一个智能代理的特性。因此，这篇论文更适合归类到Agent分类中。` `芯片设计` `自动化设计`

> AnalogCoder: Analog Circuit Design via Training-Free Code Generation

# 摘要

> 模拟电路设计在现代芯片技术中占据重要地位，涉及组件选择、连接布局及参数优化，以确保电路性能。尽管大型语言模型（LLMs）在数字电路设计领域有所突破，模拟电路的复杂性和数据匮乏仍是挑战。为此，我们开发了AnalogCoder，首个无需训练的LLM代理，利用Python代码生成模拟电路设计。AnalogCoder通过定制的领域特定提示和反馈增强流程，实现了高成功率的自动化模拟电路设计，并能自我修正。此外，它创建了一个电路工具库，将成功设计存档为可重复使用的模块化子电路，简化了复杂电路的构建。在涵盖多种模拟电路任务的基准测试中，AnalogCoder表现优于其他LLM方法，成功设计了20个电路，超越了标准GPT-4o。我们相信，AnalogCoder将极大提升芯片设计的效率，让非专业人士也能轻松设计模拟电路。相关代码和基准已发布于https://github.com/anonyanalog/AnalogCoder。

> Analog circuit design is a significant task in modern chip technology, focusing on the selection of component types, connectivity, and parameters to ensure proper circuit functionality. Despite advances made by Large Language Models (LLMs) in digital circuit design, the complexity and scarcity of data in analog circuitry pose significant challenges. To mitigate these issues, we introduce AnalogCoder, the first training-free LLM agent for designing analog circuits through Python code generation. Firstly, AnalogCoder incorporates a feedback-enhanced flow with tailored domain-specific prompts, enabling the automated and self-correcting design of analog circuits with a high success rate. Secondly, it proposes a circuit tool library to archive successful designs as reusable modular sub-circuits, simplifying composite circuit creation. Thirdly, extensive experiments on a benchmark designed to cover a wide range of analog circuit tasks show that AnalogCoder outperforms other LLM-based methods. It has successfully designed 20 circuits, 5 more than standard GPT-4o. We believe AnalogCoder can significantly improve the labor-intensive chip design process, enabling non-experts to design analog circuits efficiently. Codes and the benchmark are provided at https://github.com/anonyanalog/AnalogCoder.

[Arxiv](https://arxiv.org/abs/2405.14918)