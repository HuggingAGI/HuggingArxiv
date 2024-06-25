# 《只需提示：借助大型语言模型自动化重现Android漏洞》

发布时间：2024年05月08日

`Agent

理由：这篇论文介绍了一种名为 AdbGPT 的自动化工具，它利用大型语言模型（LLMs）的能力来模拟开发者的思维过程，以自动重现软件中的bug。这种方法通过少样本学习和思维链推理来实现，不需要传统的训练和硬编码。因此，它更像是一个智能代理（Agent），能够自主地执行任务（即bug重现），而不是仅仅应用或理论探讨。此外，它的功能和设计强调了其作为Agent的特性，即通过理解和推理来自动化复杂的任务。` `软件维护` `自动化测试`

> Prompting Is All You Need: Automated Android Bug Replay with Large Language Models

# 摘要

> Bug报告是软件维护的关键，它让用户能够向开发者反馈使用中的问题。为此，研究者们致力于自动化bug重现，以加快维护进程。但现有方法的成效受限于bug报告的质量和特性，这些方法依赖于人工设定的模式和词汇。借鉴大型语言模型（LLMs）在自然语言理解上的成就，我们开发了AdbGPT，一种无需训练和硬编码的新型轻量级方法，通过提示工程自动重现bug。AdbGPT运用少样本学习和思维链推理，模拟开发者思维，高效完成bug重现。评估表明，AdbGPT在253.6秒内成功重现了81.3%的bug报告，优于现有技术。我们还通过用户研究验证了AdbGPT在提升开发者bug重现能力上的价值。

> Bug reports are vital for software maintenance that allow users to inform developers of the problems encountered while using the software. As such, researchers have committed considerable resources toward automating bug replay to expedite the process of software maintenance. Nonetheless, the success of current automated approaches is largely dictated by the characteristics and quality of bug reports, as they are constrained by the limitations of manually-crafted patterns and pre-defined vocabulary lists. Inspired by the success of Large Language Models (LLMs) in natural language understanding, we propose AdbGPT, a new lightweight approach to automatically reproduce the bugs from bug reports through prompt engineering, without any training and hard-coding effort. AdbGPT leverages few-shot learning and chain-of-thought reasoning to elicit human knowledge and logical reasoning from LLMs to accomplish the bug replay in a manner similar to a developer. Our evaluations demonstrate the effectiveness and efficiency of our AdbGPT to reproduce 81.3% of bug reports in 253.6 seconds, outperforming the state-of-the-art baselines and ablation studies. We also conduct a small-scale user study to confirm the usefulness of AdbGPT in enhancing developers' bug replay capabilities.

[Arxiv](https://arxiv.org/abs/2306.01987)