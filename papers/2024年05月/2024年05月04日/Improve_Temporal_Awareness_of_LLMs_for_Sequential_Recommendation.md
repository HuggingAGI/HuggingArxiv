# 提升大型语言模型在序列推荐任务中的时间意识。

发布时间：2024年05月04日

`LLM应用` `序列推荐` `人工智能`

> Improve Temporal Awareness of LLMs for Sequential Recommendation

# 摘要

> 大型语言模型（LLMs）在处理多种通用任务时展现出了卓越的零样本能力。但研究发现，它们在识别和使用时间信息方面存在缺陷，这使得在处理如序列推荐等需要理解序列数据的任务时表现不尽人意。本文提出了一种基于人类认知过程启发的原则性提示框架，以增强 LLMs 对时间信息的敏感度。具体而言，我们设计了三种提示策略，旨在挖掘历史交互中的时间信息，以提升基于 LLM 的序列推荐效果。同时，我们通过整合不同策略产生的 LLM 排名结果，模拟了发散性思维。在 MovieLens-1M 和 Amazon Review 数据集上的测试结果表明，我们的方法显著提升了 LLMs 在序列推荐任务中的零样本性能。

> Large language models (LLMs) have demonstrated impressive zero-shot abilities in solving a wide range of general-purpose tasks. However, it is empirically found that LLMs fall short in recognizing and utilizing temporal information, rendering poor performance in tasks that require an understanding of sequential data, such as sequential recommendation. In this paper, we aim to improve temporal awareness of LLMs by designing a principled prompting framework inspired by human cognitive processes. Specifically, we propose three prompting strategies to exploit temporal information within historical interactions for LLM-based sequential recommendation. Besides, we emulate divergent thinking by aggregating LLM ranking results derived from these strategies. Evaluations on MovieLens-1M and Amazon Review datasets indicate that our proposed method significantly enhances the zero-shot capabilities of LLMs in sequential recommendation tasks.

![提升大型语言模型在序列推荐任务中的时间意识。](../../../paper_images/2405.02778/paper_motivation_2.png)

![提升大型语言模型在序列推荐任务中的时间意识。](../../../paper_images/2405.02778/x1.png)

![提升大型语言模型在序列推荐任务中的时间意识。](../../../paper_images/2405.02778/history_ml.png)

![提升大型语言模型在序列推荐任务中的时间意识。](../../../paper_images/2405.02778/fcl_demos.png)

[Arxiv](https://arxiv.org/abs/2405.02778)