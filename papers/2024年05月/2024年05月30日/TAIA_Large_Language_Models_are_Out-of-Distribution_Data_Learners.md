# TAIA: 大型语言模型擅长学习分布外数据

发布时间：2024年05月30日

`LLM应用

这篇论文主要探讨了在特定任务中微调大型语言模型（LLMs）的方法，特别是在医疗保健或无害内容生成等专业领域。论文提出了一种新的推理时策略，即训练所有参数但在推理时仅激活注意力，这种方法在处理数据不匹配问题时表现出色，并在多个下游任务中显示出优于传统微调模型的性能。因此，这篇论文的内容更偏向于LLM的应用层面，特别是在优化模型性能和适应特定任务方面的应用。` `医疗保健` `人工智能`

> TAIA: Large Language Models are Out-of-Distribution Data Learners

# 摘要

> 微调特定任务的问答对是提升大型语言模型（LLMs）在下游任务上性能的主流方法。但在医疗保健或无害内容生成等专业领域，获取与下游任务匹配的高质量数据极为困难。为此，我们重新审视了Transformer架构，发现并非所有微调参数都对下游性能有益。特别是在自注意力和前馈网络中，只有当训练集与测试集不完全对齐时，微调的注意力参数才显示出显著优势。据此，我们提出了一种创新的推理时策略：训练所有参数，但推理时仅激活注意力（\trainallInfAttn）。通过在两个通用数据集上验证，并在七个涉及数学、推理和知识理解的下游任务上评估，我们发现\trainallInfAttn在多数情况下显著优于完全微调模型和基础模型。其对数据不匹配的高容忍性使其在专业任务中表现出色，同时有效抵御了越狱调整的风险。

> Fine-tuning on task-specific question-answer pairs is a predominant method for enhancing the performance of instruction-tuned large language models (LLMs) on downstream tasks. However, in certain specialized domains, such as healthcare or harmless content generation, it is nearly impossible to obtain a large volume of high-quality data that matches the downstream distribution. To improve the performance of LLMs in data-scarce domains with domain-mismatched data, we re-evaluated the Transformer architecture and discovered that not all parameter updates during fine-tuning contribute positively to downstream performance. Our analysis reveals that within the self-attention and feed-forward networks, only the fine-tuned attention parameters are particularly beneficial when the training set's distribution does not fully align with the test set. Based on this insight, we propose an effective inference-time intervention method: \uline{T}raining \uline{A}ll parameters but \uline{I}nferring with only \uline{A}ttention (\trainallInfAttn). We empirically validate \trainallInfAttn using two general instruction-tuning datasets and evaluate it on seven downstream tasks involving math, reasoning, and knowledge understanding across LLMs of different parameter sizes and fine-tuning techniques. Our comprehensive experiments demonstrate that \trainallInfAttn achieves superior improvements compared to both the fully fine-tuned model and the base model in most scenarios, with significant performance gains. The high tolerance of \trainallInfAttn to data mismatches makes it resistant to jailbreaking tuning and enhances specialized tasks using general data.

![TAIA: 大型语言模型擅长学习分布外数据](../../../paper_images/2405.20192/x1.png)

![TAIA: 大型语言模型擅长学习分布外数据](../../../paper_images/2405.20192/x2.png)

![TAIA: 大型语言模型擅长学习分布外数据](../../../paper_images/2405.20192/x3.png)

![TAIA: 大型语言模型擅长学习分布外数据](../../../paper_images/2405.20192/x4.png)

![TAIA: 大型语言模型擅长学习分布外数据](../../../paper_images/2405.20192/x5.png)

![TAIA: 大型语言模型擅长学习分布外数据](../../../paper_images/2405.20192/x6.png)

![TAIA: 大型语言模型擅长学习分布外数据](../../../paper_images/2405.20192/x7.png)

![TAIA: 大型语言模型擅长学习分布外数据](../../../paper_images/2405.20192/x8.png)

![TAIA: 大型语言模型擅长学习分布外数据](../../../paper_images/2405.20192/x9.png)

![TAIA: 大型语言模型擅长学习分布外数据](../../../paper_images/2405.20192/x10.png)

![TAIA: 大型语言模型擅长学习分布外数据](../../../paper_images/2405.20192/x11.png)

![TAIA: 大型语言模型擅长学习分布外数据](../../../paper_images/2405.20192/x12.png)

![TAIA: 大型语言模型擅长学习分布外数据](../../../paper_images/2405.20192/x13.png)

[Arxiv](https://arxiv.org/abs/2405.20192)