# OpenAI-o1 AB 测试：o1 模型在数学问题解决中真的能很好地推理吗？

发布时间：2024年11月09日

`LLM应用` `模型评估`

> OpenAI-o1 AB Testing: Does the o1 model really do good reasoning in math problem solving?

# 摘要

> OpenAI 的 Orion-1 模型据称比以前的大型语言模型具有更强大的逻辑推理能力。然而，有人认为这种卓越性可能部分是由于模型“记住”了解决方案，导致在提示训练数据中不存在的问题时性能不太令人满意。我们使用两个数据集进行比较实验：一个由容易获取的国际数学奥林匹克（IMO）问题组成；另一个由难度相似但不那么容易获取的中国国家队训练营（CNT）问题组成。我们为每个问题标注响应，并比较两个数据集之间的性能。我们得出结论，没有明显的证据表明该模型依赖于记住问题和解决方案。此外，我们进行案例研究来分析模型响应的一些特征。

> The Orion-1 model by OpenAI is claimed to have more robust logical reasoning capabilities than previous large language models. However, some suggest the excellence might be partially due to the model "memorizing" solutions, resulting in less satisfactory performance when prompted with problems not in the training data. We conduct a comparison experiment using two datasets: one consisting of International Mathematics Olympiad (IMO) problems, which is easily accessible; the other one consisting of Chinese National Team Training camp (CNT) problems, which have similar difficulty but not as publically accessible. We label the response for each problem and compare the performance between the two datasets. We conclude that there is no significant evidence to show that the model relies on memorizing problems and solutions. Also, we perform case studies to analyze some features of the model's response.

[Arxiv](https://arxiv.org/abs/2411.06198)