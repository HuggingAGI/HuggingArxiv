# 代码与文档变动的关联性：初步探究

发布时间：2024年10月08日

`LLM应用` `软件开发` `开源项目`

> Linking Code and Documentation Churn: Preliminary Analysis

# 摘要

> 代码 churn 衡量项目中代码的增删改量，常用于评估代码库的稳定性和可维护性。程序理解同样关键，尤其是变更的可理解性。文档在知识传递中不可或缺，特别是新维护者接手旧代码时。我们强调文档更新的必要性，这不仅关乎项目健康，也影响其作为第三方库的信任度。因此，每次代码变更都应伴随文档更新（即文档 churn）。将代码 churn 与文档更新关联，有助于知识传递和简化程序理解，从而提升项目可持续性。本研究分析了三个 GitHub 开源项目中代码 churn 与文档更新的同步性，通过定性分析和仓库挖掘，探讨两者随时间的对齐与相关性。我们旨在识别哪些代码变更与文档同步，并评估文档自动生成的潜力。初步结果显示，各项目同步程度不一，凸显了集成文档实践的重要性，并探讨了如何利用 AI 技术（如 LLMs）来保持代码与文档的同步。本研究的创新在于展示了通过同步代码与文档更新，如何提升开发周期的多样性和效率。

> Code churn refers to the measure of the amount of code added, modified, or deleted in a project and is often used to assess codebase stability and maintainability. Program comprehension or how understandable the changes are, is equally important for maintainability. Documentation is crucial for knowledge transfer, especially when new maintainers take over abandoned code. We emphasize the need for corresponding documentation updates, as this reflects project health and trustworthiness as a third-party library. Therefore, we argue that every code change should prompt a documentation update (defined as documentation churn). Linking code churn changes with documentation updates is important for project sustainability, as it facilitates knowledge transfer and reduces the effort required for program comprehension. This study investigates the synchrony between code churn and documentation updates in three GitHub open-source projects. We will use qualitative analysis and repository mining to examine the alignment and correlation of code churn and documentation updates over time. We want to identify which code changes are likely synchronized with documentation and to what extent documentation can be auto-generated. Preliminary results indicate varying degrees of synchrony across projects, highlighting the importance of integrated concurrent documentation practices and providing insights into how recent technologies like AI, in the form of Large Language Models (i.e., LLMs), could be leveraged to keep code and documentation churn in sync. The novelty of this study lies in demonstrating how synchronizing code changes with documentation updates can improve the development lifecycle by enhancing diversity and efficiency.

[Arxiv](https://arxiv.org/abs/2410.05992)