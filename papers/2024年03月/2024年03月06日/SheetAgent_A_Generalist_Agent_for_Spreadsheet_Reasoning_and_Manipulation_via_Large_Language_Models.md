# SheetAgent 是一款借助大型语言模型，实现对电子表格进行高效推理与灵活操控的全能型智能助手。

发布时间：2024年03月06日

`Agent`

> SheetAgent: A Generalist Agent for Spreadsheet Reasoning and Manipulation via Large Language Models

> 电子表格操作已成为提高日常工作效率的必备手段，然而面对需要复杂推理及解决实际问题的场景（如长链条多步骤推理及含糊不清的需求），尽管已尝试将大型语言模型（LLM）应用至自动化处理，但效果尚待突破。为此，我们构建了一个名为$\textbf{SheetRM}$的基准测试平台，它聚焦于模拟真实生活中带来推理挑战的长时序、多类型任务。为有效应对这些挑战，我们创新设计了$\textbf{SheetAgent}$，一个充分利用LLM力量的自主智能体。SheetAgent由$\textit{Planner}$规划者、$\textit{Informer}$信息器和$\textit{Retriever}$检索器这三个协作模块构成，能通过循环任务推理和自我反思，在无需人工介入的情况下实现对电子表格的高级推理和精准操控。大量的实验验证表明，SheetAgent在多项基准测试中较基础方法提高了20%-30%的完成率，不仅在电子表格操作准确性上有所提升，还展现了出色的表格逻辑推理能力。欲了解更多详细内容和可视化展示，请访问https://sheetagent.github.io。

> Spreadsheet manipulation is widely existing in most daily works and significantly improves working efficiency. Large language model (LLM) has been recently attempted for automatic spreadsheet manipulation but has not yet been investigated in complicated and realistic tasks where reasoning challenges exist (e.g., long horizon manipulation with multi-step reasoning and ambiguous requirements). To bridge the gap with the real-world requirements, we introduce $\textbf{SheetRM}$, a benchmark featuring long-horizon and multi-category tasks with reasoning-dependent manipulation caused by real-life challenges. To mitigate the above challenges, we further propose $\textbf{SheetAgent}$, a novel autonomous agent that utilizes the power of LLMs. SheetAgent consists of three collaborative modules: $\textit{Planner}$, $\textit{Informer}$, and $\textit{Retriever}$, achieving both advanced reasoning and accurate manipulation over spreadsheets without human interaction through iterative task reasoning and reflection. Extensive experiments demonstrate that SheetAgent delivers 20-30% pass rate improvements on multiple benchmarks over baselines, achieving enhanced precision in spreadsheet manipulation and demonstrating superior table reasoning abilities. More details and visualizations are available at https://sheetagent.github.io.

[Arxiv](https://arxiv.org/abs/2403.03636)