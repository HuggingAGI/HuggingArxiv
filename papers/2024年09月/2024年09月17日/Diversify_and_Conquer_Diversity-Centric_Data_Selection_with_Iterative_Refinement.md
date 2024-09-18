# 多样化征服：聚焦多样性的数据选择与迭代优化

发布时间：2024年09月17日

`LLM理论` `人工智能` `数据科学`

> Diversify and Conquer: Diversity-Centric Data Selection with Iterative Refinement

# 摘要

> 微调大型语言模型以增强其指令跟随能力，关键在于选择最佳数据。随着指令数据集的增多，如何挑选有效训练的数据子集成为焦点。我们提出，相较于局部标准，全局视角下的数据多样性更为重要。通过 k-means 聚类，我们确保选出的数据子集能全面代表整个数据集。借鉴主动学习，我们设计了迭代优化方法，动态调整聚类的采样权重，有效过滤低质量数据。实验表明，这种方法在多个任务中表现优异，比随机选择提升 7%，比现有最佳方法提升 3.8%。这凸显了多样性在微调 LLM 中的关键作用。代码已开源，详见 https://github.com/for-ai/iterative-data-selection。

> Finetuning large language models on instruction data is crucial for enhancing pre-trained knowledge and improving instruction-following capabilities. As instruction datasets proliferate, selecting optimal data for effective training becomes increasingly important. This work addresses the question: How can we determine the optimal subset of data for effective training? While existing research often emphasizes local criteria like instance quality for subset selection, we argue that a global approach focused on data diversity is more critical. Our method employs k-means clustering to ensure the selected subset effectively represents the full dataset. We propose an iterative refinement method inspired by active learning techniques to resample instances from clusters, reassessing each cluster's importance and sampling weight in every training iteration. This approach reduces the effect of outliers and automatically filters out clusters containing low-quality data. Through extensive evaluation across natural language reasoning, general world knowledge, code and math reasoning tasks, and by fine-tuning models from various families, we observe consistent improvements, achieving a 7% increase over random selection and a 3.8% improvement over state-of-the-art sampling methods. Our work highlights the significance of diversity-first sampling when finetuning LLMs to enhance performance across a broad array of evaluation tasks. Our code is available at https://github.com/for-ai/iterative-data-selection.

[Arxiv](https://arxiv.org/abs/2409.11378)