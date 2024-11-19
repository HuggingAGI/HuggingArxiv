# Invar-RAG：用于更好生成的不变的与大型语言模型对齐的检索
发布时间：2024年11月16日

`RAG`
> Invar-RAG: Invariant LLM-aligned Retrieval for Better Generation
>
> 检索增强生成（RAG）在提供可靠的答案预测和解决幻觉问题方面显示出了令人印象深刻的能力。典型的 RAG 实现使用强大的检索模型来提取外部信息，并使用大型语言模型（LLM）来生成答案。相比之下，最近基于 LLM 的检索因其在信息检索（IR）方面的显著改进而受到关注，这得益于 LLM 的语义理解能力。然而，直接将 LLM 应用于 RAG 系统存在挑战。这可能会导致特征局部性问题，因为大量的参数知识会阻碍对整个语料库中全局信息的有效利用；例如，基于 LLM 的检索器通常输入文档摘要而不是完整的文档。此外，LLM 中的各种预训练任务会引入方差，进一步削弱作为检索器的性能。
为了解决这些问题，我们提出了一种新颖的两阶段微调架构，称为 Invar-RAG。在检索阶段，通过集成基于 LoRA 的表示学习来构建基于 LLM 的检索器，以解决特征局部性问题。为了提高检索性能，我们开发了两种模式（不变模式和可变模式）和一个不变性损失来减少 LLM 的方差。在生成阶段，采用了一种改进的微调方法来提高 LLM 根据检索到的信息生成答案的准确性。实验结果表明，Invar-RAG 在三个开放域问答（ODQA）数据集上显著优于现有的基线。代码可在补充材料中获取以进行重现。
>
> https://arxiv.org/abs/2411.07021

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2411.07021](https://arxiv.org/abs/2411.07021)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)