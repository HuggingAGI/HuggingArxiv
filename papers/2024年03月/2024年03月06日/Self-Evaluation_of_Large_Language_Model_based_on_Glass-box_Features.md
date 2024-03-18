# 针对大型语言模型，本研究采用 Glass-box 特征进行自我评估，旨在通过解析模型内部透明可见的特征来评价其性能表现。

发布时间：2024年03月06日

`LLM应用`

> Self-Evaluation of Large Language Model based on Glass-box Features

> 随着开源LLMs的广泛应用，亟需有效的评估手段。当前研究大多依赖外部评估并关注训练与提示策略，却忽略了模型内在机理这一关键要素——玻璃盒特征。本次研究创新性地探讨了在自我评估情境下，利用LLM评估自身生成结果时玻璃盒特征的作用。我们深入探究了不同类型的玻璃盒特征，发现softmax分布可作为评估质量的有力依据。进一步地，我们提出了两种融合参考信息衍生特征以增强评估效果的策略，并在公共基准测试中证实了运用玻璃盒特征进行LLMs自我评估切实可行。

> The proliferation of open-source Large Language Models (LLMs) underscores the pressing need for evaluation methods. Existing works primarily rely on external evaluators, focusing on training and prompting strategies. However, a crucial aspect - model-aware glass-box features - is overlooked. In this study, we explore the utility of glass-box features under the scenario of self-evaluation, namely applying an LLM to evaluate its own output. We investigate various glass-box feature groups and discovered that the softmax distribution serves as a reliable indicator for quality evaluation. Furthermore, we propose two strategies to enhance the evaluation by incorporating features derived from references. Experimental results on public benchmarks validate the feasibility of self-evaluation of LLMs using glass-box features.

[Arxiv](https://arxiv.org/abs/2403.04222)