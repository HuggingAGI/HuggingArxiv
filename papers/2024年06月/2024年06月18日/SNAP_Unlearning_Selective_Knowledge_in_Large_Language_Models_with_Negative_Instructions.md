# SNAP：利用负面指令在大规模语言模型中精妙遗忘选择性知识

发布时间：2024年06月18日

`LLM应用

理由：这篇论文主要讨论了大型语言模型（LLMs）在处理个人或版权信息泄露问题时的应用，特别是通过提出SNAP框架来实现选择性信息遗忘。这种方法直接应用于现有的LLMs，以改进其处理敏感信息的能力，属于LLM的具体应用场景，而非理论研究或Agent、RAG的范畴。因此，将其归类为LLM应用是合适的。` `隐私保护`

> SNAP: Unlearning Selective Knowledge in Large Language Models with Negative Instructions

# 摘要

> 像ChatGPT这样的指令遵循型大型语言模型（LLMs）越来越受到大众的喜爱，许多人将其纳入日常生活。然而，这些模型有时会无意泄露个人或版权信息，这就需要一种机器遗忘技术来剔除特定知识。以往的方法试图切断目标信息与其关联实体之间的联系，结果却产生了关于目标的不良反应，影响了用户体验。为此，我们提出了SNAP框架，它通过1）训练LLM使用负面指令产生消除性反应，2）强化硬正例以维持原始性能，3）采用Wasserstein正则化确保模型权重与初始状态有适当偏离，从而实现选择性信息遗忘。我们在多个NLP基准测试中验证了SNAP，结果显示，该框架不仅成功移除了指定信息，还保持了LLM的原有能力。

> Instruction-following large language models (LLMs), such as ChatGPT, have become increasingly popular with the general audience, many of whom are incorporating them into their daily routines. However, these LLMs inadvertently disclose personal or copyrighted information, which calls for a machine unlearning method to remove selective knowledge. Previous attempts sought to forget the link between the target information and its associated entities, but it rather led to generating undesirable responses about the target, compromising the end-user experience. In this work, we propose SNAP, an innovative framework designed to selectively unlearn information by 1) training an LLM with negative instructions to generate obliterated responses, 2) augmenting hard positives to retain the original LLM performance, and 3) applying the novel Wasserstein regularization to ensure adequate deviation from the initial weights of the LLM. We evaluate our framework on various NLP benchmarks and demonstrate that our approach retains the original LLM capabilities, while successfully unlearning the specified information.

![SNAP：利用负面指令在大规模语言模型中精妙遗忘选择性知识](../../../paper_images/2406.12329/x1.png)

![SNAP：利用负面指令在大规模语言模型中精妙遗忘选择性知识](../../../paper_images/2406.12329/x2.png)

![SNAP：利用负面指令在大规模语言模型中精妙遗忘选择性知识](../../../paper_images/2406.12329/x3.png)

![SNAP：利用负面指令在大规模语言模型中精妙遗忘选择性知识](../../../paper_images/2406.12329/x4.png)

![SNAP：利用负面指令在大规模语言模型中精妙遗忘选择性知识](../../../paper_images/2406.12329/x5.png)

[Arxiv](https://arxiv.org/abs/2406.12329)