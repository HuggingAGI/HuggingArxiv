# CrossTune —— 引入标签增强技术，针对黑盒环境下的少量样本分类任务提供解决方案

发布时间：2024年03月19日

`LLM应用` `模型优化`

> CrossTune: Black-Box Few-Shot Classification with Label Enhancement

# 摘要

> 面对LLMs训练和微调对计算资源的巨大需求，一种创新思路是将它们当作黑盒并运用前向传播技术进行互动。现有研究集中于借助无梯度提示优化手段让黑盒模型更好地适应下游任务，然而寻找任务特异性提示的过程耗时且成本高昂。有鉴于此，我们着手研究无需搜索提示的黑盒语言模型适应方案。我们创新地提出了一种名为CrossTune的标签强化交叉注意力网络，该网络能够捕捉输入文本序列与目标任务标签描述间的语义联系。在小样本文本分类任务中验证了CrossTune的有效性，并进一步利用ChatGPT通过上下文学习为模型生成附加训练数据，同时设立筛选机制剔除质量欠佳的生成数据。经过在七大权威文本分类数据集上的广泛实验，结果显示我们的方法平均超越了以往最先进的无梯度黑盒调优技术5.7%，即便没有采用ChatGPT增强数据集，CrossTune依然展现出优于或至少可媲美以往黑盒调优方法的性能，有力证实了我们方法的优越性。

> Training or finetuning large-scale language models (LLMs) requires substantial computation resources, motivating recent efforts to explore parameter-efficient adaptation to downstream tasks. One approach is to treat these models as black boxes and use forward passes (Inference APIs) to interact with them. Current research focuses on adapting these black-box models to downstream tasks using gradient-free prompt optimization, but this often involves an expensive process of searching task-specific prompts. Therefore, we are motivated to study black-box language model adaptation without prompt search. Specifically, we introduce a label-enhanced cross-attention network called CrossTune, which models the semantic relatedness between the input text sequence and task-specific label descriptions. Its effectiveness is examined in the context of few-shot text classification. To improve the generalization of CrossTune, we utilize ChatGPT to generate additional training data through in-context learning. A switch mechanism is implemented to exclude low-quality ChatGPT-generated data. Through extensive experiments on seven benchmark text classification datasets, we demonstrate that our proposed approach outperforms the previous state-of-the-art gradient-free black-box tuning method by 5.7% on average. Even without using ChatGPT-augmented data, CrossTune performs better or comparably than previous black-box tuning methods, suggesting the effectiveness of our approach.

![CrossTune —— 引入标签增强技术，针对黑盒环境下的少量样本分类任务提供解决方案](../../../paper_images/2403.12468/x1.png)

![CrossTune —— 引入标签增强技术，针对黑盒环境下的少量样本分类任务提供解决方案](../../../paper_images/2403.12468/x2.png)

![CrossTune —— 引入标签增强技术，针对黑盒环境下的少量样本分类任务提供解决方案](../../../paper_images/2403.12468/x3.png)

![CrossTune —— 引入标签增强技术，针对黑盒环境下的少量样本分类任务提供解决方案](../../../paper_images/2403.12468/embedding_plots.png)

![CrossTune —— 引入标签增强技术，针对黑盒环境下的少量样本分类任务提供解决方案](../../../paper_images/2403.12468/x4.png)

[Arxiv](https://arxiv.org/abs/2403.12468)