# 探究大型语言模型中涌现现象的量化方法

发布时间：2024年05月21日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）中涌现现象的量化方法，这是对LLMs理论层面的深入研究。论文提出的新方法是通过比较宏观语义层面与微观令牌层面的熵减少来衡量涌现强度，这种方法涉及对模型内部机制的理解和分析，属于理论研究的范畴。此外，论文还探讨了如何通过较小模型来估计更大模型的涌现，这也是理论研究的一部分，因为它涉及到模型性能的预测和理解。因此，这篇论文应归类为LLM理论。` `人工智能`

> Quantifying Emergence in Large Language Models

# 摘要

> 涌现，通常被理解为LLMs展现的“智能”行为，近期研究显示其量化难度大，因缺乏明确的定义。目前，涌现多通过模型在众多数据集和任务上的表现进行统计评估，这一过程耗费资源且解释性差，未必能准确捕捉模型内在的涌现特性。本研究提出了一种量化涌现的新方法，灵感源自动力学中的涌现理论，通过比较宏观语义层面与微观令牌层面的熵减少来衡量涌现强度，这些数据均来自变换器模块内的表示。我们采用低成本的估计方法，在ICL和自然语言处理中，对包括GPT-2、GEMMA等模型进行了测试，结果显示：(1) 我们的方法与基于性能的现有观察结果一致，证明了我们量化方法的有效性；(2) 新提出的指标揭示了涌现的新模式，如指标方差与ICL中“射击”次数的相关性，为理解LLMs中的幻觉提供了新视角；(3) 我们提出了一种通过较小模型（如GPT-2）来估计更大、封闭资源模型涌现的方法。相关代码已公开，详情请访问：https://github.com/Zodiark-ch/Emergence-of-LLMs/。

> Emergence, broadly conceptualized as the ``intelligent'' behaviors of LLMs, has recently been studied and proved challenging to quantify due to the lack of a measurable definition. Most commonly, it has been estimated statistically through model performances across extensive datasets and tasks, which consumes significant resources. In addition, such estimation is difficult to interpret and may not accurately reflect the models' intrinsic emergence. In this work, we propose a quantifiable solution for estimating emergence. Inspired by emergentism in dynamics, we quantify the strength of emergence by comparing the entropy reduction of the macroscopic (semantic) level with that of the microscopic (token) level, both of which are derived from the representations within the transformer block. Using a low-cost estimator, our quantification method demonstrates consistent behaviors across a suite of LMs (GPT-2, GEMMA, etc.) under both in-context learning (ICL) and natural sentences. Empirical results show that (1) our method gives consistent measurements which align with existing observations based on performance metrics, validating the effectiveness of our emergence quantification; (2) our proposed metric uncovers novel emergence patterns such as the correlations between the variance of our metric and the number of ``shots'' in ICL, which further suggests a new way of interpreting hallucinations in LLMs; (3) we offer a potential solution towards estimating the emergence of larger and closed-resource LMs via smaller LMs like GPT-2. Our codes are available at: https://github.com/Zodiark-ch/Emergence-of-LLMs/.

[Arxiv](https://arxiv.org/abs/2405.12617)