# 你的数据是否点燃了喜悦？在训练尾声通过领域上采样获得的性能飞跃

发布时间：2024年06月05日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）的预训练数据集对模型性能的影响，并提出了一种策略来优化这一过程。具体来说，研究关注的是如何在通用网页抓取的多样性与特定领域数据的信息密度之间找到最佳平衡点。通过在训练末期对特定领域数据集进行上采样，研究者们提升了模型在多个复杂基准上的表现。这一研究不仅涉及模型的应用，更深入地探讨了模型训练的理论和方法，因此属于LLM理论分类。` `人工智能` `数据处理`

> Does your data spark joy? Performance gains from domain upsampling at the end of training

# 摘要

> 大型语言模型（LLMs）的预训练数据集已包含数万亿令牌，涵盖了大量的CommonCrawl网页抓取和特定领域的数据集。理解这些特定领域数据集对模型性能的影响成本高昂，因为这需要大规模的计算资源来揭示对复杂基准的显著影响。随着预训练数据实验成本的上升，如何找到通用网页抓取的多样性与特定领域数据的信息密度之间的最佳平衡点？在本研究中，我们提出了一种策略：在训练末期对特定领域数据集进行上采样，以提升在复杂基准上的表现。这一策略使我们能够在MMLU上提升6.90分，GSM8K上提升8.26分，HumanEval上提升6.17分，与训练时间长两倍的Llama-2（7B）模型相媲美。通过调整领域上采样的比例，我们发现10%至20%的比例能最佳地平衡通用语言建模与特定基准的需求。此外，我们还利用这一技术评估了在训练末期移除特定数据集对不同基准性能的影响，从而以较低的成本大规模探索预训练数据集的效果。

> Pretraining datasets for large language models (LLMs) have grown to trillions of tokens composed of large amounts of CommonCrawl (CC) web scrape along with smaller, domain-specific datasets. It is expensive to understand the impact of these domain-specific datasets on model capabilities as training at large FLOP scales is required to reveal significant changes to difficult and emergent benchmarks. Given the increasing cost of experimenting with pretraining data, how does one determine the optimal balance between the diversity in general web scrapes and the information density of domain specific data? In this work, we show how to leverage the smaller domain specific datasets by upsampling them relative to CC at the end of training to drive performance improvements on difficult benchmarks. This simple technique allows us to improve up to 6.90 pp on MMLU, 8.26 pp on GSM8K, and 6.17 pp on HumanEval relative to the base data mix for a 7B model trained for 1 trillion (T) tokens, thus rivaling Llama-2 (7B)$\unicode{x2014}$a model trained for twice as long. We experiment with ablating the duration of domain upsampling from 5% to 30% of training and find that 10% to 20% percent is optimal for navigating the tradeoff between general language modeling capabilities and targeted benchmarks. We also use domain upsampling to characterize at scale the utility of individual datasets for improving various benchmarks by removing them during this final phase of training. This tool opens up the ability to experiment with the impact of different pretraining datasets at scale, but at an order of magnitude lower cost compared to full pretraining runs.

![你的数据是否点燃了喜悦？在训练尾声通过领域上采样获得的性能飞跃](../../../paper_images/2406.03476/x1.png)

![你的数据是否点燃了喜悦？在训练尾声通过领域上采样获得的性能飞跃](../../../paper_images/2406.03476/x2.png)

![你的数据是否点燃了喜悦？在训练尾声通过领域上采样获得的性能飞跃](../../../paper_images/2406.03476/x3.png)

[Arxiv](https://arxiv.org/abs/2406.03476)