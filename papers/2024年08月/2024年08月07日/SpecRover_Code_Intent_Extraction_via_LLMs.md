# SpecRover：利用 LLM 提取代码意图

发布时间：2024年08月07日

`Agent` `软件开发` `人工智能`

> SpecRover: Code Intent Extraction via LLMs

# 摘要

> 自主程序改进，即自动生成错误修复和新功能，可通过结合大型语言模型（LLM）和程序分析的LLM代理实现。在这项研究中，我们专注于在LLM代理中进行高效且经济的迭代规范推理。面对一个GitHub问题，我们的目标是通过迭代代码搜索和规范推理，从项目结构和行为中推断出开发意图。这些推断由审查代理评估，确保补丁质量并提供信心度量。我们的方法SpecRover（基于AutoCodeRover-v2）在处理2294个GitHub问题的SWE-Bench中，效能提升了50%以上，且在SWE-Bench lite中解决每个问题的成本仅为0.65美元。SpecRover不仅优化了补丁接受时机，还强调了规范推理在自动化程序修复中的关键作用，即便在LLM时代也是如此。

> Autonomous program improvement typically involves automatically producing bug fixes and feature additions. Such program improvement can be accomplished by a combination of large language model (LLM) and program analysis capabilities, in the form of an LLM agent. Since program repair or program improvement typically requires a specification of intended behavior - specification inference can be useful for producing high quality program patches. In this work, we examine efficient and low-cost workflows for iterative specification inference within an LLM agent. Given a GitHub issue to be resolved in a software project, our goal is to conduct iterative code search accompanied by specification inference - thereby inferring intent from both the project structure and behavior. The intent thus captured is examined by a reviewer agent with the goal of vetting the patches as well as providing a measure of confidence in the vetted patches. Our approach SpecRover (AutoCodeRover-v2) is built on the open-source LLM agent AutoCodeRover. In an evaluation on the full SWE-Bench consisting of 2294 GitHub issues, it shows more than 50% improvement in efficacy over AutoCodeRover. Compared to the open-source agents available, our work shows modest cost ($0.65 per issue) in resolving an average GitHub issue in SWE-Bench lite. The production of explanation by SpecRover allows for a better "signal" to be given to the developer, on when the suggested patches can be accepted with confidence. SpecRover also seeks to demonstrate the continued importance of specification inference in automated program repair, even as program repair technologies enter the LLM era.

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x1.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x2.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x3.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x4.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x5.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x6.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x7.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x8.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x9.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x10.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x11.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x12.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x13.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x14.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x15.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x16.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x17.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x18.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x19.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x20.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x21.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x22.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x23.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x24.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x25.png)

![SpecRover：利用 LLM 提取代码意图](../../../paper_images/2408.02232/x26.png)

[Arxiv](https://arxiv.org/abs/2408.02232)