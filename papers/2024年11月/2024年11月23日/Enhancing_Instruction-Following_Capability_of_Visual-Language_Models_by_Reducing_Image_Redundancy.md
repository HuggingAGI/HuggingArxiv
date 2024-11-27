# 通过降低图像冗余来提升视觉语言模型的指令跟随能力

发布时间：2024年11月23日

`LLM应用` `多模态` `语言模型`

> Enhancing Instruction-Following Capability of Visual-Language Models by Reducing Image Redundancy

# 摘要

> 大型语言模型（LLMs）具备强大的指令遵循能力，能依照人类指令去解读和执行任务。多模态大型语言模型（MLLMs）的指令遵循能力逊于 LLMs，二者存在显著差距。本研究开展了一项试点实验，结果显示对视觉标记进行空间下采样能大幅提升 MLLMs 的指令遵循能力，这是因为视觉模态存在大量冗余。不过，这种直观方法严重损害了 MLLM 的多模态理解能力。本文提出了视觉模态标记压缩（VMTC）和跨模态注意力抑制（CMAI）策略，旨在通过抑制内容生成时不相关视觉标记的影响，缩小 MLLMs 与 LLMs 的差距，增强 MLLMs 的指令遵循能力，同时保留其多模态理解能力。在 VMTC 模块中，保留主要标记，通过标记聚类和合并压缩冗余标记。在 CMAI 过程中，借助文本到文本的注意力聚合文本到图像的注意力，获取文本到图像的焦点分数，对分数低的文本-图像标记对进行注意力抑制。我们针对指令遵循能力以及 VQA-V2、GQA、TextVQA、MME 和 MMBench 这五个基准开展的综合实验表明，所提策略显著增强了 MLLMs 的指令遵循能力，同时也保留了其理解和处理多模态输入的能力。

> Large Language Models (LLMs) have strong instruction-following capability to interpret and execute tasks as directed by human commands. Multimodal Large Language Models (MLLMs) have inferior instruction-following ability compared to LLMs. However, there is a significant gap in the instruction-following capabilities between the MLLMs and LLMs. In this study, we conduct a pilot experiment, which demonstrates that spatially down-sampling visual tokens significantly enhances the instruction-following capability of MLLMs. This is attributed to the substantial redundancy in visual modality. However, this intuitive method severely impairs the MLLM's multimodal understanding capability. In this paper, we propose Visual-Modality Token Compression (VMTC) and Cross-Modality Attention Inhibition (CMAI) strategies to alleviate this gap between MLLMs and LLMs by inhibiting the influence of irrelevant visual tokens during content generation, increasing the instruction-following ability of the MLLMs while retaining their multimodal understanding capacity. In VMTC module, the primary tokens are retained and the redundant tokens are condensed by token clustering and merging. In CMAI process, we aggregate text-to-image attentions by text-to-text attentions to obtain a text-to-image focus score. Attention inhibition is performed on the text-image token pairs with low scores. Our comprehensive experiments over instruction-following capabilities and VQA-V2, GQA, TextVQA, MME and MMBench five benchmarks, demonstrate that proposed strategy significantly enhances the instruction following capability of MLLMs while preserving the ability to understand and process multimodal inputs.

[Arxiv](https://arxiv.org/abs/2411.15453)