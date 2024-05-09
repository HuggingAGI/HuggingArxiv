# 视觉图谱：借助大型多模态模型，探索视觉场景中的图论难题。

发布时间：2024年05月08日

`LLM应用

这篇论文聚焦于大型多模态模型（LMMs）在视觉理解和数学推理方面的应用，特别是在处理多模态图论问题时的能力。它介绍了VisionGraph基准，并探讨了描述-程序-推理（DPR）链如何提升逻辑推理的准确性。这些内容与LLM的应用紧密相关，特别是在评估和提升模型在特定任务上的性能方面。因此，这篇论文应归类于LLM应用。` `人工智能` `教育科技`

> VisionGraph: Leveraging Large Multimodal Models for Graph Theory Problems in Visual Context

# 摘要

> 大型多模态模型（LMMs）在视觉理解和数学推理方面取得了显著成就，尤其是在视觉环境中的数学推理能力得到了显著提升。然而，多模态图论问题对LMMs提出了挑战，要求它们准确理解图形结构并进行多步骤视觉图推理。为了推动这一领域的发展，我们首次推出了VisionGraph基准，旨在评估LMMs解决复杂图论问题的能力，涵盖了从连通性到最短路径的八项任务。我们还引入了描述-程序-推理（DPR）链，通过生成图形结构描述和算法感知推理来提升逻辑推理的准确性。研究结果显示：1) GPT-4V在多步骤图推理中超越了Gemini Pro；2) 尽管经过微调，LMMs在图形结构感知上仍显不足，影响了问题解决效率；3) DPR显著增强了LMMs的多步骤推理能力，GPT-4V（DPR）达到了业界领先水平。

> Large Multimodal Models (LMMs) have achieved impressive success in visual understanding and reasoning, remarkably improving the performance of mathematical reasoning in a visual context. Yet, a challenging type of visual math lies in the multimodal graph theory problem, which demands that LMMs understand the graphical structures accurately and perform multi-step reasoning on the visual graph. Additionally, exploring multimodal graph theory problems will lead to more effective strategies in fields like biology, transportation, and robotics planning. To step forward in this direction, we are the first to design a benchmark named VisionGraph, used to explore the capabilities of advanced LMMs in solving multimodal graph theory problems. It encompasses eight complex graph problem tasks, from connectivity to shortest path problems. Subsequently, we present a Description-Program-Reasoning (DPR) chain to enhance the logical accuracy of reasoning processes through graphical structure description generation and algorithm-aware multi-step reasoning. Our extensive study shows that 1) GPT-4V outperforms Gemini Pro in multi-step graph reasoning; 2) All LMMs exhibit inferior perception accuracy for graphical structures, whether in zero/few-shot settings or with supervised fine-tuning (SFT), which further affects problem-solving performance; 3) DPR significantly improves the multi-step graph reasoning capabilities of LMMs and the GPT-4V (DPR) agent achieves SOTA performance.

[Arxiv](https://arxiv.org/abs/2405.04950)