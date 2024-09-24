# 通过大型语言模型与位置信息，提升旅游领域基于方面的情感分析效果。

发布时间：2024年09月23日

`LLM应用` `旅游业` `情感分析`

> Enhancing Aspect-based Sentiment Analysis in Tourism Using Large Language Models and Positional Information

# 摘要

> 在旅游业中，基于方面的情感分析 (ABSA) 对于理解游客对景点特定方面的评价至关重要，有助于推动行业创新和发展。然而，传统模型存在错误传播和情感元素提取不完整的问题。为此，本文提出了 ACOS_LLM 模型，用于方面-类别-观点-情感四元组提取 (ACOSQE)。该模型通过 Adalora 微调大型语言模型生成高质量辅助知识，并利用 Sparsegpt 压缩模型至 50% 稀疏度，以提高效率。实验结果显示，该模型在旅游数据集上的 F1 值比其他模型提高了 7.49%，在 Rest15 和 Rest16 数据集上的 F1 值分别提高了 0.05% 和 1.06%。

> Aspect-Based Sentiment Analysis (ABSA) in tourism plays a significant role in understanding tourists' evaluations of specific aspects of attractions, which is crucial for driving innovation and development in the tourism industry. However, traditional pipeline models are afflicted by issues such as error propagation and incomplete extraction of sentiment elements. To alleviate this issue, this paper proposes an aspect-based sentiment analysis model, ACOS_LLM, for Aspect-Category-Opinion-Sentiment Quadruple Extraction (ACOSQE). The model comprises two key stages: auxiliary knowledge generation and ACOSQE. Firstly, Adalora is used to fine-tune large language models for generating high-quality auxiliary knowledge. To enhance model efficiency, Sparsegpt is utilized to compress the fine-tuned model to 50% sparsity. Subsequently, Positional information and sequence modeling are employed to achieve the ACOSQE task, with auxiliary knowledge and the original text as inputs. Experiments are conducted on both self-created tourism datasets and publicly available datasets, Rest15 and Rest16. Results demonstrate the model's superior performance, with an F1 improvement of 7.49% compared to other models on the tourism dataset. Additionally, there is an F1 improvement of 0.05% and 1.06% on the Rest15 and Rest16 datasets, respectively.

[Arxiv](https://arxiv.org/abs/2409.14997)