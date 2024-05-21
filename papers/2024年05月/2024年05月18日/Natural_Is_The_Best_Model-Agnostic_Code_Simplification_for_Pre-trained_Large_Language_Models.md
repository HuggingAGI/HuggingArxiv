# 自然至上：简化预训练大型语言模型的模型无关代码

发布时间：2024年05月18日

`LLM应用

理由：这篇论文主要讨论了针对大型语言模型（LLM）在代码处理方面的优化方法，特别是提出了SlimCode这一独立于模型的代码简化方案。论文通过实证研究展示了SlimCode在代码搜索和摘要任务上的性能提升，并且降低了计算成本。这些内容主要关注于LLM的实际应用层面，即如何更有效地使用LLM处理特定任务（如代码搜索和摘要），因此归类为LLM应用。` `软件开发` `人工智能`

> Natural Is The Best: Model-Agnostic Code Simplification for Pre-trained Large Language Models

# 摘要

> 预训练的大型语言模型（LLM）在多个领域取得了显著成就，但面向代码的LLMs计算复杂度高，且随输入长度呈二次增长。为了简化LLM的输入，现有技术依据LLM的注意力分数筛选代码令牌。然而，这种简化策略不应仅依赖于LLM的注意力模式，因为这些模式受模型结构和预训练数据集的双重影响。由于模型和数据集属于解决方案域，而非输入所在的问题域，不同数据集预训练的模型可能产生不同结果。为此，我们提出了SlimCode，一种独立于模型的代码简化方案，它根据输入代码令牌的特性进行操作。通过对CodeBERT、CodeT5和GPT-4等LLM在代码搜索和摘要任务上的实证研究，我们发现：1) 代码令牌的移除比例与训练时间的节省比例呈线性关系，2) 分类令牌对代码简化的影响差异显著，3) 这种影响虽任务特定，但与模型无关，4) 这些发现同样适用于范式提示工程和交互式情境学习。实证结果显示，SlimCode在代码搜索和摘要任务上，分别将最先进技术的MRR和BLEU分数提高了9.46%和5.15%，且速度提升了133倍。此外，SlimCode还能在每个API查询中将调用GPT-4的成本降低高达24%，同时保持与原始代码相当的结果。

> Pre-trained Large Language Models (LLM) have achieved remarkable successes in several domains. However, code-oriented LLMs are heavy in computational complexity, and quadratically with the length of the input. Toward simplifying the input program of an LLM, the state-of-the-art approach has the strategies to filter the input code tokens based on the attention scores given by the LLM. The decision to simplify the input should not rely on the attention patterns of an LLM, as these patterns are influenced by both the model architecture and the pre-training dataset. Since the model and dataset are part of the solution domain, not the problem domain where the input belongs, the outcome may differ when the model is pre-trained on a different dataset. We propose SlimCode, a model-agnostic code simplification solution for LLMs that depends on the nature of input code tokens. As an empirical study on the LLMs including CodeBERT, CodeT5, and GPT-4 for two main tasks: code search and summarization, we reported that 1) the removal ratio of code has a linear-like relation with the saving ratio on training time, 2) the impact of categorized tokens on code simplification can vary significantly, 3) the impact of categorized tokens on code simplification is task-specific but model-agnostic, and 4) the above findings hold for the paradigm-prompt engineering and interactive in-context learning. The empirical results showed that SlimCode can improve the state-of-the-art technique by 9.46% and 5.15% in terms of MRR and BLEU score on code search and summarization. Moreover, SlimCode is 133 times faster than the state-of-the-art approach. Additionally, SlimCode can reduce the cost of invoking GPT-4 by up to 24% per API query, while still producing comparable results to those with the original code.

![自然至上：简化预训练大型语言模型的模型无关代码](../../../paper_images/2405.11196/x1.png)

![自然至上：简化预训练大型语言模型的模型无关代码](../../../paper_images/2405.11196/x2.png)

[Arxiv](https://arxiv.org/abs/2405.11196)