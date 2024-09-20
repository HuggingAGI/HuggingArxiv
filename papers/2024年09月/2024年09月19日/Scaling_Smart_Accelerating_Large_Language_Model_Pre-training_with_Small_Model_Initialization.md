# 智能扩展：从小模型起步，加速大型语言模型的预训练进程。

发布时间：2024年09月19日

`LLM理论` `人工智能` `云计算`

> Scaling Smart: Accelerating Large Language Model Pre-training with Small Model Initialization

# 摘要

> 语言模型的预训练通常从随机参数开始，但随着模型规模的扩大，训练成本和时间也随之增加。相比之下，小型模型虽成本低廉，但准确性有限。本文探讨了一个创新思路：能否用小型预训练模型初始化大型模型？这种初始化能否提升训练效率和准确性？我们提出了HyperCloning方法，通过扩展预训练模型的参数，使其具备更大模型的隐藏维度，同时保留原有功能。这样，大型模型在训练前已具备小型模型的预测能力。实验表明，这种方法显著减少了预训练大型模型所需的GPU时间。

> The pre-training phase of language models often begins with randomly initialized parameters. With the current trends in scaling models, training their large number of parameters can be extremely slow and costly. In contrast, small language models are less expensive to train, but they often cannot achieve the accuracy of large models. In this paper, we explore an intriguing idea to connect these two different regimes: Can we develop a method to initialize large language models using smaller pre-trained models? Will such initialization bring any benefits in terms of training time and final accuracy? In this paper, we introduce HyperCloning, a method that can expand the parameters of a pre-trained language model to those of a larger model with increased hidden dimensions. Our method ensures that the larger model retains the functionality of the smaller model. As a result, the larger model already inherits the predictive power and accuracy of the smaller model before the training starts. We demonstrate that training such an initialized model results in significant savings in terms of GPU hours required for pre-training large language models.

[Arxiv](https://arxiv.org/abs/2409.12903)