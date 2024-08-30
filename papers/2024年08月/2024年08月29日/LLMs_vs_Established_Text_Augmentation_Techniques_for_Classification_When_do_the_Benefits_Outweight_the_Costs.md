# 在分类任务中，大型语言模型与传统文本增强技术相比，何时能带来更多收益而非成本？

发布时间：2024年08月29日

`LLM应用` `数据增强` `机器学习`

> LLMs vs Established Text Augmentation Techniques for Classification: When do the Benefits Outweight the Costs?

# 摘要

> 生成式大型语言模型 (LLM) 正广泛应用于数据增强，通过 LLM 释义文本样本后进行分类器微调。尽管如此，LLM 是否比传统增强方法更具成本效益尚无定论。我们对比了最新 LLM 增强技术与传统方法在多个数据集和分类器上的效果，并调整种子数量以深入探索模型准确性。成本效益分析显示，仅在极少种子情况下，LLM 方法才具优势。多数场合，传统方法同样高效甚至更优。

> The generative large language models (LLMs) are increasingly being used for data augmentation tasks, where text samples are LLM-paraphrased and then used for classifier fine-tuning. However, a research that would confirm a clear cost-benefit advantage of LLMs over more established augmentation methods is largely missing. To study if (and when) is the LLM-based augmentation advantageous, we compared the effects of recent LLM augmentation methods with established ones on 6 datasets, 3 classifiers and 2 fine-tuning methods. We also varied the number of seeds and collected samples to better explore the downstream model accuracy space. Finally, we performed a cost-benefit analysis and show that LLM-based methods are worthy of deployment only when very small number of seeds is used. Moreover, in many cases, established methods lead to similar or better model accuracies.

[Arxiv](https://arxiv.org/abs/2408.16502)