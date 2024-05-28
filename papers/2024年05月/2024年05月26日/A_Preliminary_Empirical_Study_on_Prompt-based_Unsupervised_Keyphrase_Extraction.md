# 基于提示的无监督关键词提取：一项初步实证研究

发布时间：2024年05月26日

`LLM理论

理由：这篇论文主要探讨了预训练大型语言模型在关键词提取任务中对不同提示的响应和效果，这涉及到模型对输入提示的理解和处理机制，属于对大型语言模型理论层面的研究。虽然实验部分涉及具体应用（关键词提取），但核心关注点在于提示设计对模型性能的影响，这是对LLM理论的深入探讨。` `关键词提取`

> A Preliminary Empirical Study on Prompt-based Unsupervised Keyphrase Extraction

# 摘要

> 预训练的大型语言模型依赖人类设计的提示来执行自然语言处理任务，但提示设计常需繁琐的“提示工程”，依赖人工试错和专业介入。在关键词提取任务中，我们探讨了不同提示的有效性，并发现：(1) 复杂提示未必优于简单提示；(2) 提示中个别关键词的变动能影响整体效果；(3) 面对长文档，复杂提示表现更佳。实验涵盖了六个数据集和多种模型，验证了这些发现。

> Pre-trained large language models can perform natural language processing downstream tasks by conditioning on human-designed prompts. However, a prompt-based approach often requires "prompt engineering" to design different prompts, primarily hand-crafted through laborious trial and error, requiring human intervention and expertise. It is a challenging problem when constructing a prompt-based keyphrase extraction method. Therefore, we investigate and study the effectiveness of different prompts on the keyphrase extraction task to verify the impact of the cherry-picked prompts on the performance of extracting keyphrases. Extensive experimental results on six benchmark keyphrase extraction datasets and different pre-trained large language models demonstrate that (1) designing complex prompts may not necessarily be more effective than designing simple prompts; (2) individual keyword changes in the designed prompts can affect the overall performance; (3) designing complex prompts achieve better performance than designing simple prompts when facing long documents.

![基于提示的无监督关键词提取：一项初步实证研究](../../../paper_images/2405.16571/x1.png)

[Arxiv](https://arxiv.org/abs/2405.16571)