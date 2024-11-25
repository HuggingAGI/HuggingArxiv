# TransformLLM：借助 LLM 转换的阅读理解文本以适应大型语言模型

发布时间：2024年10月28日

`LLM应用` `语言模型`

> TransformLLM: Adapting Large Language Models via LLM-Transformed Reading Comprehension Text

# 摘要

> 大型语言模型（LLMs）在高度专业化领域颇具前景，然而在准确性和成本方面仍存挑战。这些局限限制了现有模型在特定领域任务中的运用。尽管对预训练模型的微调成果可期，但此过程可能计算开销大，且需大量特定应用的数据集。在本项工作中，我们填补了这一空缺。我们研发了 Phi-2-Legal 和 Mistral-Legal-7B，这两款是专为法律应用打造的语言模型。它们基于 Phi-2 和 Mistral-7B-v0.1，并历经对超 5 亿个法律文本标记的持续预训练。我们的创新之法借助大型语言模型（LLMs）将原始训练数据转化为阅读理解文本，极大提升了在法律任务中的能力。我们的法律 LLMs 在法律基准测试中表现卓越，甚至胜过在更大数据集和更多资源下训练的模型。此项工作凸显了针对特定领域文本持续预训练的成效，同时利用经济的 LLMs 进行数据转换，使这些模型兼具领域专长和一般语言理解能力。虽然本工作以法律领域为测试实例，但我们的方法可拓展并应用于任何预训练数据集，在不同任务中实现显著提升。这些发现彰显了领域自适应预训练和阅读理解对于开发高效特定领域语言模型的潜力。

> Large Language Models (LLMs) have shown promise in highly-specialized domains, however challenges are still present in aspects of accuracy and costs. These limitations restrict the usage of existing models in domain-specific tasks. While fine-tuning pre-trained models have shown promising results, this process can be computationally expensive and require massive datasets of the specialized application in hand. In this work, we bridge that gap. We have developed Phi-2-Legal and Mistral-Legal-7B, which are language models specifically designed for legal applications. These models are based on Phi-2 and Mistral-7B-v0.1, and have gone through continued pre-training with over 500 million tokens of legal texts. Our innovative approach significantly improves capabilities in legal tasks by using Large Language Models (LLMs) to convert raw training data into reading comprehension text. Our legal LLMs have demonstrated superior performance in legal benchmarks, even outperforming models trained on much larger datasets with more resources. This work emphasizes the effectiveness of continued pre-training on domain-specific texts, while using affordable LLMs for data conversion, which gives these models domain expertise while retaining general language understanding capabilities. While this work uses the legal domain as a test case, our method can be scaled and applied to any pre-training dataset, resulting in significant improvements across different tasks. These findings underscore the potential of domain-adaptive pre-training and reading comprehension for the development of highly effective domain-specific language models.

[Arxiv](https://arxiv.org/abs/2410.21479)