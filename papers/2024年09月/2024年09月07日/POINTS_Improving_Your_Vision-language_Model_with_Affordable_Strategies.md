# POINTS：用实惠的策略升级你的视觉-语言模型

发布时间：2024年09月07日

`LLM应用` `计算机视觉`

> POINTS: Improving Your Vision-language Model with Affordable Strategies

# 摘要

> 近年来，视觉-语言模型在光学字符识别和几何问题解决等任务中表现优异。然而，仍存在一些关键问题：1) 专有模型缺乏架构透明度，开源模型则需更详细的训练策略分析。2) 开源预训练数据探索不足，添加数据集过程繁琐。3) 微调主要依赖数据集添加，导致收益递减。为此，我们提出：1) 利用最新技术训练稳健基线模型，并进行全面消融验证。2) 借鉴大型语言模型，用困惑度筛选预训练数据，精选1M数据集训练，性能优异。3) 视觉指令微调中，当数据集添加效果有限时，采用模型汤策略。最终，我们构建了9B参数模型，性能媲美最先进模型，策略高效轻量，易于社区采纳。

> In recent years, vision-language models have made significant strides, excelling in tasks like optical character recognition and geometric problem-solving. However, several critical issues remain: 1) Proprietary models often lack transparency about their architectures, while open-source models need more detailed ablations of their training strategies. 2) Pre-training data in open-source works is under-explored, with datasets added empirically, making the process cumbersome. 3) Fine-tuning often focuses on adding datasets, leading to diminishing returns. To address these issues, we propose the following contributions: 1) We trained a robust baseline model using the latest advancements in vision-language models, introducing effective improvements and conducting comprehensive ablation and validation for each technique. 2) Inspired by recent work on large language models, we filtered pre-training data using perplexity, selecting the lowest perplexity data for training. This approach allowed us to train on a curated 1M dataset, achieving competitive performance. 3) During visual instruction tuning, we used model soup on different datasets when adding more datasets yielded marginal improvements. These innovations resulted in a 9B parameter model that performs competitively with state-of-the-art models. Our strategies are efficient and lightweight, making them easily adoptable by the community.

[Arxiv](https://arxiv.org/abs/2409.04828)