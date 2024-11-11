# DesignRepair：使用大型语言模型的双流设计指南感知前端修复

发布时间：2024年11月03日

`LLM应用` `前端开发` `用户界面设计`

> DesignRepair: Dual-Stream Design Guideline-Aware Frontend Repair with Large Language Models

# 摘要

> 大型语言模型（LLMs）的兴起通过像 Vercel 的 V0 这样的工具简化了前端界面的创建，但也在设计质量（例如，可访问性和可用性）方面出现了挑战。当前的解决方案，往往由于其重点、通用性或数据依赖性的限制，在解决这些复杂性方面存在不足。此外，它们中没有一个检查 LLM 生成的 UI 设计的质量。在这项工作中，我们引入了 DesignRepair，这是一个新颖的双流设计指南感知系统，从代码方面和渲染页面方面检查和修复 UI 设计质量问题。我们利用成熟和流行的 Material Design 作为我们的知识库来指导这个过程。具体来说，我们首先构建了一个全面的知识库，将谷歌的 Material Design 原则编码为低级组件知识库和高级系统设计知识库。之后，DesignRepair 采用 LLM 来提取关键组件，并利用 Playwright 工具进行精确的页面分析，将这些与已建立的知识库对齐。最后，我们将检索增强生成与像 GPT-4 这样的最先进的 LLM 集成，通过分而治之的策略全面改进和修复前端代码。我们广泛的评估验证了我们方法的有效性和实用性，展示了在遵循设计指南、可访问性和用户体验指标方面的显著增强。

> The rise of Large Language Models (LLMs) has streamlined frontend interface creation through tools like Vercel's V0, yet surfaced challenges in design quality (e.g., accessibility, and usability). Current solutions, often limited by their focus, generalisability, or data dependency, fall short in addressing these complexities. Moreover, none of them examine the quality of LLM-generated UI design. In this work, we introduce DesignRepair, a novel dual-stream design guideline-aware system to examine and repair the UI design quality issues from both code aspect and rendered page aspect. We utilised the mature and popular Material Design as our knowledge base to guide this process. Specifically, we first constructed a comprehensive knowledge base encoding Google's Material Design principles into low-level component knowledge base and high-level system design knowledge base. After that, DesignRepair employs a LLM for the extraction of key components and utilizes the Playwright tool for precise page analysis, aligning these with the established knowledge bases. Finally, we integrate Retrieval-Augmented Generation with state-of-the-art LLMs like GPT-4 to holistically refine and repair frontend code through a strategic divide and conquer approach. Our extensive evaluations validated the efficacy and utility of our approach, demonstrating significant enhancements in adherence to design guidelines, accessibility, and user experience metrics.

[Arxiv](https://arxiv.org/abs/2411.01606)