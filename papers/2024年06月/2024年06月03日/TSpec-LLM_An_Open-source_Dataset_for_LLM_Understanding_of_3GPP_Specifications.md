# TSpec-LLM：一款开源数据集，专为大型语言模型深入解读3GPP规范而设计

发布时间：2024年06月03日

`RAG

理由：这篇论文主要介绍了名为\textit{TSpec-LLM}的数据集，并探讨了如何通过检索增强生成（RAG）框架来提升大型语言模型（LLMs）在处理电信标准文档时的性能。论文的核心贡献在于数据集的创建和RAG框架的应用，这直接关联到RAG技术在LLM中的应用，而不是Agent、LLM应用或LLM理论。因此，将其归类为RAG是合适的。` `数据集`

> TSpec-LLM: An Open-source Dataset for LLM Understanding of 3GPP Specifications

# 摘要

> 理解电信标准需要深入研究3GPP等组织发布的大量技术文档，这一过程既耗时又费力。尽管大型语言模型（LLMs）能辅助处理这些庞大的知识库，但一个全面的数据集对其预训练和微调至关重要。本文介绍了\textit{TSpec-LLM}，一个覆盖1999至2023年间所有3GPP文档的开源综合数据集。为验证其效能，我们选取了代表性的3GPP文档样本，设计了相关技术问题，并测试了多种LLMs的初始性能。随后，我们引入了检索增强生成（RAG）框架，通过从\textit{TSpec-LLM}中提取相关上下文来提升LLMs的性能。结果表明，采用RAG框架后，GPT-3.5、Gemini 1.0 Pro和GPT-4的准确率分别提升至71%、75%和72%。

> Understanding telecom standards involves sorting through numerous technical documents, such as those produced by the 3rd Generation Partnership Project (3GPP), which is time-consuming and labor-intensive. While large language models (LLMs) can assist with the extensive 3GPP knowledge base, an inclusive dataset is crucial for their effective pre-training and fine-tuning. In this paper, we introduce \textit{TSpec-LLM}, an open-source comprehensive dataset covering all 3GPP documents from Release 8 to Release 19 (1999--2023). To evaluate its efficacy, we first select a representative sample of 3GPP documents, create corresponding technical questions, and assess the baseline performance of various LLMs. We then incorporate a retrieval-augmented generation (RAG) framework to enhance LLM capabilities by retrieving relevant context from the \textit{TSpec-LLM} dataset. Our evaluation shows that using a naive-RAG framework on \textit{TSpec-LLM} improves the accuracy of GPT-3.5, Gemini 1.0 Pro, and GPT-4 from 44\%, 46\%, and 51\% to 71\%, 75\%, and 72\%, respectively.

![TSpec-LLM：一款开源数据集，专为大型语言模型深入解读3GPP规范而设计](../../../paper_images/2406.01768/x1.png)

![TSpec-LLM：一款开源数据集，专为大型语言模型深入解读3GPP规范而设计](../../../paper_images/2406.01768/2024_05_30_RAG_sketch.jpg)

![TSpec-LLM：一款开源数据集，专为大型语言模型深入解读3GPP规范而设计](../../../paper_images/2406.01768/x2.png)

![TSpec-LLM：一款开源数据集，专为大型语言模型深入解读3GPP规范而设计](../../../paper_images/2406.01768/x3.png)

![TSpec-LLM：一款开源数据集，专为大型语言模型深入解读3GPP规范而设计](../../../paper_images/2406.01768/x4.png)

![TSpec-LLM：一款开源数据集，专为大型语言模型深入解读3GPP规范而设计](../../../paper_images/2406.01768/2024_05_29_data_vis.jpg)

![TSpec-LLM：一款开源数据集，专为大型语言模型深入解读3GPP规范而设计](../../../paper_images/2406.01768/2024_05_30_eqn_vis.jpg)

![TSpec-LLM：一款开源数据集，专为大型语言模型深入解读3GPP规范而设计](../../../paper_images/2406.01768/2024_05_30_eqn_vis_TSpec.jpg)

[Arxiv](https://arxiv.org/abs/2406.01768)