# IntGrad MT：借助句子插值与逐步机器翻译，激发 LLM 的翻译潜能

发布时间：2024年10月15日

`LLM应用` `低资源语言`

> IntGrad MT: Eliciting LLMs' Machine Translation Capabilities with Sentence Interpolation and Gradual MT

# 摘要

> 最近的大型语言模型 (LLM) 在无需额外微调的情况下，翻译表现出色。然而，在低资源语言对上，其表现仍显不足。以往的研究通过利用少样本示例或外部资源（如词典、语法书）来缓解这一问题，但模型因此过度依赖这些非参数信息源。本文提出了一种名为 IntGrad MT 的新方法，旨在充分挖掘 LLM 的固有翻译能力。IntGrad MT 通过构建难度递增的少样本示例链，每个示例包含源句子和模型自身的翻译。该方法结合了句子插值和渐进式 MT 两种技术，前者生成从易到难的句子序列，后者则利用早期翻译作为后续翻译的少样本示例。实验结果显示，这种方法显著提升了多种语言的 xCOMET 分数，特别是在低资源语言如印地语、斯瓦希里语、孟加拉语和马拉地语上。IntGrad MT 提供了一种无需额外训练即可提升 LLM 翻译性能的实用方案。

> Recent Large Language Models (LLMs) have demonstrated strong performance in translation without needing to be finetuned on additional parallel corpora. However, they still underperform for low-resource language pairs. Previous works have focused on mitigating this issue by leveraging relevant few-shot examples or external resources such as dictionaries or grammar books, making models heavily reliant on these nonparametric sources of information. In this paper, we propose a novel method named IntGrad MT that focuses on fully exploiting an LLM's inherent translation capability. IntGrad MT achieves this by constructing a chain of few-shot examples, each consisting of a source sentence and the model's own translation, that rise incrementally in difficulty. IntGrad MT employs two techniques: Sentence Interpolation, which generates a sequence of sentences that gradually change from an easy sentence to translate to a difficult one, and Gradual MT, which sequentially translates this chain using translations of earlier sentences as few-shot examples for the translation of subsequent ones. With this approach, we observe a substantial enhancement in the xCOMET scores of various LLMs for multiple languages, especially in low-resource languages such as Hindi(8.26), Swahili(7.10), Bengali(6.97) and Marathi(13.03). Our approach presents a practical way of enhancing LLMs' performance without extra training.

[Arxiv](https://arxiv.org/abs/2410.11693)