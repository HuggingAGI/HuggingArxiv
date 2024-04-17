# 本研究旨在通过持续预训练的方法，打造一款专门针对金融领域的日语大型语言模型。

发布时间：2024年04月16日

`LLM应用`

> Construction of Domain-specified Japanese Large Language Model for Finance through Continual Pre-training

# 摘要

> 大型语言模型（LLMs）如今在金融等众多领域大放异彩。不过，专门针对日本金融领域的LLM尚未问世。本研究致力于通过持续预训练打造一款日本金融定制版LLM。在模型调优前，我们创建了专注于日本金融领域的数据集，以便进行持续预训练。选用了一款在10亿参数级别的日语LLM作为基础模型，该模型在日本金融基准测试中表现卓越。经过数据集和基础模型的持续预训练，调优后的模型在日本金融基准测试上超越了原版模型。而且，输出对比结果显示，调优模型的答案在质量和长度上往往更佳。这一成果证实了领域定制的持续预训练对LLMs同样适用。目前，该调优模型已在Hugging Face平台对外开放。

> Large language models (LLMs) are now widely used in various fields, including finance. However, Japanese financial-specific LLMs have not been proposed yet. Hence, this study aims to construct a Japanese financial-specific LLM through continual pre-training. Before tuning, we constructed Japanese financial-focused datasets for continual pre-training. As a base model, we employed a Japanese LLM that achieved state-of-the-art performance on Japanese financial benchmarks among the 10-billion-class parameter models. After continual pre-training using the datasets and the base model, the tuned model performed better than the original model on the Japanese financial benchmarks. Moreover, the outputs comparison results reveal that the tuned model's outputs tend to be better than the original model's outputs in terms of the quality and length of the answers. These findings indicate that domain-specific continual pre-training is also effective for LLMs. The tuned model is publicly available on Hugging Face.

[Arxiv](https://arxiv.org/abs/2404.10555)