# LLM-Select：借助大型语言模型实现特征选择

发布时间：2024年07月02日

`LLM应用` `数据科学`

> LLM-Select: Feature Selection with Large Language Models

# 摘要

> 本研究揭示了大型语言模型（LLM）的一项惊人能力：仅凭输入特征名称和预测任务描述，LLM便能精准挑选出最具预测性的特征，其表现堪比数据科学领域的标准工具。这些模型在多种查询机制下均展现出此能力，例如，通过零-shot提示，LLM能直接输出特定特征（如“血压”）对预测目标（如“心脏病”）的数值重要性评分，无需额外上下文。最新模型如GPT-4，无论查询方式如何变化，均能稳定识别关键特征，适应多种提示策略。我们在真实数据上的实验证实，基于LLM的特征选择持续展现出与LASSO等数据驱动方法相媲美的性能，即便未接触下游训练数据。此发现不仅预示LLM在训练特征选择上的应用潜力，更可能指导实际操作中应优先收集哪些特征，特别是在数据收集成本高昂的医疗保健等领域，具有重要实践价值。

> In this paper, we demonstrate a surprising capability of large language models (LLMs): given only input feature names and a description of a prediction task, they are capable of selecting the most predictive features, with performance rivaling the standard tools of data science. Remarkably, these models exhibit this capacity across various query mechanisms. For example, we zero-shot prompt an LLM to output a numerical importance score for a feature (e.g., "blood pressure") in predicting an outcome of interest (e.g., "heart failure"), with no additional context. In particular, we find that the latest models, such as GPT-4, can consistently identify the most predictive features regardless of the query mechanism and across various prompting strategies. We illustrate these findings through extensive experiments on real-world data, where we show that LLM-based feature selection consistently achieves strong performance competitive with data-driven methods such as the LASSO, despite never having looked at the downstream training data. Our findings suggest that LLMs may be useful not only for selecting the best features for training but also for deciding which features to collect in the first place. This could potentially benefit practitioners in domains like healthcare, where collecting high-quality data comes at a high cost.

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x1.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x2.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x3.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x4.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x5.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x6.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x7.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x8.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x9.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x10.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x11.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x12.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x13.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x14.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x15.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x16.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x17.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x18.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x19.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x20.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x21.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x22.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x23.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x24.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x25.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x26.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x27.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x28.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x29.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x30.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x31.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x32.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x33.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x34.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x35.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x36.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x37.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x38.png)

![LLM-Select：借助大型语言模型实现特征选择](../../../paper_images/2407.02694/x39.png)

[Arxiv](https://arxiv.org/abs/2407.02694)