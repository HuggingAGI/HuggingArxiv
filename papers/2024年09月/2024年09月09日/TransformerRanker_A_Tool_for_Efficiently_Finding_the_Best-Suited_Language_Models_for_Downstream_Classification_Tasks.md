# TransformerRanker：一款高效工具，专为寻找最适合下游分类任务的语言模型而设计。

发布时间：2024年09月09日

`LLM应用` `机器学习`

> TransformerRanker: A Tool for Efficiently Finding the Best-Suited Language Models for Downstream Classification Tasks

# 摘要

> 在 NLP 分类任务中，通常选择预训练模型并进行微调。然而，面对众多可用的 PLM，如何挑选最适合特定任务的模型成为一大挑战。为此，我们推出了 TransformerRanker，一个无需昂贵微调即可高效排序 PLM 的轻量级库。它集成了最新的迁移性评估方法（如 LogME、H-Score、kNN）和层聚合技术，实证显示能生成顶尖的 PLM 排名。设计简洁易用，用户可直接接入 HuggingFace 库，只需指定任务和模型列表，即可获得最佳候选模型排名。TransformerRanker 现已作为开源库发布，可通过 pip 安装，地址见 https://github.com/flairNLP/transformer-ranker。

> Classification tasks in NLP are typically addressed by selecting a pre-trained language model (PLM) from a model hub, and fine-tuning it for the task at hand. However, given the very large number of PLMs that are currently available, a practical challenge is to determine which of them will perform best for a specific downstream task. With this paper, we introduce TransformerRanker, a lightweight library that efficiently ranks PLMs for classification tasks without the need for computationally costly fine-tuning. Our library implements current approaches for transferability estimation (LogME, H-Score, kNN), in combination with layer aggregation options, which we empirically showed to yield state-of-the-art rankings of PLMs (Garbas et al., 2024). We designed the interface to be lightweight and easy to use, allowing users to directly connect to the HuggingFace Transformers and Dataset libraries. Users need only select a downstream classification task and a list of PLMs to create a ranking of likely best-suited PLMs for their task. We make TransformerRanker available as a pip-installable open-source library https://github.com/flairNLP/transformer-ranker.

[Arxiv](https://arxiv.org/abs/2409.05997)