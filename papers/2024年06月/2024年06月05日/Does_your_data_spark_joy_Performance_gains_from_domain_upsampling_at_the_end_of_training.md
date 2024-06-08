# 你的数据是否点燃了喜悦？训练尾声的领域上采样，如何为性能提升添砖加瓦。

发布时间：2024年06月05日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）预训练数据集中特定领域数据集对模型性能的影响，并提出了一种在训练末期对特定领域数据集进行上采样的方法，以优化模型在特定基准上的表现。这种方法涉及对预训练数据集的策略调整，属于对LLM训练过程的理论研究，因此归类为LLM理论。` `机器学习` `数据处理`

> Does your data spark joy? Performance gains from domain upsampling at the end of training

# 摘要

> 大型语言模型（LLMs）的预训练数据集已包含数万亿令牌，涵盖了大量CommonCrawl网页抓取数据和特定领域的小型数据集。然而，要揭示这些特定领域数据集对模型性能的影响，需要在大规模计算下进行训练，成本高昂。面对预训练数据实验成本的上升，我们如何找到通用网页抓取与特定领域数据信息密度之间的最佳平衡点？本研究提出了一种简单方法：在训练末期对特定领域数据集进行上采样，以提升在困难基准上的表现。这种方法使我们的7B模型在MMLU、GSM8K和HumanEval基准上分别提升了6.90、8.26和6.17个百分点，与训练时间翻倍的Llama-2（7B）模型相媲美。通过调整特定领域数据上采样的持续时间（从5%到30%的训练周期），我们发现10%至20%的比例能最佳平衡通用语言建模与特定基准的需求。此外，我们还通过在训练末期移除特定数据集来评估它们对提升不同基准的贡献，这一策略大大降低了大规模实验预训练数据集影响的成本。

> Pretraining datasets for large language models (LLMs) have grown to trillions of tokens composed of large amounts of CommonCrawl (CC) web scrape along with smaller, domain-specific datasets. It is expensive to understand the impact of these domain-specific datasets on model capabilities as training at large FLOP scales is required to reveal significant changes to difficult and emergent benchmarks. Given the increasing cost of experimenting with pretraining data, how does one determine the optimal balance between the diversity in general web scrapes and the information density of domain specific data? In this work, we show how to leverage the smaller domain specific datasets by upsampling them relative to CC at the end of training to drive performance improvements on difficult benchmarks. This simple technique allows us to improve up to 6.90 pp on MMLU, 8.26 pp on GSM8K, and 6.17 pp on HumanEval relative to the base data mix for a 7B model trained for 1 trillion (T) tokens, thus rivaling Llama-2 (7B)$\unicode{x2014}$a model trained for twice as long. We experiment with ablating the duration of domain upsampling from 5% to 30% of training and find that 10% to 20% percent is optimal for navigating the tradeoff between general language modeling capabilities and targeted benchmarks. We also use domain upsampling to characterize at scale the utility of individual datasets for improving various benchmarks by removing them during this final phase of training. This tool opens up the ability to experiment with the impact of different pretraining datasets at scale, but at an order of magnitude lower cost compared to full pretraining runs.

![你的数据是否点燃了喜悦？训练尾声的领域上采样，如何为性能提升添砖加瓦。](../../../paper_images/2406.03476/x1.png)

![你的数据是否点燃了喜悦？训练尾声的领域上采样，如何为性能提升添砖加瓦。](../../../paper_images/2406.03476/x2.png)

![你的数据是否点燃了喜悦？训练尾声的领域上采样，如何为性能提升添砖加瓦。](../../../paper_images/2406.03476/x3.png)

[Arxiv](https://arxiv.org/abs/2406.03476)