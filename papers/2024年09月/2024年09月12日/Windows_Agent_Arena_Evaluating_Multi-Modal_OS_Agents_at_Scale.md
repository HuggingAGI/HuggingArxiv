# Windows Agent Arena：大规模评测多模态操作系统代理

发布时间：2024年09月12日

`Agent` `软件开发` `人工智能`

> Windows Agent Arena: Evaluating Multi-Modal OS Agents at Scale

# 摘要

> 大型语言模型 (LLM) 在作为计算机代理方面展现出巨大潜力，能够提升人类在多模态任务中的生产力和软件可访问性，这些任务需要规划和推理。然而，在现实环境中评估代理性能仍面临挑战：(i) 多数基准局限于特定模态或领域，(ii) 完整评估因任务的多步骤性质而耗时较长。为此，我们推出了 Windows Agent Arena：一个专注于 Windows 操作系统的可复现、通用环境，代理可在真实 Windows OS 中自由操作，并使用与人类用户相同的广泛应用和工具。我们基于 OSWorld 框架创建了 150 多个多样化任务，涵盖规划、屏幕理解和工具使用等领域。该基准可扩展，并在 Azure 中可并行化，仅需 20 分钟即可完成全面评估。为展示其能力，我们引入了多模态代理 Navi，其在 Windows 领域成功率达 19.5%，远低于人类（74.5%）。Navi 在 Mind2Web 基准上也表现优异。我们深入分析了 Navi 的性能，并探讨了未来在代理开发和数据生成方面的研究机会。

> Large language models (LLMs) show remarkable potential to act as computer agents, enhancing human productivity and software accessibility in multi-modal tasks that require planning and reasoning. However, measuring agent performance in realistic environments remains a challenge since: (i) most benchmarks are limited to specific modalities or domains (e.g. text-only, web navigation, Q&A, coding) and (ii) full benchmark evaluations are slow (on order of magnitude of days) given the multi-step sequential nature of tasks. To address these challenges, we introduce the Windows Agent Arena: a reproducible, general environment focusing exclusively on the Windows operating system (OS) where agents can operate freely within a real Windows OS and use the same wide range of applications, tools, and web browsers available to human users when solving tasks. We adapt the OSWorld framework (Xie et al., 2024) to create 150+ diverse Windows tasks across representative domains that require agent abilities in planning, screen understanding, and tool usage. Our benchmark is scalable and can be seamlessly parallelized in Azure for a full benchmark evaluation in as little as 20 minutes. To demonstrate Windows Agent Arena's capabilities, we also introduce a new multi-modal agent, Navi. Our agent achieves a success rate of 19.5% in the Windows domain, compared to 74.5% performance of an unassisted human. Navi also demonstrates strong performance on another popular web-based benchmark, Mind2Web. We offer extensive quantitative and qualitative analysis of Navi's performance, and provide insights into the opportunities for future research in agent development and data generation using Windows Agent Arena.
  Webpage: https://microsoft.github.io/WindowsAgentArena
  Code: https://github.com/microsoft/WindowsAgentArena

[Arxiv](https://arxiv.org/abs/2409.08264)