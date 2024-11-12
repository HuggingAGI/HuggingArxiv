# 大型语言模型的样本高效对齐

发布时间：2024年11月09日

`LLM应用` `语言模型` `偏好对齐`

> Sample-Efficient Alignment for LLMs

# 摘要

> 我们研究了在给定预算在线反馈的情况下，有效使大型语言模型（LLM）与人类偏好对齐的方法。我们首先在上下文决斗强盗的框架中制定了 LLM 对齐问题。这种制定方式，包含了最近的范式，如在线 RLHF 和在线 DPO，本质上寻求结合在线主动探索的样本高效算法。利用强盗理论的见解，我们引入了一种基于汤普森采样的统一算法，并强调了其在两种不同的 LLM 对齐场景中的应用。有效实现此算法的实际代理，名为 SEA（样本高效对齐），通过在三个模型规模（1B、2.8B、6.9B）和三种偏好学习算法（DPO、IPO、SLiC）上进行的大量实验得到了经验验证。结果表明，SEA 实现了与神谕偏好的高度样本高效对齐，优于最近针对 LLM 的主动探索方法。此外，我们发布了 SEA 的实现以及为 LLM 在线对齐设计的高效代码库，旨在加速该领域的未来研究。

> We study methods for efficiently aligning large language models (LLMs) with human preferences given budgeted online feedback. We first formulate the LLM alignment problem in the frame of contextual dueling bandits. This formulation, subsuming recent paradigms such as online RLHF and online DPO, inherently quests for sample-efficient algorithms that incorporate online active exploration. Leveraging insights from bandit theory, we introduce a unified algorithm based on Thompson sampling and highlight its applications in two distinct LLM alignment scenarios. The practical agent that efficiently implements this algorithm, named SEA (Sample-Efficient Alignment), is empirically validated through extensive experiments across three model scales (1B, 2.8B, 6.9B) and three preference learning algorithms (DPO, IPO, SLiC). The results demonstrate that SEA achieves highly sample-efficient alignment with oracle's preferences, outperforming recent active exploration methods for LLMs. Additionally, we release the implementation of SEA together with an efficient codebase designed for online alignment of LLMs, aiming to accelerate future research in this field.

[Arxiv](https://arxiv.org/abs/2411.01493)