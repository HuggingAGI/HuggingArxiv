# 优化型越狱技术在大规模语言模型上的新进展

发布时间：2024年05月31日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）的安全性问题，并提出了一系列针对现有优化越狱技术的改进措施。这些改进措施包括使用多样化的模板和自动多坐标更新策略，以及采用由易到难的初始化技巧。这些研究内容更偏向于理论层面的探讨和方法论的改进，而不是直接的应用或Agent的设计。因此，将其归类为LLM理论是合适的。` `网络安全` `人工智能安全`

> Improved Techniques for Optimization-Based Jailbreaking on Large Language Models

# 摘要

> 大型语言模型（LLMs）的快速发展中，安全性对齐是其广泛应用的关键。红队行动中，贪婪坐标梯度（GCG）攻击的成功引发了基于优化越狱技术的研究热潮。尽管GCG标志着重要进展，但其攻击效率仍有待提高。本文提出了一系列针对GCG等优化越狱技术的改进措施。我们发现，“Sure”单一模板严重限制了GCG的攻击效果，因此建议采用包含误导性自我建议和指导的多样化模板。同时，我们提出了一种自动多坐标更新策略，通过自适应调整每步替换的令牌数量来加速收敛，并采用了由易到难的初始化技巧。这些技术的结合催生了高效的越狱方法——$\mathcal{I}$-GCG。实验结果显示，这些改进使GCG超越了当前最佳越狱攻击，实现了近100%的成功率。相关代码已公开于https://github.com/jiaxiaojunQAQ/I-GCG。

> Large language models (LLMs) are being rapidly developed, and a key component of their widespread deployment is their safety-related alignment. Many red-teaming efforts aim to jailbreak LLMs, where among these efforts, the Greedy Coordinate Gradient (GCG) attack's success has led to a growing interest in the study of optimization-based jailbreaking techniques. Although GCG is a significant milestone, its attacking efficiency remains unsatisfactory. In this paper, we present several improved (empirical) techniques for optimization-based jailbreaks like GCG. We first observe that the single target template of "Sure" largely limits the attacking performance of GCG; given this, we propose to apply diverse target templates containing harmful self-suggestion and/or guidance to mislead LLMs. Besides, from the optimization aspects, we propose an automatic multi-coordinate updating strategy in GCG (i.e., adaptively deciding how many tokens to replace in each step) to accelerate convergence, as well as tricks like easy-to-hard initialisation. Then, we combine these improved technologies to develop an efficient jailbreak method, dubbed $\mathcal{I}$-GCG. In our experiments, we evaluate on a series of benchmarks (such as NeurIPS 2023 Red Teaming Track). The results demonstrate that our improved techniques can help GCG outperform state-of-the-art jailbreaking attacks and achieve nearly 100% attack success rate. The code is released at https://github.com/jiaxiaojunQAQ/I-GCG.

![优化型越狱技术在大规模语言模型上的新进展](../../../paper_images/2405.21018/x1.png)

![优化型越狱技术在大规模语言模型上的新进展](../../../paper_images/2405.21018/x2.png)

![优化型越狱技术在大规模语言模型上的新进展](../../../paper_images/2405.21018/x3.png)

![优化型越狱技术在大规模语言模型上的新进展](../../../paper_images/2405.21018/x4.png)

![优化型越狱技术在大规模语言模型上的新进展](../../../paper_images/2405.21018/x5.png)

![优化型越狱技术在大规模语言模型上的新进展](../../../paper_images/2405.21018/x6.png)

![优化型越狱技术在大规模语言模型上的新进展](../../../paper_images/2405.21018/x7.png)

![优化型越狱技术在大规模语言模型上的新进展](../../../paper_images/2405.21018/x8.png)

[Arxiv](https://arxiv.org/abs/2405.21018)