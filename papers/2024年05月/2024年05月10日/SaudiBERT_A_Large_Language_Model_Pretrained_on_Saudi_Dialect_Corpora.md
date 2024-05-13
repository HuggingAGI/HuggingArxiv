# 沙特方言之光：SaudiBERT——专为沙特语境定制的大型预训练语言模型

发布时间：2024年05月10日

`Agent

这篇论文介绍了一个专门针对沙特方言预训练的阿拉伯语言模型SaudiBERT，并通过实验展示了其在特定任务上的优越性能。这个模型可以被视为一个智能代理（Agent），因为它被设计来处理特定的语言任务，并且在这些任务上表现出了高效率和效果。此外，论文还提到了为模型预训练提供支持的两个大型语料库，这进一步强调了模型作为处理特定语言任务的智能代理的角色。因此，这篇论文更适合归类在Agent分类下。` `语言模型`

> SaudiBERT: A Large Language Model Pretrained on Saudi Dialect Corpora

# 摘要

> 本文介绍了专为沙特方言预训练的阿拉伯语言模型SaudiBERT，并通过与六个多方言模型的比较，在情感分析和文本分类的11个数据集上展示了其卓越性能。SaudiBERT分别以86.15%和87.86%的平均F1分数领先，显著超越了其他模型。同时，我们还推出了两个庞大的沙特方言语料库：包含1.41亿条推文的STMC和15.2GB文本的SFC，它们均为SaudiBERT的预训练提供了支持，并创下了文献中沙特方言语料库的规模之最。实验结果表明，SaudiBERT在处理沙特方言文本方面表现出色，多数任务中均达到或超越了现有模型的性能。该模型现已公开，可在\url{https://huggingface.co/faisalq/SaudiBERT}获取。

> In this paper, we introduce SaudiBERT, a monodialect Arabic language model pretrained exclusively on Saudi dialectal text. To demonstrate the model's effectiveness, we compared SaudiBERT with six different multidialect Arabic language models across 11 evaluation datasets, which are divided into two groups: sentiment analysis and text classification. SaudiBERT achieved average F1-scores of 86.15\% and 87.86\% in these groups respectively, significantly outperforming all other comparative models. Additionally, we present two novel Saudi dialectal corpora: the Saudi Tweets Mega Corpus (STMC), which contains over 141 million tweets in Saudi dialect, and the Saudi Forums Corpus (SFC), which includes 15.2 GB of text collected from five Saudi online forums. Both corpora are used in pretraining the proposed model, and they are the largest Saudi dialectal corpora ever reported in the literature. The results confirm the effectiveness of SaudiBERT in understanding and analyzing Arabic text expressed in Saudi dialect, achieving state-of-the-art results in most tasks and surpassing other language models included in the study. SaudiBERT model is publicly available on \url{https://huggingface.co/faisalq/SaudiBERT}.

[Arxiv](https://arxiv.org/abs/2405.06239)