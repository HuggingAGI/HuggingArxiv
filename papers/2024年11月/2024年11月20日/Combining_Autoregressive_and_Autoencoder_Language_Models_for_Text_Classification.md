# 将自回归和自动编码器语言模型相结合以用于文本分类

发布时间：2024年11月20日

`LLM应用` `社会科学` `内容分析`

> Combining Autoregressive and Autoencoder Language Models for Text Classification

# 摘要

> 这篇论文呈现了 CAALM-TC（将自回归和自编码器语言模型相结合用于文本分类）这一创新方法，它通过融合自回归和自编码器语言模型来提升文本分类效果。诸如 Open AI 的 GPT、Meta 的 Llama 以及微软的 Phi 等自回归大型语言模型为内容分析从业者带来了良好前景，然而在文本分类上，它们通常逊于基于监督的 BERT 模型。CAALM 借助自回归模型依据输入文本生成上下文信息，接着将其与原始文本结合并输入自编码器模型进行分类。这种混合方式充分发挥了自回归模型丰富的上下文知识和自编码器高效的分类能力。在四个基准数据集上的实验结果显示，CAALM 持续优于现有方法，尤其在数据集较小和分类目标更抽象的任务里。这些发现表明，CAALM 为社会科学研究中的自动内容分析提供了一种可扩展且高效的解决方案，极大地降低了样本量需求。

> This paper presents CAALM-TC (Combining Autoregressive and Autoencoder Language Models for Text Classification), a novel method that enhances text classification by integrating autoregressive and autoencoder language models. Autoregressive large language models such as Open AI's GPT, Meta's Llama or Microsoft's Phi offer promising prospects for content analysis practitioners, but they generally underperform supervised BERT based models for text classification. CAALM leverages autoregressive models to generate contextual information based on input texts, which is then combined with the original text and fed into an autoencoder model for classification. This hybrid approach capitalizes on the extensive contextual knowledge of autoregressive models and the efficient classification capabilities of autoencoders. Experimental results on four benchmark datasets demonstrate that CAALM consistently outperforms existing methods, particularly in tasks with smaller datasets and more abstract classification objectives. The findings indicate that CAALM offers a scalable and effective solution for automated content analysis in social science research that minimizes sample size requirements.

[Arxiv](https://arxiv.org/abs/2411.13282)