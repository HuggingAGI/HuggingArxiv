# 借助Prompt微调技术提升大型语言模型在挖掘健康社会决定因素时的泛化性能

发布时间：2024年03月18日

`LLM应用`

> Improving Generalizability of Extracting Social Determinants of Health Using Large Language Models through Prompt-tuning

> 得益于 LLMs 的推动，NLP 在解析临床叙事以提取患者信息方面取得显著进展。但依赖微调策略的传统方法在面对跨领域应用时，其迁移学习能力受限。一项新研究提出了创新方案，利用软提示引导的训练架构，让 LLMs 更精准地生成目标输出。研究针对仅编码器 GatorTron 和仅解码器 GatorTronGPT 两种 LLM 结构进行探索，并借助于2022年n2c2挑战赛提供的跨机构数据集及UF Health的跨疾病数据集，对其在提取健康的社会决定因素（SDoH）任务上的表现进行了评估。实验结果显示，在跨领域应用场景下，经过提示调整的仅解码器 LLMs 性能更为出色。其中，GatorTronGPT 在两组数据集中均斩获最高 F1 分值，分别比常规微调的 GatorTron 在跨机构场景下提升8.9%至21.8%，在跨疾病场景下提升5.5%至14.5%。

> The progress in natural language processing (NLP) using large language models (LLMs) has greatly improved patient information extraction from clinical narratives. However, most methods based on the fine-tuning strategy have limited transfer learning ability for cross-domain applications. This study proposed a novel approach that employs a soft prompt-based learning architecture, which introduces trainable prompts to guide LLMs toward desired outputs. We examined two types of LLM architectures, including encoder-only GatorTron and decoder-only GatorTronGPT, and evaluated their performance for the extraction of social determinants of health (SDoH) using a cross-institution dataset from the 2022 n2c2 challenge and a cross-disease dataset from the University of Florida (UF) Health. The results show that decoder-only LLMs with prompt tuning achieved better performance in cross-domain applications. GatorTronGPT achieved the best F1 scores for both datasets, outperforming traditional fine-tuned GatorTron by 8.9% and 21.8% in a cross-institution setting, and 5.5% and 14.5% in a cross-disease setting.

[Arxiv](https://arxiv.org/abs/2403.12374)