# 大型语言模型偏爱形式性：解析其在冲突知识数据上的学习倾向

发布时间：2024年10月07日

`LLM理论` `人工智能`

> Formality is Favored: Unraveling the Learning Preferences of Large Language Models on Data with Conflicting Knowledge

# 摘要

> 大型语言模型在海量预训练数据上训练，表现出色，但这些数据常含误导或矛盾信息。我们研究了 LLM 如何处理这些噪声数据，发现它们像人类一样，偏好正式、拼写错误少的文本，从而在冲突中更快学习。这一发现适用于不同模型和语言，尤其在大型模型中更为显著。深入分析显示，LLM 更信任与多数数据一致的特征，且通过调整一致性，可改变其偏好。

> Having been trained on massive pretraining data, large language models have shown excellent performance on many knowledge-intensive tasks. However, pretraining data tends to contain misleading and even conflicting information, and it is intriguing to understand how LLMs handle these noisy data during training. In this study, we systematically analyze LLMs' learning preferences for data with conflicting knowledge. We find that pretrained LLMs establish learning preferences similar to humans, i.e., preferences towards formal texts and texts with fewer spelling errors, resulting in faster learning and more favorable treatment of knowledge in data with such features when facing conflicts. This finding is generalizable across models and languages and is more evident in larger models. An in-depth analysis reveals that LLMs tend to trust data with features that signify consistency with the majority of data, and it is possible to instill new preferences and erase old ones by manipulating the degree of consistency with the majority data.

[Arxiv](https://arxiv.org/abs/2410.04784)