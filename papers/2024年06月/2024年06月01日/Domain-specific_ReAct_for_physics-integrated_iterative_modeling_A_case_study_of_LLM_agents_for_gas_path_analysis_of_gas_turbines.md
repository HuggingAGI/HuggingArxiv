# 特定领域 ReAct 在物理集成迭代建模中的应用：以大型语言模型代理在燃气轮机气体路径分析中的案例为例，探讨其在特定领域的应用与效果。

发布时间：2024年06月01日

`Agent

理由：这篇论文主要探讨了大型语言模型（LLMs）在能源与电力工程领域的应用，特别是在燃气轮机气体路径分析中。论文中提到的“双代理工具调用机制”表明了Agent的概念，即模型作为代理在特定领域内执行任务，调用工具并结合专家知识和推理能力解决问题。这与Agent的定义相符，即一个能够感知环境并采取行动以达到目标的系统。因此，这篇论文应归类于Agent。` `能源与电力工程` `人工智能`

> Domain-specific ReAct for physics-integrated iterative modeling: A case study of LLM agents for gas path analysis of gas turbines

# 摘要

> 本研究深入探讨了大型语言模型（LLMs）在能源与电力工程领域，尤其是燃气轮机气体路径分析中的应用，并创新性地开发了一种双代理工具调用机制，融合了专家知识、预设工具与LLM的推理能力。我们评估了LLama3、Qwen1.5和GPT等多种模型，发现小型模型在工具应用和参数提取上力不从心，而大型模型则表现出色。然而，面对复杂的多组件问题，所有模型均显露出挑战。测试结果表明，具备约100亿参数的LLMs，在精心调整和巧妙提示设计的加持下，能够满足专业场景的严格要求。未来发展有望进一步提升其精确度和效能，为AI驱动的解决方案开辟更广阔的前景。

> This study explores the application of large language models (LLMs) with callable tools in energy and power engineering domain, focusing on gas path analysis of gas turbines. We developed a dual-agent tool-calling process to integrate expert knowledge, predefined tools, and LLM reasoning. We evaluated various LLMs, including LLama3, Qwen1.5 and GPT. Smaller models struggled with tool usage and parameter extraction, while larger models demonstrated favorable capabilities. All models faced challenges with complex, multi-component problems. Based on the test results, we infer that LLMs with nearly 100 billion parameters could meet professional scenario requirements with fine-tuning and advanced prompt design. Continued development are likely to enhance their accuracy and effectiveness, paving the way for more robust AI-driven solutions.

[Arxiv](https://arxiv.org/abs/2406.07572)