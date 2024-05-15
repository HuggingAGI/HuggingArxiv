# 推动科学领域的AI公平：普及视觉语言模型研究的泛化领域提示学习方法

发布时间：2024年05月14日

`LLM应用

这篇论文探讨了如何通过广义领域提示学习（GDPL）框架，利用小规模模型和少量样本实现大规模视觉-语言模型（VLMs）在特定领域的识别能力转移。这种方法不需要大量标注数据和资源，有助于打破学术界与工业界之间的壁垒，促进VLMs研究的可持续性和包容性。因此，它属于LLM应用的范畴，因为它关注的是如何应用现有的LLM技术来解决特定领域的问题，而不是深入探讨LLM的理论基础或Agent的设计与实现。` `视觉-语言模型` `领域适应`

> Promoting AI Equity in Science: Generalized Domain Prompt Learning for Accessible VLM Research

# 摘要

> 大规模视觉-语言模型（VLMs）在自然视觉任务中表现卓越，激发了跨领域研究者对特定领域VLMs的探索。然而，构建特定领域VLMs需要大量标注数据和资源，这些资源主要集中在工业界，限制了学术界的研究。为此，我们提出了广义领域提示学习（GDPL）框架，它通过小规模模型和少量样本，实现了VLMs在特定领域的识别能力转移，无需大量数据或资源。GDPL利用四元网络赋予语言分支领域知识，揭示了特定领域视觉特征与自然视觉上下文之间的联系。同时，通过视觉提示特征的分层传播，GDPL引导视觉分支深入特定领域。我们还引入了一种新的低秩适应方法，以最大化VLMs的领域适应性。在多个领域的实验证明了GDPL的有效性，它能在提示学习范式中达到顶尖的领域识别性能。我们的框架促进了VLMs研究的可持续性和包容性，打破了学术界与工业界之间的壁垒。

> Large-scale Vision-Language Models (VLMs) have demonstrated exceptional performance in natural vision tasks, motivating researchers across domains to explore domain-specific VLMs. However, the construction of powerful domain-specific VLMs demands vast amounts of annotated data, substantial electrical energy, and computing resources, primarily accessible to industry, yet hindering VLM research in academia. To address this challenge and foster sustainable and equitable VLM research, we present the Generalized Domain Prompt Learning (GDPL) framework. GDPL facilitates the transfer of VLMs' robust recognition capabilities from natural vision to specialized domains, without the need for extensive data or resources. By leveraging small-scale domain-specific foundation models and minimal prompt samples, GDPL empowers the language branch with domain knowledge through quaternion networks, uncovering cross-modal relationships between domain-specific vision features and natural vision-based contextual embeddings. Simultaneously, GDPL guides the vision branch into specific domains through hierarchical propagation of generated vision prompt features, grounded in well-matched vision-language relations. Furthermore, to fully harness the domain adaptation potential of VLMs, we introduce a novel low-rank adaptation approach. Extensive experiments across diverse domains like remote sensing, medical imaging, geology, Synthetic Aperture Radar, and fluid dynamics, validate the efficacy of GDPL, demonstrating its ability to achieve state-of-the-art domain recognition performance in a prompt learning paradigm. Our framework paves the way for sustainable and inclusive VLM research, transcending the barriers between academia and industry.

[Arxiv](https://arxiv.org/abs/2405.08668)