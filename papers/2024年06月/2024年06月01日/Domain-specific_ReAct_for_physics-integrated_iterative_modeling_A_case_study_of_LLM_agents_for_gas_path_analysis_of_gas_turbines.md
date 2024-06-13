# 特定领域 ReAct 在物理集成迭代建模中的应用：以大型语言模型代理在燃气轮机气体路径分析中的案例为例

发布时间：2024年06月01日

`Agent

理由：这篇论文主要探讨了大型语言模型（LLMs）在能源与电力工程领域的应用，特别是在燃气轮机气体路径分析中，并设计了一种双代理工具调用机制。这种机制结合了专家知识、预设工具与LLM的推理能力，体现了一种Agent的设计和应用。因此，它更适合归类于Agent分类，而不是RAG、LLM应用或LLM理论。` `能源与电力工程` `人工智能`

> Domain-specific ReAct for physics-integrated iterative modeling: A case study of LLM agents for gas path analysis of gas turbines

# 摘要

> 本研究深入探讨了大型语言模型（LLMs）在能源与电力工程领域，尤其是燃气轮机气体路径分析中的应用，并结合了可调用工具。我们创新性地设计了一种双代理工具调用机制，巧妙融合了专家知识、预设工具与LLM的推理能力。在评估中，我们涵盖了LLama3、Qwen1.5及GPT等多种模型。小型模型在工具运用与参数提取上显得力不从心，而大型模型则展现出卓越的适应性。然而，面对复杂的多组件问题，所有模型均遭遇了挑战。测试结果表明，具备约100亿参数的LLMs，在精心调整与高级提示设计的加持下，能满足专业场景的严格要求。展望未来，持续的技术进步将进一步提升这些模型的精确度与效能，为AI驱动的解决方案开辟更广阔的前景。

> This study explores the application of large language models (LLMs) with callable tools in energy and power engineering domain, focusing on gas path analysis of gas turbines. We developed a dual-agent tool-calling process to integrate expert knowledge, predefined tools, and LLM reasoning. We evaluated various LLMs, including LLama3, Qwen1.5 and GPT. Smaller models struggled with tool usage and parameter extraction, while larger models demonstrated favorable capabilities. All models faced challenges with complex, multi-component problems. Based on the test results, we infer that LLMs with nearly 100 billion parameters could meet professional scenario requirements with fine-tuning and advanced prompt design. Continued development are likely to enhance their accuracy and effectiveness, paving the way for more robust AI-driven solutions.

[Arxiv](https://arxiv.org/abs/2406.07572)