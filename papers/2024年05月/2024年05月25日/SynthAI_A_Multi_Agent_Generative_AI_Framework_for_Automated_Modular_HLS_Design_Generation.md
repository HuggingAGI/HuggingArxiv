# SynthAI：多代理生成式AI框架，专为自动化模块化高层次综合设计而生

发布时间：2024年05月25日

`Agent

这篇论文介绍了一种名为 SynthAI 的高层次综合（HLS）设计自动化方法，它结合了 ReAct 代理、思维链提示、网络搜索技术和检索增强生成框架。这些组件共同作用于一个结构化的决策图上，以分解和生成复杂的硬件设计任务。这种集成的方法体现了 Agent 的概念，即一个能够自主执行任务并做出决策的系统。因此，这篇论文应归类于Agent。` `硬件设计` `自动化设计`

> SynthAI: A Multi Agent Generative AI Framework for Automated Modular HLS Design Generation

# 摘要

> 本文介绍了 SynthAI，一种前沿的高层次综合（HLS）设计自动化方法。它巧妙融合了 ReAct 代理、思维链提示、网络搜索技术及检索增强生成框架，构建于一个结构化的决策图之上。SynthAI 能将复杂的硬件设计任务有序分解为多个阶段和更小、易管理的部分，从而生成符合用户设计目标和功能需求的高质量设计。通过多个案例研究，我们展示了 SynthAI 在从单一提示出发，高效生成复杂多模块逻辑设计方面的卓越能力。其代码已公开于 GitHub 仓库：\url{https://github.com/sarashs/FPGA_AGI}。

> In this paper, we introduce SynthAI, a pioneering method for the automated creation of High-Level Synthesis (HLS) designs. SynthAI integrates ReAct agents, Chain-of-Thought (CoT) prompting, web search technologies, and the Retrieval-Augmented Generation (RAG) framework within a structured decision graph. This innovative approach enables the systematic decomposition of complex hardware design tasks into multiple stages and smaller, manageable modules. As a result, SynthAI produces synthesizable designs that closely adhere to user-specified design objectives and functional requirements. We further validate the capabilities of SynthAI through several case studies, highlighting its proficiency in generating complex, multi-module logic designs from a single initial prompt. The SynthAI code is provided via the following repo: \url{https://github.com/sarashs/FPGA_AGI}

![SynthAI：多代理生成式AI框架，专为自动化模块化高层次综合设计而生](../../../paper_images/2405.16072/single_node.png)

![SynthAI：多代理生成式AI框架，专为自动化模块化高层次综合设计而生](../../../paper_images/2405.16072/litreview.png)

![SynthAI：多代理生成式AI框架，专为自动化模块化高层次综合设计而生](../../../paper_images/2405.16072/moduledesign.png)

[Arxiv](https://arxiv.org/abs/2405.16072)