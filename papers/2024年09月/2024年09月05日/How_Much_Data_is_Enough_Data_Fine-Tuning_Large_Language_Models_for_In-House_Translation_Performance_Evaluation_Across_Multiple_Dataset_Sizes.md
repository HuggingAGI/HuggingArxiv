# 多少数据才算足够？本文探讨了为内部翻译任务微调大型语言模型时，不同数据集大小对性能的影响。

发布时间：2024年09月05日

`LLM应用` `软件行业`

> How Much Data is Enough Data? Fine-Tuning Large Language Models for In-House Translation: Performance Evaluation Across Multiple Dataset Sizes

# 摘要

> 仅解码器的 LLM 在 MT 中表现优异，但处理特定组织翻译的细微差别时却力不从心。本研究探索了微调 Llama 3 8B Instruct 结合翻译记忆 (TMs) 以提升翻译准确性和效率的效果。我们使用软件行业特定组织的 TMs 微调 Llama 3 模型，实验涵盖五种语言的翻译方向。通过分析不同大小的训练数据集（1k 到 207k 片段），我们发现数据集越大，翻译质量提升越显著。平均而言，最大训练集的 BLEU 和 COMET 分数分别提高了 13 和 25 分。尽管在仅微调 1k 和 2k 示例时性能有所下降，但随着数据集增大，改进显著。研究显示，结合 TMs 与 LLM 可定制满足企业特定需求的翻译模型，提升翻译质量和效率。这一方法为寻求优化翻译成果的组织提供了宝贵参考，特别是在特定领域。

> Decoder-only LLMs have shown impressive performance in MT due to their ability to learn from extensive datasets and generate high-quality translations. However, LLMs often struggle with the nuances and style required for organisation-specific translation. In this study, we explore the effectiveness of fine-tuning Large Language Models (LLMs), particularly Llama 3 8B Instruct, leveraging translation memories (TMs), as a valuable resource to enhance accuracy and efficiency. We investigate the impact of fine-tuning the Llama 3 model using TMs from a specific organisation in the software sector. Our experiments cover five translation directions across languages of varying resource levels (English to Brazilian Portuguese, Czech, German, Finnish, and Korean). We analyse diverse sizes of training datasets (1k to 207k segments) to evaluate their influence on translation quality. We fine-tune separate models for each training set and evaluate their performance based on automatic metrics, BLEU, chrF++, TER, and COMET. Our findings reveal improvement in translation performance with larger datasets across all metrics. On average, BLEU and COMET scores increase by 13 and 25 points, respectively, on the largest training set against the baseline model. Notably, there is a performance deterioration in comparison with the baseline model when fine-tuning on only 1k and 2k examples; however, we observe a substantial improvement as the training dataset size increases. The study highlights the potential of integrating TMs with LLMs to create bespoke translation models tailored to the specific needs of businesses, thus enhancing translation quality and reducing turn-around times. This approach offers a valuable insight for organisations seeking to leverage TMs and LLMs for optimal translation outcomes, especially in narrower domains.

[Arxiv](https://arxiv.org/abs/2409.03454)