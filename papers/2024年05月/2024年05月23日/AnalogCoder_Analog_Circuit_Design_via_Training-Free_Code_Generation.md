# AnalogCoder：模拟电路设计新方法——无需训练的代码生成技术

发布时间：2024年05月23日

`Agent

理由：这篇论文介绍了一个名为 AnalogCoder 的 LLM 代理，它专门用于模拟电路设计，并且不需要训练。该代理通过定制的领域特定提示和反馈增强流程来生成 Python 代码，以设计模拟电路。此外，AnalogCoder 还创建了一个电路工具库，用于存储和复用设计。这些特性表明 AnalogCoder 是一个专门设计的代理，用于解决特定领域的问题，即模拟电路设计。因此，它符合Agent分类的定义。` `芯片设计` `自动化设计`

> AnalogCoder: Analog Circuit Design via Training-Free Code Generation

# 摘要

> 模拟电路设计在现代芯片技术中占据重要地位，涉及组件选择、连接与参数调整，确保电路功能完善。尽管大型语言模型（LLMs）在数字电路设计领域有所突破，模拟电路的复杂性与数据稀缺仍是难题。为此，我们开发了AnalogCoder，首个无需训练的LLM代理，利用Python代码生成模拟电路设计。AnalogCoder通过定制的领域特定提示和反馈增强流程，实现高成功率的自动化自校正设计。此外，它创建了一个电路工具库，将成功设计存档为可复用的模块化子电路，简化复合电路构建。在一项覆盖广泛模拟电路任务的基准测试中，AnalogCoder表现优于其他LLM方法，成功设计了20个电路，超出标准GPT-4o五个。我们相信，AnalogCoder将极大提升芯片设计的效率，使非专业人士也能轻松设计模拟电路。相关代码和基准已发布于https://github.com/anonyanalog/AnalogCoder。

> Analog circuit design is a significant task in modern chip technology, focusing on the selection of component types, connectivity, and parameters to ensure proper circuit functionality. Despite advances made by Large Language Models (LLMs) in digital circuit design, the complexity and scarcity of data in analog circuitry pose significant challenges. To mitigate these issues, we introduce AnalogCoder, the first training-free LLM agent for designing analog circuits through Python code generation. Firstly, AnalogCoder incorporates a feedback-enhanced flow with tailored domain-specific prompts, enabling the automated and self-correcting design of analog circuits with a high success rate. Secondly, it proposes a circuit tool library to archive successful designs as reusable modular sub-circuits, simplifying composite circuit creation. Thirdly, extensive experiments on a benchmark designed to cover a wide range of analog circuit tasks show that AnalogCoder outperforms other LLM-based methods. It has successfully designed 20 circuits, 5 more than standard GPT-4o. We believe AnalogCoder can significantly improve the labor-intensive chip design process, enabling non-experts to design analog circuits efficiently. Codes and the benchmark are provided at https://github.com/anonyanalog/AnalogCoder.

[Arxiv](https://arxiv.org/abs/2405.14918)