# BMRetriever：优化大型语言模型，提升其在生物医学文本检索方面的性能。

发布时间：2024年04月29日

`分类：LLM应用

这篇论文介绍了BMRetriever，这是一个针对生物医学检索任务的高效模型。它通过在大规模生物医学语料库上进行无监督预训练，并在标记数据集和合成样本的组合上进行指令微调，以提升生物医学检索性能。这表明了该研究在应用大型语言模型（LLM）于特定领域（生物医学检索）的应用上取得了显著成果。` `生物医学` `信息检索`

> BMRetriever: Tuning Large Language Models as Better Biomedical Text Retrievers

# 摘要

> 为了在知识密集型的生物医学任务中取得卓越表现，开发高效的生物医学检索模型至关重要，但这一任务因公开可用的生物医学数据标注不足和计算资源有限而充满挑战。我们介绍了 BMRetriever，这是一系列密集型检索器，通过在大规模生物医学语料库上进行无监督预训练，并在标记数据集和合成样本的组合上进行指令微调，以提升生物医学检索性能。在 11 个数据集上的 5 项生物医学任务的实验证实了 BMRetriever 在多样化应用中的高效性。BMRetriever 在参数效率上也表现出色，其 410M 版本性能超过基线模型达 11.7 倍，而 2B 版本则能与参数量超过 5B 的模型相媲美。为了确保透明度、可复现性以及促进新领域的应用，我们在 \url{https://huggingface.co/BMRetriever} 上公开了训练数据和模型检查点。

> Developing effective biomedical retrieval models is important for excelling at knowledge-intensive biomedical tasks but still challenging due to the deficiency of sufficient publicly annotated biomedical data and computational resources. We present BMRetriever, a series of dense retrievers for enhancing biomedical retrieval via unsupervised pre-training on large biomedical corpora, followed by instruction fine-tuning on a combination of labeled datasets and synthetic pairs. Experiments on 5 biomedical tasks across 11 datasets verify BMRetriever's efficacy on various biomedical applications. BMRetriever also exhibits strong parameter efficiency, with the 410M variant outperforming baselines up to 11.7 times larger, and the 2B variant matching the performance of models with over 5B parameters. The training data and model checkpoints are released at \url{https://huggingface.co/BMRetriever} to ensure transparency, reproducibility, and application to new domains.

[Arxiv](https://arxiv.org/abs/2404.18443)