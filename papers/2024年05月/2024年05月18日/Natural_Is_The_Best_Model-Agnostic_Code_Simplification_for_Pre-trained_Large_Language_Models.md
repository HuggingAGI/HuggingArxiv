# 自然至上：简化预训练大型语言模型的模型无关代码

发布时间：2024年05月18日

`LLM应用

理由：这篇论文主要讨论了针对大型语言模型（LLM）的代码简化方案SlimCode，该方案旨在减少LLM处理代码时的计算复杂度和成本。论文通过实证研究展示了SlimCode在代码搜索和摘要任务中的性能提升，并且讨论了其对模型无关性的影响。这些内容主要关注于LLM在实际应用中的优化和改进，因此属于LLM应用类别。` `软件开发` `人工智能`

> Natural Is The Best: Model-Agnostic Code Simplification for Pre-trained Large Language Models

# 摘要

> 预训练的大型语言模型（LLM）在多个领域取得了显著成就，但面向代码的LLMs计算复杂度高，且随输入长度呈二次增长。为了简化LLM的输入，现有技术通过LLM的注意力分数筛选代码令牌。然而，这种简化不应依赖于LLM的注意力模式，因为这些模式受模型架构和预训练数据集的影响，而这两者属于解决方案域，并非问题域。因此，当模型预训练数据集变化时，结果可能不同。我们提出的SlimCode是一种模型无关的代码简化方案，它根据输入代码令牌的特性进行操作。通过对CodeBERT、CodeT5和GPT-4等LLMs在代码搜索和摘要任务上的实证研究，我们发现：1) 代码令牌移除比例与训练时间节省比例呈线性关系；2) 分类令牌对代码简化的影响差异显著；3) 这种影响虽任务特定，但与模型无关；4) 这些发现适用于范式提示工程和交互式上下文学习。实证结果表明，SlimCode在代码搜索和摘要任务中，分别提高了9.46%和5.15%的MRR和BLEU分数，且速度比现有技术快133倍。此外，SlimCode在每次API查询中最多可减少24%的GPT-4调用成本，同时保持与原始代码相当的结果。

> Pre-trained Large Language Models (LLM) have achieved remarkable successes in several domains. However, code-oriented LLMs are heavy in computational complexity, and quadratically with the length of the input. Toward simplifying the input program of an LLM, the state-of-the-art approach has the strategies to filter the input code tokens based on the attention scores given by the LLM. The decision to simplify the input should not rely on the attention patterns of an LLM, as these patterns are influenced by both the model architecture and the pre-training dataset. Since the model and dataset are part of the solution domain, not the problem domain where the input belongs, the outcome may differ when the model is pre-trained on a different dataset. We propose SlimCode, a model-agnostic code simplification solution for LLMs that depends on the nature of input code tokens. As an empirical study on the LLMs including CodeBERT, CodeT5, and GPT-4 for two main tasks: code search and summarization, we reported that 1) the removal ratio of code has a linear-like relation with the saving ratio on training time, 2) the impact of categorized tokens on code simplification can vary significantly, 3) the impact of categorized tokens on code simplification is task-specific but model-agnostic, and 4) the above findings hold for the paradigm-prompt engineering and interactive in-context learning. The empirical results showed that SlimCode can improve the state-of-the-art technique by 9.46% and 5.15% in terms of MRR and BLEU score on code search and summarization. Moreover, SlimCode is 133 times faster than the state-of-the-art approach. Additionally, SlimCode can reduce the cost of invoking GPT-4 by up to 24% per API query, while still producing comparable results to those with the original code.

![自然至上：简化预训练大型语言模型的模型无关代码](../../../paper_images/2405.11196/x1.png)

![自然至上：简化预训练大型语言模型的模型无关代码](../../../paper_images/2405.11196/x2.png)

[Arxiv](https://arxiv.org/abs/2405.11196)