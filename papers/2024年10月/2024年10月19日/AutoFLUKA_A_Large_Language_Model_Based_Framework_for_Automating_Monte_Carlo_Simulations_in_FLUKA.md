# AutoFLUKA：基于大型语言模型，自动化 FLUKA 中的蒙特卡罗模拟框架

发布时间：2024年10月19日

`Agent` `科学研究`

> AutoFLUKA: A Large Language Model Based Framework for Automating Monte Carlo Simulations in FLUKA

# 摘要

> 蒙特卡罗模拟（尤其是 FLUKA）在科学和工程领域中复制现实场景至关重要。然而，FLUKA 在自动化和集成方面存在显著局限，导致工作流程复杂且易错。传统方法如 shell 脚本、MATLAB 和 Excel 缺乏灵活性，增加了操作难度。本研究探索了大型语言模型（LLM）和 AI 代理的潜力，通过自然语言处理和自主推理，实现自动化决策和规划。我们开发的 AutoFLUKA 应用，利用 LangChain 框架，自动修改 FLUKA 输入文件、执行模拟并高效处理结果，大幅减少人力和错误。案例研究显示，AutoFLUKA 在微剂量学等领域的应用表现出色，展示了其可扩展性和灵活性。此外，检索增强生成工具作为虚拟助手，进一步提升了用户体验和效率。总之，AutoFLUKA 不仅简化了 MC 模拟流程，还为高能物理、医学物理等领域开辟了新的研究路径。

> Monte Carlo (MC) simulations, particularly using FLUKA, are essential for replicating real-world scenarios across scientific and engineering fields. Despite the robustness and versatility, FLUKA faces significant limitations in automation and integration with external post-processing tools, leading to workflows with a steep learning curve, which are time-consuming and prone to human errors. Traditional methods involving the use of shell and Python scripts, MATLAB, and Microsoft Excel require extensive manual intervention and lack flexibility, adding complexity to evolving scenarios. This study explores the potential of Large Language Models (LLMs) and AI agents to address these limitations. AI agents, integrate natural language processing with autonomous reasoning for decision-making and adaptive planning, making them ideal for automation. We introduce AutoFLUKA, an AI agent application developed using the LangChain Python Framework to automate typical MC simulation workflows in FLUKA. AutoFLUKA can modify FLUKA input files, execute simulations, and efficiently process results for visualization, significantly reducing human labor and error. Our case studies demonstrate that AutoFLUKA can handle both generalized and domain-specific cases, such as Microdosimetry, with an streamlined automated workflow, showcasing its scalability and flexibility. The study also highlights the potential of Retrieval Augmentation Generation (RAG) tools to act as virtual assistants for FLUKA, further improving user experience, time and efficiency. In conclusion, AutoFLUKA represents a significant advancement in automating MC simulation workflows, offering a robust solution to the inherent limitations. This innovation not only saves time and resources but also opens new paradigms for research and development in high energy physics, medical physics, nuclear engineering space and environmental science.

[Arxiv](https://arxiv.org/abs/2410.15222)