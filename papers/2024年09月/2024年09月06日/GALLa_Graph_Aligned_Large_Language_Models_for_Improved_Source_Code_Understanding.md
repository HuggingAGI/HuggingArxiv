# GALLa：通过图对齐技术提升源代码理解能力的大型语言模型

发布时间：2024年09月06日

`LLM应用` `软件开发` `人工智能`

> GALLa: Graph Aligned Large Language Models for Improved Source Code Understanding

# 摘要

> 编程语言蕴含丰富的语义信息，如数据流图，这些信息在源代码表面难以捕捉。尽管现代代码语言模型已扩展至数十亿参数，但仍仅将代码视为文本，忽视其结构信息。而那些尝试编码结构信息的模型，则需修改Transformer架构，限制了其规模与预训练LLM的兼容性。为此，我们提出了GALLa——图对齐大型语言模型，结合图神经网络与跨模态对齐技术，在微调过程中将代码结构信息融入LLM。GALLa不仅模型与任务无关，还能在训练时仅依赖与微调数据无关的语料库中的结构图数据，推理时则无需额外成本。实验表明，GALLa在五个代码任务上，对从350M到8B参数的四个基线LLM均表现出色，甚至在强大的LLaMA3模型上也实现了显著提升。

> Programming languages possess rich semantic information such as data flow that is represented by graphs and not available from the surface form of source code. Recent code language models have scaled to billions of parameters, but model source code solely as text tokens while ignoring any other structural information. Conversely, models that do encode structural information of code make modifications to the Transformer architecture, limiting their scale and compatibility with pretrained LLMs. In this work, we take the best of both worlds with GALLa - Graph Aligned Large Language Model. GALLa utilizes graph neural networks and cross-modal alignment technologies to inject the structural information of code into LLMs as an auxiliary task during finetuning. This framework is both model-agnostic and task-agnostic, as it can be applied to any code LLM for any code downstream task, and requires the structural graph data only at training time from a corpus unrelated to the finetuning data, while incurring no cost at inference time over the baseline LLM. Experiments on five code tasks with four different baseline LLMs ranging in size from 350M to 8B validate the effectiveness of GALLa, demonstrating consistent improvement over the baseline, even for powerful models such as LLaMA3.

[Arxiv](https://arxiv.org/abs/2409.04183)