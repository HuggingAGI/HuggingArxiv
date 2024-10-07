# 大型语言模型的信息流分析：一种开放性研究

发布时间：2024年10月03日

`LLM应用` `软件工程` `网络安全`

> Permissive Information-Flow Analysis for Large Language Models

# 摘要

> 大型语言模型 (LLM) 正迅速成为软件系统的重要组成部分，但也带来了安全和隐私的挑战。例如，一个组件中的有害数据可能改变模型行为，甚至泄露机密信息。传统的污点跟踪方法过于保守，不适用于 LLM 处理多样输入的场景。为此，我们提出了一种更灵活的信息流标签传播方法，仅标记对输出有影响的输入，忽略无关信息。我们基于提示和 $k$-nearest-neighbors 语言模型实现了两种变体，并与基线方法进行了比较。结果显示，我们的方法在超过 85% 的情况下提升了标签准确性，证明了其在增强检索中的实用价值。

> Large Language Models (LLMs) are rapidly becoming commodity components of larger software systems. This poses natural security and privacy problems: poisoned data retrieved from one component can change the model's behavior and compromise the entire system, including coercing the model to spread confidential data to untrusted components. One promising approach is to tackle this problem at the system level via dynamic information flow (aka taint) tracking. Unfortunately, the traditional approach of propagating the most restrictive input label to the output is too conservative for applications where LLMs operate on inputs retrieved from diverse sources. In this paper, we propose a novel, more permissive approach to propagate information flow labels through LLM queries. The key idea behind our approach is to propagate only the labels of the samples that were influential in generating the model output and to eliminate the labels of unnecessary input. We implement and investigate the effectiveness of two variations of this approach, based on (i) prompt-based retrieval augmentation, and (ii) a $k$-nearest-neighbors language model. We compare these with the baseline of an introspection-based influence estimator that directly asks the language model to predict the output label. The results obtained highlight the superiority of our prompt-based label propagator, which improves the label in more than 85% of the cases in an LLM agent setting. These findings underscore the practicality of permissive label propagation for retrieval augmentation.

[Arxiv](https://arxiv.org/abs/2410.03055)