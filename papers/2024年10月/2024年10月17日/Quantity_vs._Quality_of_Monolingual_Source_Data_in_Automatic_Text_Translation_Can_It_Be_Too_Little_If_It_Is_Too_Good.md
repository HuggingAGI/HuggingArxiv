# 在自动文本翻译中，单语源数据的数量与质量孰重孰轻？质量虽高，数量不足是否仍能胜任？

发布时间：2024年10月17日

`LLM应用` `数据处理`

> Quantity vs. Quality of Monolingual Source Data in Automatic Text Translation: Can It Be Too Little If It Is Too Good?

# 摘要

> 单语数据因其丰富而易于获取，常被用来补充稀缺的平行数据，以训练更优的翻译模型。自我学习法让模型从自身输出中学习，是利用单语数据的一种方式。然而，若平行数据极为有限，过多的单语数据反而可能损害模型性能。本研究探讨了单语数据是否也可能不足，以及基于质量的筛选是否能提升翻译效果。实验显示，在英语-德语低资源翻译任务中，精选高质量或与目标领域相近的额外数据，往往比全盘利用所有数据更为有效。

> Monolingual data, being readily available in large quantities, has been used to upscale the scarcely available parallel data to train better models for automatic translation. Self-learning, where a model is made to learn from its output, is one approach to exploit such data. However, it has been shown that too much of this data can be detrimental to the performance of the model if the available parallel data is comparatively extremely low. In this study, we investigate whether the monolingual data can also be too little and if this reduction, based on quality, has any effect on the performance of the translation model. Experiments have shown that on English-German low-resource NMT, it is often better to select only the most useful additional data, based on quality or closeness to the domain of the test data, than utilizing all of the available data.

[Arxiv](https://arxiv.org/abs/2410.13783)