# 仅仅依赖基准训练远远不够

发布时间：2024年09月03日

`LLM应用` `人工智能` `数据安全`

> Training on the Benchmark Is Not All You Need

# 摘要

> 大型语言模型的成功，关键在于预训练阶段所吸收的海量数据。然而，预训练过程的不透明性及其数据的不透明性，使得众多基准测试的可信度大打折扣。一旦模型在测试集上训练，将严重威胁领域的健康发展。为此，众多主流基准测试采用多项选择形式，以实现自动化和高效的能力测试。我们巧妙利用多项选择题选项内容互换不影响题意的特性，提出了一种简便而高效的数据泄露检测方法。具体而言，我们通过打乱选项内容生成衍生数据集，并依据模型在衍生数据集上的对数概率分布来识别数据泄露。若对数概率集合中出现极值和异常值，则数据泄露的嫌疑极大。我们的方法在黑盒条件下运作，无需触及模型训练数据或权重，能有效侦测预训练数据中的基准测试集泄露，涵盖正常与复杂场景，包括选项的有意或无意打乱。实验证明，我们的方法在两个 LLM 和基准设计中表现出色。此外，我们对 31 个主流开源 LLM 在四个基准数据集上的泄露程度进行了评估，并给出了泄露 LLM 的排名，结果显示 Qwen 系列 LLM 的泄露程度最为严重。

> The success of Large Language Models (LLMs) relies heavily on the huge amount of pre-training data learned in the pre-training phase. The opacity of the pre-training process and the training data causes the results of many benchmark tests to become unreliable. If any model has been trained on a benchmark test set, it can seriously hinder the health of the field. In order to automate and efficiently test the capabilities of large language models, numerous mainstream benchmarks adopt a multiple-choice format. As the swapping of the contents of multiple-choice options does not affect the meaning of the question itself, we propose a simple and effective data leakage detection method based on this property. Specifically, we shuffle the contents of the options in the data to generate the corresponding derived data sets, and then detect data leakage based on the model's log probability distribution over the derived data sets. If there is a maximum and outlier in the set of log probabilities, it indicates that the data is leaked. Our method is able to work under black-box conditions without access to model training data or weights, effectively identifying data leakage from benchmark test sets in model pre-training data, including both normal scenarios and complex scenarios where options may have been shuffled intentionally or unintentionally. Through experiments based on two LLMs and benchmark designs, we demonstrate the effectiveness of our method. In addition, we evaluate the degree of data leakage of 31 mainstream open-source LLMs on four benchmark datasets and give a ranking of the leaked LLMs for each benchmark, and we find that the Qwen family of LLMs has the highest degree of data leakage.

[Arxiv](https://arxiv.org/abs/2409.01790)