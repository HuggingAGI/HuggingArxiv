# cPAPERS：科学论文中情境化与多模态交互对话的数据集宝库

发布时间：2024年06月12日

`Agent

理由：这篇论文主要关注的是在SIMMC研究领域中，如何通过定制的方法来满足科研人员与科学论文（包括文本、公式、图表和表格）交互的需求。论文中提到的cPAPERS数据集和基于LLMs的零样本和微调方法，都是为了增强Agent（在这里指的是科研人员或其代理）与科学论文的交互能力。因此，这篇论文更符合Agent分类，因为它主要探讨的是如何通过技术手段提升用户与科学论文的交互体验和效率。` `问答系统`

> cPAPERS: A Dataset of Situated and Multimodal Interactive Conversations in Scientific Papers

# 摘要

> 在SIMMC研究领域，科学论文的交互成为一个新兴研究方向。科学论文由文本、公式、图表和表格构成，因此需要针对每个组件定制SIMMC方法，以满足科研人员深入探究和交互的需求。本研究推出了cPAPERS数据集，该数据集包含基于学术论文评审的对话式问答对，这些问答对与arXiv上的科学文档中的论文组件及其引用紧密相关。我们设计了一种策略，从OpenReview收集问答对，并将其与LaTeX源文件的上下文信息相联系。同时，我们提出了一系列基于LLMs的零样本和微调方法，作为处理cPAPERS数据集的基准。

> An emerging area of research in situated and multimodal interactive conversations (SIMMC) includes interactions in scientific papers. Since scientific papers are primarily composed of text, equations, figures, and tables, SIMMC methods must be developed specifically for each component to support the depth of inquiry and interactions required by research scientists. This work introduces Conversational Papers (cPAPERS), a dataset of conversational question-answer pairs from reviews of academic papers grounded in these paper components and their associated references from scientific documents available on arXiv. We present a data collection strategy to collect these question-answer pairs from OpenReview and associate them with contextual information from LaTeX source files. Additionally, we present a series of baseline approaches utilizing Large Language Models (LLMs) in both zero-shot and fine-tuned configurations to address the cPAPERS dataset.

![cPAPERS：科学论文中情境化与多模态交互对话的数据集宝库](../../../paper_images/2406.08398/overview.png)

[Arxiv](https://arxiv.org/abs/2406.08398)