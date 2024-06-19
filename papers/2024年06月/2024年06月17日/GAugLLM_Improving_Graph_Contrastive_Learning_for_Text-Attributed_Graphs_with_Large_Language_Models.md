# GAugLLM：借助大型语言模型优化文本属性图的图对比学习

发布时间：2024年06月17日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（如Mistral）来增强文本属性图（TAGs）的自监督图学习。论文中提出的GAugLLM框架通过混合提示专家技术和协作边修改器，有效地利用了大型语言模型的能力来优化图学习过程。这种方法的应用性质明显，因为它直接将LLM技术应用于解决图学习中的具体问题，而不是探讨LLM的理论基础或其内部机制。因此，这篇论文更适合归类于LLM应用。` `图学习`

> GAugLLM: Improving Graph Contrastive Learning for Text-Attributed Graphs with Large Language Models

# 摘要

> 本研究探索了文本属性图（TAGs）的自监督图学习，其中节点通过文本属性来表示。我们不同于传统方法，不通过扰动数值特征空间和改变图结构，而是利用语言监督来优化视图生成。这是因为实际应用中，文本属性为图结构提供了丰富的语义信息。但这也带来了挑战：文本属性的长度和质量不一，难以在不改变原意的情况下进行扰动；同时，文本与图结构并非自然对齐。为此，我们提出了GAugLLM框架，利用如Mistral等大型语言模型来增强图学习。我们采用了混合提示专家技术，通过提示工程自适应地修改文本属性并映射到数值空间。此外，我们还设计了协作边修改器，通过分析或建立节点间的联系来增强边的增强。实验结果显示，我们的框架能有效提升多个领域五个基准数据集上的对比学习方法性能，并能增强生成模型和图神经网络的表现。GAugLLM的开源代码已在Github上发布。

> This work studies self-supervised graph learning for text-attributed graphs (TAGs) where nodes are represented by textual attributes. Unlike traditional graph contrastive methods that perturb the numerical feature space and alter the graph's topological structure, we aim to improve view generation through language supervision. This is driven by the prevalence of textual attributes in real applications, which complement graph structures with rich semantic information. However, this presents challenges because of two major reasons. First, text attributes often vary in length and quality, making it difficulty to perturb raw text descriptions without altering their original semantic meanings. Second, although text attributes complement graph structures, they are not inherently well-aligned. To bridge the gap, we introduce GAugLLM, a novel framework for augmenting TAGs. It leverages advanced large language models like Mistral to enhance self-supervised graph learning. Specifically, we introduce a mixture-of-prompt-expert technique to generate augmented node features. This approach adaptively maps multiple prompt experts, each of which modifies raw text attributes using prompt engineering, into numerical feature space. Additionally, we devise a collaborative edge modifier to leverage structural and textual commonalities, enhancing edge augmentation by examining or building connections between nodes. Empirical results across five benchmark datasets spanning various domains underscore our framework's ability to enhance the performance of leading contrastive methods as a plug-in tool. Notably, we observe that the augmented features and graph structure can also enhance the performance of standard generative methods, as well as popular graph neural networks. The open-sourced implementation of our GAugLLM is available at Github.

![GAugLLM：借助大型语言模型优化文本属性图的图对比学习](../../../paper_images/2406.11945/x1.png)

![GAugLLM：借助大型语言模型优化文本属性图的图对比学习](../../../paper_images/2406.11945/x2.png)

![GAugLLM：借助大型语言模型优化文本属性图的图对比学习](../../../paper_images/2406.11945/x3.png)

![GAugLLM：借助大型语言模型优化文本属性图的图对比学习](../../../paper_images/2406.11945/x4.png)

![GAugLLM：借助大型语言模型优化文本属性图的图对比学习](../../../paper_images/2406.11945/x5.png)

![GAugLLM：借助大型语言模型优化文本属性图的图对比学习](../../../paper_images/2406.11945/x6.png)

![GAugLLM：借助大型语言模型优化文本属性图的图对比学习](../../../paper_images/2406.11945/x7.png)

[Arxiv](https://arxiv.org/abs/2406.11945)