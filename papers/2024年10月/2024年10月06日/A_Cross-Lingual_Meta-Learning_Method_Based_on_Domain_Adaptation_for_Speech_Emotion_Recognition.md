# 一种基于领域适应的跨语言元学习方法，专为语音情感识别设计。

发布时间：2024年10月06日

`LLM应用` `语音识别` `情感分析`

> A Cross-Lingual Meta-Learning Method Based on Domain Adaptation for Speech Emotion Recognition

# 摘要

> 顶尖的语音模型依赖于大量特定语言的数据进行训练，但多数语言数据稀缺，训练难度大。尤其在语音情感识别领域，数据短缺问题更为突出。我们专注于在有限数据条件下，提升语音情感识别的模型性能。通过引入元学习技术，我们不仅优化了语音情感识别，还改进了口音识别和个人身份识别。我们提出了一系列多阶段元学习方法的改进，不同于其他因计算成本高而选择小模型的研究，我们采用更实际的策略，结合大型预训练模型和原型网络，使方法更具可行性。最值得一提的是，我们在元测试阶段采用的改进微调技术，显著提升了模型在分布外数据集上的表现。这些成果，加上其他研究的逐步改进，使我们在4-way 5-shot学习环境下，对未参与训练和验证的希腊语和罗马尼亚语语音情感识别数据集，分别达到了83.78%和56.30%的准确率。

> Best-performing speech models are trained on large amounts of data in the language they are meant to work for. However, most languages have sparse data, making training models challenging. This shortage of data is even more prevalent in speech emotion recognition. Our work explores the model's performance in limited data, specifically for speech emotion recognition. Meta-learning specializes in improving the few-shot learning. As a result, we employ meta-learning techniques on speech emotion recognition tasks, accent recognition, and person identification. To this end, we propose a series of improvements over the multistage meta-learning method. Unlike other works focusing on smaller models due to the high computational cost of meta-learning algorithms, we take a more practical approach. We incorporate a large pre-trained backbone and a prototypical network, making our methods more feasible and applicable. Our most notable contribution is an improved fine-tuning technique during meta-testing that significantly boosts the performance on out-of-distribution datasets. This result, together with incremental improvements from several other works, helped us achieve accuracy scores of 83.78% and 56.30% for Greek and Romanian speech emotion recognition datasets not included in the training or validation splits in the context of 4-way 5-shot learning.

[Arxiv](https://arxiv.org/abs/2410.04633)