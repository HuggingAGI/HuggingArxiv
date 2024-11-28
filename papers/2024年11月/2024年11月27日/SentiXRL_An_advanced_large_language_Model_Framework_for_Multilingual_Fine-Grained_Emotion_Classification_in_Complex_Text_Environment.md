# SentiXRL：一个用于复杂文本环境中多语言细粒度情感分类的先进大型语言模型框架

发布时间：2024年11月27日

`LLM应用` `情感分析`

> SentiXRL: An advanced large language Model Framework for Multilingual Fine-Grained Emotion Classification in Complex Text Environment

# 摘要

> 大型语言模型（LLMs）的表达能力强大，生成模型能有效捕捉情感结构和深层语义，不过在多语言及复杂语境下的细粒度情感分类方面仍存挑战。为此，我们提出了情感跨语言识别和逻辑框架（SentiXRL），它涵盖两个模块，一是情感检索增强模块，借助历史对话和逻辑推理提升复杂语境下的情感分类准确率；二是自循环分析协商机制（SANM），利于单个模型内自主决策以完成分类任务。我们已在多个标准数据集上证实了 SentiXRL 的优势，其在 CPED 和 CH-SIMS 上的表现优于现有模型，在 MELD、Emorynlp 和 IEMOCAP 上的整体性能也更出色。尤为值得一提的是，我们统一了若干细粒度情感标注数据集的标签，并开展了类别混淆实验，揭示了标准数据集中类别不平衡带来的挑战和影响。

> With strong expressive capabilities in Large Language Models(LLMs), generative models effectively capture sentiment structures and deep semantics, however, challenges remain in fine-grained sentiment classification across multi-lingual and complex contexts. To address this, we propose the Sentiment Cross-Lingual Recognition and Logic Framework (SentiXRL), which incorporates two modules,an emotion retrieval enhancement module to improve sentiment classification accuracy in complex contexts through historical dialogue and logical reasoning,and a self-circulating analysis negotiation mechanism (SANM)to facilitates autonomous decision-making within a single model for classification tasks.We have validated SentiXRL's superiority on multiple standard datasets, outperforming existing models on CPED and CH-SIMS,and achieving overall better performance on MELD,Emorynlp and IEMOCAP. Notably, we unified labels across several fine-grained sentiment annotation datasets and conducted category confusion experiments, revealing challenges and impacts of class imbalance in standard datasets.

[Arxiv](https://arxiv.org/abs/2411.18162)