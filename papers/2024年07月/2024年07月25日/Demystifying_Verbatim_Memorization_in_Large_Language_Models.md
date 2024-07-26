# 探究大型语言模型中的逐字记忆之谜

发布时间：2024年07月25日

`LLM理论`

> Demystifying Verbatim Memorization in Large Language Models

# 摘要

> 大型语言模型常逐字记忆长序列，带来严重的法律和隐私问题。为此，我们设计了一个框架，在受控环境中通过继续预训练和注入序列来研究逐字记忆。研究发现：(1) 大量重复是逐字记忆的前提；(2) 较新的模型更易记忆，甚至包括分布外的序列；(3) 记忆生成依赖于编码高级特征的模型状态，并充分利用了语言建模能力。基于此，我们进行了压力测试，发现遗忘方法难以彻底移除记忆，且会损害模型性能。这些发现表明，逐字记忆并非源于特定机制，而是与模型的通用能力紧密相关，因此难以在不损害模型质量的前提下进行隔离和抑制。

> Large Language Models (LLMs) frequently memorize long sequences verbatim, often with serious legal and privacy implications. Much prior work has studied such verbatim memorization using observational data. To complement such work, we develop a framework to study verbatim memorization in a controlled setting by continuing pre-training from Pythia checkpoints with injected sequences. We find that (1) non-trivial amounts of repetition are necessary for verbatim memorization to happen; (2) later (and presumably better) checkpoints are more likely to verbatim memorize sequences, even for out-of-distribution sequences; (3) the generation of memorized sequences is triggered by distributed model states that encode high-level features and makes important use of general language modeling capabilities. Guided by these insights, we develop stress tests to evaluate unlearning methods and find they often fail to remove the verbatim memorized information, while also degrading the LM. Overall, these findings challenge the hypothesis that verbatim memorization stems from specific model weights or mechanisms. Rather, verbatim memorization is intertwined with the LM's general capabilities and thus will be very difficult to isolate and suppress without degrading model quality.

![探究大型语言模型中的逐字记忆之谜](../../../paper_images/2407.17817/x1.png)

![探究大型语言模型中的逐字记忆之谜](../../../paper_images/2407.17817/x2.png)

![探究大型语言模型中的逐字记忆之谜](../../../paper_images/2407.17817/x3.png)

![探究大型语言模型中的逐字记忆之谜](../../../paper_images/2407.17817/x4.png)

![探究大型语言模型中的逐字记忆之谜](../../../paper_images/2407.17817/x5.png)

![探究大型语言模型中的逐字记忆之谜](../../../paper_images/2407.17817/x6.png)

![探究大型语言模型中的逐字记忆之谜](../../../paper_images/2407.17817/x7.png)

![探究大型语言模型中的逐字记忆之谜](../../../paper_images/2407.17817/x8.png)

![探究大型语言模型中的逐字记忆之谜](../../../paper_images/2407.17817/x9.png)

![探究大型语言模型中的逐字记忆之谜](../../../paper_images/2407.17817/x10.png)

![探究大型语言模型中的逐字记忆之谜](../../../paper_images/2407.17817/x11.png)

![探究大型语言模型中的逐字记忆之谜](../../../paper_images/2407.17817/x12.png)

![探究大型语言模型中的逐字记忆之谜](../../../paper_images/2407.17817/x13.png)

![探究大型语言模型中的逐字记忆之谜](../../../paper_images/2407.17817/exp-dep-vs-step-6.9b.png)

![探究大型语言模型中的逐字记忆之谜](../../../paper_images/2407.17817/exp-dep-vs-layer-6.9b.png)

![探究大型语言模型中的逐字记忆之谜](../../../paper_images/2407.17817/exp-component-vs-mem-pythia-160m-freq5e4.png)

![探究大型语言模型中的逐字记忆之谜](../../../paper_images/2407.17817/exp-component-vs-mem-pythia-160m-freq1e4.png)

![探究大型语言模型中的逐字记忆之谜](../../../paper_images/2407.17817/x14.png)

![探究大型语言模型中的逐字记忆之谜](../../../paper_images/2407.17817/x15.png)

![探究大型语言模型中的逐字记忆之谜](../../../paper_images/2407.17817/x16.png)

![探究大型语言模型中的逐字记忆之谜](../../../paper_images/2407.17817/x17.png)

![探究大型语言模型中的逐字记忆之谜](../../../paper_images/2407.17817/x18.png)

![探究大型语言模型中的逐字记忆之谜](../../../paper_images/2407.17817/x19.png)

[Arxiv](https://arxiv.org/abs/2407.17817)