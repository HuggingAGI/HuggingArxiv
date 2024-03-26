# 是否有一种“一模通用”的信息抽取解决方案？让我们再次探讨任务定义偏差在其中的作用。

发布时间：2024年03月24日

`LLM应用` `信息抽取` `模型偏差`

> Is There a One-Model-Fits-All Approach to Information Extraction? Revisiting Task Definition Biases

> 定义偏差这一负面现象易使模型误入歧途，在信息抽取领域不仅横跨不同领域的数据集，甚至在同领域内共享的数据集中也会出现。本文区分了IE中两类定义偏差：数据集内部的定义偏差以及信息抽取数据集与指令调整数据集间的偏差。为深入探索定义偏差，我们设计了三组探测实验，量化分析并揭示了统一信息抽取方法及大型语言模型在应对定义偏差时的局限。为此，我们创新提出一套包含定义偏差测量、注重偏差的微调以及针对具体任务的偏差缓解在内的多阶段框架。实验证明，该框架在解决定义偏差问题上成效显著，相关资源可在https://github.com/EZ-hwh/definition-bias获取。

> Definition bias is a negative phenomenon that can mislead models. Definition bias in information extraction appears not only across datasets from different domains but also within datasets sharing the same domain. We identify two types of definition bias in IE: bias among information extraction datasets and bias between information extraction datasets and instruction tuning datasets. To systematically investigate definition bias, we conduct three probing experiments to quantitatively analyze it and discover the limitations of unified information extraction and large language models in solving definition bias. To mitigate definition bias in information extraction, we propose a multi-stage framework consisting of definition bias measurement, bias-aware fine-tuning, and task-specific bias mitigation. Experimental results demonstrate the effectiveness of our framework in addressing definition bias. Resources of this paper can be found at https://github.com/EZ-hwh/definition-bias

[Arxiv](https://arxiv.org/abs/2403.16396)