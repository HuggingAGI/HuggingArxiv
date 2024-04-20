# 本文系统性地审视了大型语言模型中的提示工程，涵盖了相关技术和应用。

发布时间：2024年02月05日

`LLM应用` `人工智能`

> A Systematic Survey of Prompt Engineering in Large Language Models: Techniques and Applications

# 摘要

> 提示工程正成为提升大型语言模型（LLMs）和视觉-语言模型（VLMs）功能的关键技术。它通过特定任务的提示——即指令，来提升模型效率，而无需更改模型的核心参数。这些提示通过激发基于给定指令的期望模型行为，实现了预训练模型向下游任务的平滑过渡。提示形式多样，可以是提供指导上下文的自然语言指令，也可以是触发相关知识的向量表示。这一领域在问答、常识推理等多个应用场景中取得了显著成效。尽管如此，当前对于多样化的提示工程技术和方法的系统化梳理和理解尚显不足。本篇综述文章旨在填补这一空白，通过应用领域分类，系统梳理了提示工程的最新进展。对于每种提示策略，文章不仅概述了其方法论、应用场景、所涉及的模型和数据集，还深入分析了各自的优势与局限，并辅以分类图和表格，总结了各提示技术的关键信息。这一系统性的研究不仅加深了对该领域的理解，也为未来的研究指明了方向，揭示了面临的挑战和潜在的机遇。

> Prompt engineering has emerged as an indispensable technique for extending the capabilities of large language models (LLMs) and vision-language models (VLMs). This approach leverages task-specific instructions, known as prompts, to enhance model efficacy without modifying the core model parameters. Rather than updating the model parameters, prompts allow seamless integration of pre-trained models into downstream tasks by eliciting desired model behaviors solely based on the given prompt. Prompts can be natural language instructions that provide context to guide the model or learned vector representations that activate relevant knowledge. This burgeoning field has enabled success across various applications, from question-answering to commonsense reasoning. However, there remains a lack of systematic organization and understanding of the diverse prompt engineering methods and techniques. This survey paper addresses the gap by providing a structured overview of recent advancements in prompt engineering, categorized by application area. For each prompting approach, we provide a summary detailing the prompting methodology, its applications, the models involved, and the datasets utilized. We also delve into the strengths and limitations of each approach and include a taxonomy diagram and table summarizing datasets, models, and critical points of each prompting technique. This systematic analysis enables a better understanding of this rapidly developing field and facilitates future research by illuminating open challenges and opportunities for prompt engineering.

![本文系统性地审视了大型语言模型中的提示工程，涵盖了相关技术和应用。](../../../paper_images/2402.07927/x1.png)

[Arxiv](https://arxiv.org/abs/2402.07927)