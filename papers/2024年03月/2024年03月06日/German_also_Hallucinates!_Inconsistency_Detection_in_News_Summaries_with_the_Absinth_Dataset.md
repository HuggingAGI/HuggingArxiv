# [德语文本亦会“幻想”！利用Absinth数据集揭示新闻摘要中的不一致性问题](https://arxiv.org/abs/2403.03750)

发布时间：2024年03月06日

`LLM应用`

> German also Hallucinates! Inconsistency Detection in News Summaries with the Absinth Dataset

> 随着LLMs的兴起，各类自然语言处理任务都取得了显著进展。然而，在输出中产生臆想信息的问题依然困扰着大型模型，尤其在自动文本摘要领域，保证生成摘要忠实于原文是至关重要的。之前的研究针对此问题，通过检测输出中的臆想（即不一致性）来评估摘要的真实度，但大多聚焦于英语，而对德语数据的支持不足。本研究介绍了名为absinth的手动标注德语新闻摘要臆想检测数据集，并在微调及上下文学习环境下检验了最新开源LLMs对此任务的处理能力。为了促进德语文本臆想检测领域的深入研究，我们决定开源并发布absinth数据集。

> The advent of Large Language Models (LLMs) has led to remarkable progress on a wide range of natural language processing tasks. Despite the advances, these large-sized models still suffer from hallucinating information in their output, which poses a major issue in automatic text summarization, as we must guarantee that the generated summary is consistent with the content of the source document. Previous research addresses the challenging task of detecting hallucinations in the output (i.e. inconsistency detection) in order to evaluate the faithfulness of the generated summaries. However, these works primarily focus on English and recent multilingual approaches lack German data. This work presents absinth, a manually annotated dataset for hallucination detection in German news summarization and explores the capabilities of novel open-source LLMs on this task in both fine-tuning and in-context learning settings. We open-source and release the absinth dataset to foster further research on hallucination detection in German.