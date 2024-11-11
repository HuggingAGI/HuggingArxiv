# 微调视觉语言模型用于自动化工程图纸信息提取

发布时间：2024年11月06日

`LLM应用` `制造业` `视觉语言模型`

> Fine-Tuning Vision-Language Model for Automated Engineering Drawing Information Extraction

# 摘要

> 几何尺寸与公差（GD&T）在制造业中起着关键作用，它通过定义零件特征的可接受变化来确保组件的质量和功能。然而，从二维工程图纸中提取 GD&T 信息是一项耗时且劳动密集型的任务，通常依赖人工努力或半自动工具。为了应对这些挑战，本研究通过微调开源的视觉语言模型（VLM）Florence-2 提出了一种自动化且计算效率高的 GD&T 提取方法。该模型在由领域专家提供真实标注的 400 张图纸的数据集上进行训练。为了进行比较，在相同的数据集上对两个最先进的闭源 VLM，GPT-4o 和 Claude-3.5-Sonnet 进行了评估。所有模型都使用精度、召回率、F1 分数和幻觉指标进行评估。由于针对特定领域任务微调大型闭源 VLM 的计算成本和不切实际性，GPT-4o 和 Claude-3.5-Sonnet 在零样本设置中进行评估。相比之下，具有 2.3 亿参数的较小模型 Florence-2 通过在三个不同的实验中进行全参数微调进行优化，每个实验都使用了扩充到不同水平的数据集。结果表明，与表现最佳的闭源模型相比，Florence-2 的精度提高了 29.95％，召回率提高了 37.75％，F1 分数提高了 52.40％，幻觉率降低了 43.15％。这些发现突出了微调像 Florence-2 这样较小的开源 VLM 的有效性，为支持下游制造任务的自动化 GD&T 提取提供了实用且高效的解决方案。

> Geometric Dimensioning and Tolerancing (GD&T) plays a critical role in manufacturing by defining acceptable variations in part features to ensure component quality and functionality. However, extracting GD&T information from 2D engineering drawings is a time-consuming and labor-intensive task, often relying on manual efforts or semi-automated tools. To address these challenges, this study proposes an automated and computationally efficient GD&T extraction method by fine-tuning Florence-2, an open-source vision-language model (VLM). The model is trained on a dataset of 400 drawings with ground truth annotations provided by domain experts. For comparison, two state-of-the-art closed-source VLMs, GPT-4o and Claude-3.5-Sonnet, are evaluated on the same dataset. All models are assessed using precision, recall, F1-score, and hallucination metrics. Due to the computational cost and impracticality of fine-tuning large closed-source VLMs for domain-specific tasks, GPT-4o and Claude-3.5-Sonnet are evaluated in a zero-shot setting. In contrast, Florence-2, a smaller model with 0.23 billion parameters, is optimized through full-parameter fine-tuning across three distinct experiments, each utilizing datasets augmented to different levels. The results show that Florence-2 achieves a 29.95% increase in precision, a 37.75% increase in recall, a 52.40% improvement in F1-score, and a 43.15% reduction in hallucination rate compared to the best-performing closed-source model. These findings highlight the effectiveness of fine-tuning smaller, open-source VLMs like Florence-2, offering a practical and efficient solution for automated GD&T extraction to support downstream manufacturing tasks.

[Arxiv](https://arxiv.org/abs/2411.03707)