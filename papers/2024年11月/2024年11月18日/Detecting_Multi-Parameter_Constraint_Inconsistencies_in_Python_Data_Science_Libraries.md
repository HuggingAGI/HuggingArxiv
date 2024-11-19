# 检测 Python 数据科学库中的多参数约束不一致情况

发布时间：2024年11月18日

`LLM应用` `数据科学`

> Detecting Multi-Parameter Constraint Inconsistencies in Python Data Science Libraries

# 摘要

> 现代的 AI 及数据密集型软件系统高度依赖数据科学和机器学习库，此类库提供了关键的算法实现与计算框架。这些库所公开的复杂 API，其正确使用得遵循多个相互依存的参数间的约束。使用这些 API 的开发者应通过所提供的文档来知晓这些约束，任何偏差都可能引发意外状况。然而，在 API 文档中维持正确且一致的多参数约束，对于 API 的兼容性和可靠性而言，始终是重大挑战。为应对此挑战，我们提出了 MPDetector 来检测代码与文档之间的不一致，尤其聚焦于多参数约束。MPDetector 借助符号执行探索执行路径以在代码层面识别这些约束，并进一步运用大型语言模型（LLMs）从文档中提取相应约束。我们提出了一种定制的模糊约束逻辑，以协调 LLM 输出的不可预测性，并检测代码与文档约束之间的逻辑不一致。我们从四个热门的数据科学库收集并构建了两个数据集，并在其上对 MPDetector 进行了评估。结果显示，MPDetector 能有效检测不一致问题，准确率达 92.8%。我们还向库开发者报告了 14 个检测出的不一致问题，截至撰写时，他们已确认了 11 个问题。

> Modern AI- and Data-intensive software systems rely heavily on data science and machine learning libraries that provide essential algorithmic implementations and computational frameworks. These libraries expose complex APIs whose correct usage has to follow constraints among multiple interdependent parameters. Developers using these APIs are expected to learn about the constraints through the provided documentations and any discrepancy may lead to unexpected behaviors. However, maintaining correct and consistent multi-parameter constraints in API documentations remains a significant challenge for API compatibility and reliability. To address this challenge, we propose an MPDetector for detecting inconsistencies between code and documentation, specifically focusing on multi-parameter constraints. MPDetector identifies these constraints at the code level by exploring execution paths through symbolic execution and further extracts corresponding constraints from documentation using large language models (LLMs). We propose a customized fuzzy constraint logic to reconcile the unpredictability of LLM outputs and detect logical inconsistencies between the code and documentation constraints. We collected and constructed two datasets from four popular data science libraries and evaluated MPDetector on them. The results demonstrate that MPDetector can effectively detect inconsistency issues with the precision of 92.8%. We further reported 14 detected inconsistency issues to the library developers, who have confirmed 11 issues at the time of writing.

[Arxiv](https://arxiv.org/abs/2411.11410)