# 探索低资源语言翻译的高效参数微调方法

发布时间：2024年04月05日

`LLM应用` `低资源语言` `神经机器翻译`

> Unlocking Parameter-Efficient Fine-Tuning for Low-Resource Language Translation

# 摘要

> 参数高效微调（PEFT）技术对于调整大型预训练语言模型以应对多样化任务至关重要，它在保持适应性和计算效率之间取得了平衡。在低资源语言的神经机器翻译（NMT）领域，PEFT技术尤其关键，能够在资源有限的情况下提升翻译的准确度。然而，不同语言间PEFT的实际效果参差不齐。我们通过在多个不同规模和领域的低资源语言环境中进行广泛的实证实验，利用SacreBLEU评分对8种PEFT方法及其15种不同架构进行了性能评估。结果表明，有6种PEFT架构在相关和非相关领域的测试中均超越了基准水平，而Houlsby+Inversion适配器的整体表现最为出色，验证了PEFT方法的有效性。

> Parameter-efficient fine-tuning (PEFT) methods are increasingly vital in adapting large-scale pre-trained language models for diverse tasks, offering a balance between adaptability and computational efficiency. They are important in Low-Resource Language (LRL) Neural Machine Translation (NMT) to enhance translation accuracy with minimal resources. However, their practical effectiveness varies significantly across different languages. We conducted comprehensive empirical experiments with varying LRL domains and sizes to evaluate the performance of 8 PEFT methods with in total of 15 architectures using the SacreBLEU score. We showed that 6 PEFT architectures outperform the baseline for both in-domain and out-domain tests and the Houlsby+Inversion adapter has the best performance overall, proving the effectiveness of PEFT methods.

![探索低资源语言翻译的高效参数微调方法](../../../paper_images/2404.04212/peft.png)

![探索低资源语言翻译的高效参数微调方法](../../../paper_images/2404.04212/heatmap.png)

![探索低资源语言翻译的高效参数微调方法](../../../paper_images/2404.04212/languages.png)

[Arxiv](https://arxiv.org/abs/2404.04212)