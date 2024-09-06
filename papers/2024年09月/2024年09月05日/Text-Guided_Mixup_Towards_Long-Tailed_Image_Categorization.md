# 通过文本引导的混合技术，解决长尾图像分类问题

发布时间：2024年09月05日

`LLM应用` `机器学习` `计算机视觉`

> Text-Guided Mixup Towards Long-Tailed Image Categorization

# 摘要

> 在现实应用中，训练数据的类别标签常呈长尾分布，给需要大量平衡数据的深度神经网络训练带来挑战。收集和标注平衡数据既昂贵又耗时。现有解决方案如集成学习、再平衡策略或微调，都受限于少数类别样本的问题。最近，CLIP 等视觉-语言模型通过捕捉图像和文本对之间的相似性，成为零样本或小样本学习的有效方案。考虑到大型预训练模型可能包含对少数类别有价值的文本信息，我们提出利用文本监督来应对长尾学习挑战。具体来说，我们提出了一种文本引导的混合技术，利用预训练文本编码器识别的类别间语义关系，来缓解长尾问题。我们的实证研究表明，该方法在基准长尾任务上具有理论保证的有效性。代码可在 https://github.com/rsamf/text-guided-mixup 获取。

> In many real-world applications, the frequency distribution of class labels for training data can exhibit a long-tailed distribution, which challenges traditional approaches of training deep neural networks that require heavy amounts of balanced data. Gathering and labeling data to balance out the class label distribution can be both costly and time-consuming. Many existing solutions that enable ensemble learning, re-balancing strategies, or fine-tuning applied to deep neural networks are limited by the inert problem of few class samples across a subset of classes. Recently, vision-language models like CLIP have been observed as effective solutions to zero-shot or few-shot learning by grasping a similarity between vision and language features for image and text pairs. Considering that large pre-trained vision-language models may contain valuable side textual information for minor classes, we propose to leverage text supervision to tackle the challenge of long-tailed learning. Concretely, we propose a novel text-guided mixup technique that takes advantage of the semantic relations between classes recognized by the pre-trained text encoder to help alleviate the long-tailed problem. Our empirical study on benchmark long-tailed tasks demonstrates the effectiveness of our proposal with a theoretical guarantee. Our code is available at https://github.com/rsamf/text-guided-mixup.

[Arxiv](https://arxiv.org/abs/2409.03583)