# 动态子集调整：扩大大型语言模型参数高效训练的操作范围

发布时间：2024年11月13日

`LLM应用` `模型训练`

> Dynamic Subset Tuning: Expanding the Operational Range of Parameter-Efficient Training for Large Language Models

# 摘要

> 我们为大型语言模型提出了一种新颖的参数高效训练（PET）方法，通过优化现有模型参数的一小部分来使模型适应下游任务。与先前的方法不同，这个子集的位置不是固定的，而是在训练过程中哪些参数被修改是不断变化的。这种动态参数选择可以用比现有方法少得多的参数产生良好的性能。我们的方法能够在整个模型大小的任意比例上无缝扩展子集的大小，而像提示调整和 LoRA 这样流行的 PET 方法只覆盖了这个范围的一小部分。在给定的参数预算下，对于不同的模型家族和大小，在大多数情况下，我们在各种 NLP 任务（MT、QA、GSM8K、SuperGLUE）上与提示调整和 LoRA 相当或表现更优。

> We propose a novel parameter-efficient training (PET) method for large language models that adapts models to downstream tasks by optimizing a small subset of the existing model parameters. Unlike prior methods, this subset is not fixed in location but rather which parameters are modified evolves over the course of training. This dynamic parameter selection can yield good performance with many fewer parameters than extant methods. Our method enables a seamless scaling of the subset size across an arbitrary proportion of the total model size, while popular PET approaches like prompt tuning and LoRA cover only a small part of this spectrum. We match or outperform prompt tuning and LoRA in most cases on a variety of NLP tasks (MT, QA, GSM8K, SuperGLUE) for a given parameter budget across different model families and sizes.

[Arxiv](https://arxiv.org/abs/2411.08610)