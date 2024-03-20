# 通过优化提示调优，我们致力于提升大型语言模型在挖掘健康社会决定因素时的泛化性能，以期在各类情境下更为准确、稳定地识别与健康相关的社会因素。

发布时间：2024年03月18日

`LLM应用`

> Improving Generalizability of Extracting Social Determinants of Health Using Large Language Models through Prompt-tuning

> 得益于LLMs的助力，NLP技术在从临床记录中抽提患者信息方面取得了显著进步。但多数依赖微调策略的方法在应对跨领域问题时，迁移学习能力显得不足。本次研究创新性地运用了一种基于软提示的学习框架，借助可训练的提示巧妙指引LLMs以生成理想输出。我们对两类LLM结构——仅包含编码器的GatorTron和仅含解码器的GatorTronGPT进行了探究，并通过2022年n2c2挑战赛的跨机构数据集及UF健康学院的跨疾病数据集，评估了它们在抽取SDoH指标上的表现。实验结果显示，在跨领域应用场景下，配合提示调优的仅解码器LLMs展现出更卓越的表现。其中，GatorTronGPT在两个数据集上都赢得了最高的F1得分，与传统微调型GatorTron相比，在跨机构测试中分别提升了8.9%至21.8%，在跨疾病场景下则分别提升了5.5%至14.5%。

> The progress in natural language processing (NLP) using large language models (LLMs) has greatly improved patient information extraction from clinical narratives. However, most methods based on the fine-tuning strategy have limited transfer learning ability for cross-domain applications. This study proposed a novel approach that employs a soft prompt-based learning architecture, which introduces trainable prompts to guide LLMs toward desired outputs. We examined two types of LLM architectures, including encoder-only GatorTron and decoder-only GatorTronGPT, and evaluated their performance for the extraction of social determinants of health (SDoH) using a cross-institution dataset from the 2022 n2c2 challenge and a cross-disease dataset from the University of Florida (UF) Health. The results show that decoder-only LLMs with prompt tuning achieved better performance in cross-domain applications. GatorTronGPT achieved the best F1 scores for both datasets, outperforming traditional fine-tuned GatorTron by 8.9% and 21.8% in a cross-institution setting, and 5.5% and 14.5% in a cross-disease setting.

[Arxiv](https://arxiv.org/abs/2403.12374)