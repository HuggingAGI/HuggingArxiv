# FFN：精细划分的中英金融领域平行语料库

发布时间：2024年06月26日

`LLM应用

这篇论文聚焦于大型语言模型（LLMs）在金融领域机器翻译的应用。通过构建和评估一个特定的中英文金融新闻平行语料库，研究者们探讨了LLMs如ChatGPT和ERNIE-bot在金融翻译中的表现，并与传统机器翻译模型进行了比较。这种研究直接关联到LLMs在特定行业（金融）的实际应用，因此属于LLM应用分类。` `机器翻译`

> FFN: a Fine-grained Chinese-English Financial Domain Parallel Corpus

# 摘要

> 大型语言模型（LLMs）在机器翻译领域取得了显著进步，但在金融领域的应用仍是一片未被充分探索的领域。为此，我们精心构建了名为FFN的中英文金融新闻平行语料库，涵盖了2014年至2023年间来自CNN、FOX和中国日报等主流媒体的文章。通过人工校正，我们确保了1013篇正文和809个标题的质量。我们采用BLEU、TER和chrF等指标，评估了ChatGPT和ERNIE-bot的翻译表现，并与基于我们数据集训练的OpenNMT模型进行了对比。我们的研究不仅揭示了LLMs在金融翻译中的挑战，还提供了深入的分析，旨在推动这一领域的进一步研究和改进。我们强调，为了确保金融翻译的准确性和质量，优化LLMs在特定领域的应用至关重要。

> Large Language Models (LLMs) have stunningly advanced the field of machine translation, though their effectiveness within the financial domain remains largely underexplored. To probe this issue, we constructed a fine-grained Chinese-English parallel corpus of financial news called FFN. We acquired financial news articles spanning between January 1st, 2014, to December 31, 2023, from mainstream media websites such as CNN, FOX, and China Daily. The dataset consists of 1,013 main text and 809 titles, all of which have been manually corrected. We measured the translation quality of two LLMs -- ChatGPT and ERNIE-bot, utilizing BLEU, TER and chrF scores as the evaluation metrics. For comparison, we also trained an OpenNMT model based on our dataset. We detail problems of LLMs and provide in-depth analysis, intending to stimulate further research and solutions in this largely uncharted territory. Our research underlines the need to optimize LLMs within the specific field of financial translation to ensure accuracy and quality.

[Arxiv](https://arxiv.org/abs/2406.18856)