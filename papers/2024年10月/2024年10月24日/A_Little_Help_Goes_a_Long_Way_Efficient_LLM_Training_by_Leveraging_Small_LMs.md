# 一点帮助作用很大：通过利用小型语言模型进行高效的大型语言模型训练

发布时间：2024年10月24日

`LLM理论` `语言模型` `预训练`

> A Little Help Goes a Long Way: Efficient LLM Training by Leveraging Small LMs

# 摘要

> 大型语言模型（LLM）开发中的一个主要挑战是其繁重的预训练成本。通常，这种预训练涉及在一个大型语料库上优化一个自监督目标（如下一令牌预测）。本文探讨了一种有前途的范式，通过适当地利用小型语言模型（SLM）来提高 LLM 预训练的效率和质量。特别是，这种范式依赖于 SLM 来（1）提供软标签作为额外的训练监督，以及（2）选择一小部分有价值的（“信息丰富”和“困难”）训练示例。综合起来，这能够有效地将 SLM 的预测分布转移到 LLM，同时优先考虑训练数据分布的特定区域。从经验上看，与标准训练相比，这减少了 LLM 的训练时间，同时提高了整体质量。从理论上讲，我们开发了一个统计框架，以系统地研究 SLM 在实现高质量 LLM 的高效训练中的效用。特别是，我们的框架描述了 SLM 看似低质量的监督如何能够增强更强大的 LLM 的训练。此外，它还强调了需要自适应地利用这种监督，在 SLM 提供的软标签引入的偏差和方差之间取得平衡。我们通过在 Pile 数据集上利用具有 15 亿参数的较小 LM 来改进具有 28 亿参数的 LLM 的预训练，从而证实了我们的理论框架。

> A primary challenge in large language model (LLM) development is their onerous pre-training cost. Typically, such pre-training involves optimizing a self-supervised objective (such as next-token prediction) over a large corpus. This paper explores a promising paradigm to improve LLM pre-training efficiency and quality by suitably leveraging a small language model (SLM). In particular, this paradigm relies on an SLM to both (1) provide soft labels as additional training supervision, and (2) select a small subset of valuable ("informative" and "hard") training examples. Put together, this enables an effective transfer of the SLM's predictive distribution to the LLM, while prioritizing specific regions of the training data distribution. Empirically, this leads to reduced LLM training time compared to standard training, while improving the overall quality. Theoretically, we develop a statistical framework to systematically study the utility of SLMs in enabling efficient training of high-quality LLMs. In particular, our framework characterizes how the SLM's seemingly low-quality supervision can enhance the training of a much more capable LLM. Furthermore, it also highlights the need for an adaptive utilization of such supervision, by striking a balance between the bias and variance introduced by the SLM-provided soft labels. We corroborate our theoretical framework by improving the pre-training of an LLM with 2.8B parameters by utilizing a smaller LM with 1.5B parameters on the Pile dataset.

[Arxiv](https://arxiv.org/abs/2410.18779)