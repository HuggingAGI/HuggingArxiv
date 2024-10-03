# 大型语言模型的涌现能力背后，U形和倒U形缩放起着关键作用。

发布时间：2024年10月02日

`LLM理论` `人工智能` `机器学习`

> U-shaped and Inverted-U Scaling behind Emergent Abilities of Large Language Models

# 摘要

> LLM 在某些任务中展现出独特的涌现能力，起初性能停滞，随后在规模超越某个临界点时，性能骤然提升。我们发现，难题呈现 U 形增长，而简单问题则先倒 U 形后稳步提升。有趣的是，涌现阈值恰与简单问题从反向缩放转向标准缩放的转折点相吻合。基于此，我们设计了名为“切片三明治”的简洁高效流程，用以预测这一阈值及超越阈值后的模型表现。

> Large language models (LLMs) have been shown to exhibit emergent abilities in some downstream tasks, where performance seems to stagnate at first and then improve sharply and unpredictably with scale beyond a threshold. By dividing questions in the datasets according to difficulty level by average performance, we observe U-shaped scaling for hard questions, and inverted-U scaling followed by steady improvement for easy questions. Moreover, the emergence threshold roughly coincides with the point at which performance on easy questions reverts from inverse scaling to standard scaling. Capitalizing on the observable though opposing scaling trend on easy and hard questions, we propose a simple yet effective pipeline, called Slice-and-Sandwich, to predict both the emergence threshold and model performance beyond the threshold.

[Arxiv](https://arxiv.org/abs/2410.01692)