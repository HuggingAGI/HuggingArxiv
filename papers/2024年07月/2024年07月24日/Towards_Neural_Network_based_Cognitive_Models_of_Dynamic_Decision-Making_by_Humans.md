# 探索基于神经网络的人类动态决策认知模型

发布时间：2024年07月24日

`Agent` `网络安全` `人工智能`

> Towards Neural Network based Cognitive Models of Dynamic Decision-Making by Humans

# 摘要

> 在动态决策任务中模拟人类认知过程一直是AI领域的长期挑战。虽然早期研究尝试使用神经网络和大型语言模型，但往往采用单一模型来概括所有人类行为。然而，每个人的行为都独具特色，受特定任务经验影响。为此，我们借鉴了基于实例的学习（IBL）模型，该模型认为决策基于过往类似情境。我们设计了两种基于注意力机制的神经网络模型，用于模拟动态环境下的决策过程。实验采用两个独特数据集：一是人类检测钓鱼邮件，二是人类在网络安全中扮演攻击者选择攻击策略。通过与IBL和GPT3.5的对比实验，我们发现其中一个神经网络模型在模拟人类决策上表现最佳。有趣的是，模型在预测更擅长任务的人的决策时更为准确。此外，我们还探讨了模型如何基于其预测中的关键因素来解释人类决策。总体而言，我们的研究为神经网络在人类决策认知建模中的应用展现了光明前景。代码已公开在https://github.com/shshnkreddy/NCM-HDM。

> Modelling human cognitive processes in dynamic decision-making tasks has been an endeavor in AI for a long time. Some initial works have attempted to utilize neural networks (and large language models) but often assume one common model for all humans and aim to emulate human behavior in aggregate. However, behavior of each human is distinct, heterogeneous and relies on specific past experiences in specific tasks. To that end, we build on a well known model of cognition, namely Instance Based Learning (IBL), that posits that decisions are made based on similar situations encountered in the past. We propose two new attention based neural network models to model human decision-making in dynamic settings. We experiment with two distinct datasets gathered from human subject experiment data, one focusing on detection of phishing email by humans and another where humans act as attackers in a cybersecurity setting and decide on an attack option. We conduct extensive experiments with our two neural network models, IBL, and GPT3.5, and demonstrate that one of our neural network models achieves the best performance in representing human decision-making. We find an interesting trend that all models predict a human's decision better if that human is better at the task. We also explore explanation of human decisions based on what our model considers important in prediction. Overall, our work yields promising results for further use of neural networks in cognitive modelling of human decision making. Our code is available at https://github.com/shshnkreddy/NCM-HDM.

[Arxiv](https://arxiv.org/abs/2407.17622)