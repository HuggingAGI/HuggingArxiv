# 上下文序列可能性：提升自然语言生成的置信度评分

发布时间：2024年06月03日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）的置信度评估问题，并提出了一种新的评分方法——上下文化序列可能性（CSL）。该研究通过分析基础LLM的注意力值来为不同词元分配不同权重，从而提高预测序列的概率。这种方法的提出和验证，以及其在多个QA数据集和一系列LLMs中的应用，都是对LLM理论的深入研究和贡献。因此，这篇论文应归类于LLM理论。` `问答系统`

> Contextualized Sequence Likelihood: Enhanced Confidence Scores for Natural Language Generation

# 摘要

> 大型语言模型（LLMs）的兴起极大地提升了自然语言生成任务的技术水平。为了确保LLMs的可靠应用，准确评估其置信度至关重要。目前，最常用的置信度评分是生成序列的可能性，但这种方法混淆了语义和句法因素。例如，在问答任务中，正确答案的尴尬表达可能导致预测概率降低。此外，根据上下文，不同词元的权重应有所不同。本研究提出，通过利用基础LLM的注意力值为不同词元分配不同权重，来提升预测序列的概率。通过验证集，我们能够识别关键的注意力头，显著提高了序列概率置信度量度的可靠性。我们称这种新评分方法为上下文化序列可能性（CSL）。CSL不仅易于实施和快速计算，还具有通过特定任务提示进一步优化的潜力。在多个QA数据集和一系列LLMs中，CSL在预测生成质量方面，通过AUROC或AUARC测量，显示出比现有技术基线更高的可靠性。

> The advent of large language models (LLMs) has dramatically advanced the state-of-the-art in numerous natural language generation tasks. For LLMs to be applied reliably, it is essential to have an accurate measure of their confidence. Currently, the most commonly used confidence score function is the likelihood of the generated sequence, which, however, conflates semantic and syntactic components. For instance, in question-answering (QA) tasks, an awkward phrasing of the correct answer might result in a lower probability prediction. Additionally, different tokens should be weighted differently depending on the context. In this work, we propose enhancing the predicted sequence probability by assigning different weights to various tokens using attention values elicited from the base LLM. By employing a validation set, we can identify the relevant attention heads, thereby significantly improving the reliability of the vanilla sequence probability confidence measure. We refer to this new score as the Contextualized Sequence Likelihood (CSL). CSL is easy to implement, fast to compute, and offers considerable potential for further improvement with task-specific prompts. Across several QA datasets and a diverse array of LLMs, CSL has demonstrated significantly higher reliability than state-of-the-art baselines in predicting generation quality, as measured by the AUROC or AUARC.

![上下文序列可能性：提升自然语言生成的置信度评分](../../../paper_images/2406.01806/x1.png)

![上下文序列可能性：提升自然语言生成的置信度评分](../../../paper_images/2406.01806/x2.png)

![上下文序列可能性：提升自然语言生成的置信度评分](../../../paper_images/2406.01806/x3.png)

![上下文序列可能性：提升自然语言生成的置信度评分](../../../paper_images/2406.01806/x4.png)

![上下文序列可能性：提升自然语言生成的置信度评分](../../../paper_images/2406.01806/x5.png)

![上下文序列可能性：提升自然语言生成的置信度评分](../../../paper_images/2406.01806/x6.png)

[Arxiv](https://arxiv.org/abs/2406.01806)