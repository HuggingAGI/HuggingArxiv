# 为元分析赋能：借助大型语言模型实现科学综合

发布时间：2024年11月16日

`LLM应用` `科学研究` `文献分析`

> Empowering Meta-Analysis: Leveraging Large Language Models for Scientific Synthesis

# 摘要

> 本研究探讨了利用大型语言模型（LLMs）实现科学文献中元分析的自动化。元分析是一种强有力的统计手段，能综合多篇研究支持文章的成果，从而达成全面的理解。我们清楚，元文章会对多篇文章展开结构化分析。但人工进行元分析不仅费力、耗时，还易出现人为差错，这凸显出对自动化流程以简化过程的迫切需求。我们的研究引入了全新的方法，即在大量科学数据集上对LLM进行微调，以应对大数据处理和结构化数据提取方面的挑战。我们通过整合检索增强生成（RAG）来实现元分析过程的自动化和优化。借助提示工程以及专为在大型上下文数据集中微调而设计的新损失指标——反余弦距离（ICD），LLMs能够高效生成结构化的元分析内容。随后，人类评估会评估相关性，并提供关键指标中模型性能的相关信息。本研究表明，微调模型优于未微调模型，微调后的LLMs生成的元分析摘要相关度达87.6%。基于人类评估的上下文相关性显示，不相关度从4.56%降至1.9%。这些实验在低资源环境中开展，突显了该研究对提升元分析自动化效率和可靠性的贡献。

> This study investigates the automation of meta-analysis in scientific documents using large language models (LLMs). Meta-analysis is a robust statistical method that synthesizes the findings of multiple studies support articles to provide a comprehensive understanding. We know that a meta-article provides a structured analysis of several articles. However, conducting meta-analysis by hand is labor-intensive, time-consuming, and susceptible to human error, highlighting the need for automated pipelines to streamline the process. Our research introduces a novel approach that fine-tunes the LLM on extensive scientific datasets to address challenges in big data handling and structured data extraction. We automate and optimize the meta-analysis process by integrating Retrieval Augmented Generation (RAG). Tailored through prompt engineering and a new loss metric, Inverse Cosine Distance (ICD), designed for fine-tuning on large contextual datasets, LLMs efficiently generate structured meta-analysis content. Human evaluation then assesses relevance and provides information on model performance in key metrics. This research demonstrates that fine-tuned models outperform non-fine-tuned models, with fine-tuned LLMs generating 87.6% relevant meta-analysis abstracts. The relevance of the context, based on human evaluation, shows a reduction in irrelevancy from 4.56% to 1.9%. These experiments were conducted in a low-resource environment, highlighting the study's contribution to enhancing the efficiency and reliability of meta-analysis automation.

[Arxiv](https://arxiv.org/abs/2411.10878)