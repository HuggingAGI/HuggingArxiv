# VS助手：外科医生的得力助手，满足多样化的手术需求

发布时间：2024年05月13日

`Agent

这篇论文介绍了一个名为“多功能手术助手（VS-Assistant）”的智能系统，它基于多模态大型语言模型（MLLMs），能够理解外科医生的意图并执行多种手术任务。这个系统通过引入混合投影器（MOP）模块和手术功能调用调整策略，提升了手术多模态理解能力，并在神经外科领域的实验中证明了其有效性。这个系统可以被视为一个智能代理（Agent），因为它能够自主地执行任务并对外科医生的意图做出响应。因此，它被归类为Agent。` `手术辅助系统`

> VS-Assistant: Versatile Surgery Assistant on the Demand of Surgeons

# 摘要

> 手术干预对患者健康至关重要，现有算法虽已取得显著进展，但仍局限于特定任务和场景，且需手动整合功能，限制了其广泛应用。因此，我们期望一个智能且多才多艺的手术助手，能够精准洞察外科医生的意图，并灵活执行手术任务。本研究中，我们借助先进的多模态大型语言模型（MLLMs），打造了一款名为“多功能手术助手（VS-Assistant）”的智能系统，它能够精准解读外科意图，执行手术场景分析、器械检测等任务。为提升手术多模态理解能力，我们创新性地引入了混合投影器（MOP）模块，平衡自然与手术知识。同时，我们开发了手术功能调用调整策略，使VS-Assistant能够洞察手术意图，并按需调用手术功能，满足外科需求。在神经外科领域的广泛实验证明，VS-Assistant在理解外科意图方面超越了现有MLLM，在文本与视觉任务中表现卓越。我们将公开源代码和模型，以供进一步研究。

> The surgical intervention is crucial to patient healthcare, and many studies have developed advanced algorithms to provide understanding and decision-making assistance for surgeons. Despite great progress, these algorithms are developed for a single specific task and scenario, and in practice require the manual combination of different functions, thus limiting the applicability. Thus, an intelligent and versatile surgical assistant is expected to accurately understand the surgeon's intentions and accordingly conduct the specific tasks to support the surgical process. In this work, by leveraging advanced multimodal large language models (MLLMs), we propose a Versatile Surgery Assistant (VS-Assistant) that can accurately understand the surgeon's intention and complete a series of surgical understanding tasks, e.g., surgical scene analysis, surgical instrument detection, and segmentation on demand. Specifically, to achieve superior surgical multimodal understanding, we devise a mixture of projectors (MOP) module to align the surgical MLLM in VS-Assistant to balance the natural and surgical knowledge. Moreover, we devise a surgical Function-Calling Tuning strategy to enable the VS-Assistant to understand surgical intentions, and thus make a series of surgical function calls on demand to meet the needs of the surgeons. Extensive experiments on neurosurgery data confirm that our VS-Assistant can understand the surgeon's intention more accurately than the existing MLLM, resulting in overwhelming performance in textual analysis and visual tasks. Source code and models will be made public.

[Arxiv](https://arxiv.org/abs/2405.08272)