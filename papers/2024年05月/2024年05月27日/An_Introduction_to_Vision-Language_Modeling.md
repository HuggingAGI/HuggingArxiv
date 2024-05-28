# 视觉与语言建模入门

发布时间：2024年05月27日

`LLM应用

这篇论文摘要主要讨论了视觉-语言模型（VLM）在视觉领域的应用，包括其定义、工作原理、训练方法以及评估策略。此外，还探讨了将VLM应用于视频的可能性。这些内容主要集中在LLM的实际应用层面，而非理论研究或Agent、RAG的特定领域。因此，将其归类为LLM应用是合适的。` `视觉-语言模型` `人工智能`

> An Introduction to Vision-Language Modeling

# 摘要

> 随着大型语言模型（LLMs）的兴起，人们开始探索其在视觉领域的应用。从引导我们在陌生环境中的视觉助手，到仅凭文本描述生成图像的模型，视觉-语言模型（VLM）正改变我们与技术的互动。然而，要提升这些模型的可靠性，仍需克服诸多挑战。语言虽为离散，视觉却存在于高维空间，其概念难以简单离散化。为了深入理解视觉与语言间的映射机制，我们撰写了这篇VLM入门指南，旨在为初入此领域者提供帮助。文章首先解释了VLM的定义、工作原理及训练方法，随后探讨了评估VLM的策略，并扩展讨论了将VLM应用于视频的可能性。

> Following the recent popularity of Large Language Models (LLMs), several attempts have been made to extend them to the visual domain. From having a visual assistant that could guide us through unfamiliar environments to generative models that produce images using only a high-level text description, the vision-language model (VLM) applications will significantly impact our relationship with technology. However, there are many challenges that need to be addressed to improve the reliability of those models. While language is discrete, vision evolves in a much higher dimensional space in which concepts cannot always be easily discretized. To better understand the mechanics behind mapping vision to language, we present this introduction to VLMs which we hope will help anyone who would like to enter the field. First, we introduce what VLMs are, how they work, and how to train them. Then, we present and discuss approaches to evaluate VLMs. Although this work primarily focuses on mapping images to language, we also discuss extending VLMs to videos.

![视觉与语言建模入门](../../../paper_images/2405.17247/x1.png)

![视觉与语言建模入门](../../../paper_images/2405.17247/x2.png)

![视觉与语言建模入门](../../../paper_images/2405.17247/x3.png)

[Arxiv](https://arxiv.org/abs/2405.17247)