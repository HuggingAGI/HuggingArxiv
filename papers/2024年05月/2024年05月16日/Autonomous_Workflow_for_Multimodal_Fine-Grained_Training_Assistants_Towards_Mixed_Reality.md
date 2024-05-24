# 混合现实环境下的自主多模态细粒度训练助手工作流程

发布时间：2024年05月16日

`Agent

这篇论文主要探讨了自主AI代理在扩展现实（XR）应用中的集成和训练，以及如何通过融合大型语言模型（LLM）、记忆、规划功能和视觉-语言代理来提供多模态细致指导。此外，论文还介绍了LEGO-MRTA数据集的创建，并评估了不同开源LLM在此数据集上的表现。这些内容主要集中在AI代理的设计、实现和应用上，因此归类为Agent。` `扩展现实` `人机交互`

> Autonomous Workflow for Multimodal Fine-Grained Training Assistants Towards Mixed Reality

# 摘要

> 随着大型语言模型（LLMs）的飞速发展，自主AI代理已成为自动解析语言环境的先锋。尽管如此，多模态环境的深入理解仍是一片待开发的领域。本研究精心打造了一套自主工作流程，旨在将AI代理融入扩展现实（XR）应用，进行精准训练。我们首次展示了在XR试点环境中，为乐高积木组装提供多模态细致指导的AI助手。该助手融合了LLM与记忆、规划功能，并能与XR工具互动，同时配备视觉-语言代理，使其能基于过往经验做出决策。此外，我们推出了LEGO-MRTA，一个由商业LLM驱动的工作流程自动生成的多模态细致组装对话数据集，涵盖了多模态指南、对话、XR反馈及视觉问答。最后，我们以几种主流开源LLM为基准，评估了它们在提议数据集上微调前后的表现。我们期待这一工作流程能推动更智能的XR交互助手的发展，同时激发AI与HCI领域的研究热情。

> Autonomous artificial intelligence (AI) agents have emerged as promising protocols for automatically understanding the language-based environment, particularly with the exponential development of large language models (LLMs). However, a fine-grained, comprehensive understanding of multimodal environments remains under-explored. This work designs an autonomous workflow tailored for integrating AI agents seamlessly into extended reality (XR) applications for fine-grained training. We present a demonstration of a multimodal fine-grained training assistant for LEGO brick assembly in a pilot XR environment. Specifically, we design a cerebral language agent that integrates LLM with memory, planning, and interaction with XR tools and a vision-language agent, enabling agents to decide their actions based on past experiences. Furthermore, we introduce LEGO-MRTA, a multimodal fine-grained assembly dialogue dataset synthesized automatically in the workflow served by a commercial LLM. This dataset comprises multimodal instruction manuals, conversations, XR responses, and vision question answering. Last, we present several prevailing open-resource LLMs as benchmarks, assessing their performance with and without fine-tuning on the proposed dataset. We anticipate that the broader impact of this workflow will advance the development of smarter assistants for seamless user interaction in XR environments, fostering research in both AI and HCI communities.

[Arxiv](https://arxiv.org/abs/2405.13034)