# CREAM：一致性正则化自我奖励语言模型

发布时间：2024年10月16日

`LLM理论` `人工智能`

> CREAM: Consistency Regularized Self-Rewarding Language Models

# 摘要

> 最近的自奖励 LLM 通过 LLM-as-a-Judge 实现了无需人工注释的迭代对齐性能提升。这些方法通常让同一个 LLM 同时扮演策略模型和奖励模型的角色。然而，这一过程中奖励和排序的准确性无法保证，这对高质量偏好数据至关重要。实证结果显示，自奖励在几次迭代后可能失效，原因在于奖励系统中的累积偏差。为解决这一问题，我们提出了广义迭代偏好微调框架，并引入正则化以减轻过度自信的偏好标签。基于此，我们开发了 CREAM 模型，利用不同迭代间的奖励一致性进行正则化训练，从而提升奖励一致性和对齐性能。实证结果显示，CREAM 表现优异。代码已公开在 https://github.com/Raibows/CREAM。

> Recent self-rewarding large language models (LLM) have successfully applied LLM-as-a-Judge to iteratively improve the alignment performance without the need of human annotations for preference data. These methods commonly utilize the same LLM to act as both the policy model (which generates responses) and the reward model (which scores and ranks those responses). The ranked responses are then used as preference pairs to train the LLM via direct alignment technologies (e.g. DPO). However, it is noteworthy that throughout this process, there is no guarantee of accuracy in the rewarding and ranking, which is critical for ensuring accurate rewards and high-quality preference data. Empirical results from relatively small LLMs (e.g., 7B parameters) also indicate that improvements from self-rewarding may diminish after several iterations in certain situations, which we hypothesize is due to accumulated bias in the reward system. This bias can lead to unreliable preference data for training the LLM. To address this issue, we first formulate and analyze the generalized iterative preference fine-tuning framework for self-rewarding language model. We then introduce the regularization to this generalized framework to mitigate the overconfident preference labeling in the self-rewarding process. Based on this theoretical insight, we propose a Consistency Regularized sElf-rewarding lAnguage Model (CREAM) that leverages the rewarding consistency across different iterations to regularize the self-rewarding training, helping the model to learn from more reliable preference data. With this explicit regularization, our empirical results demonstrate the superiority of CREAM in improving both reward consistency and alignment performance. The code is publicly available at https://github.com/Raibows/CREAM.

[Arxiv](https://arxiv.org/abs/2410.12735)