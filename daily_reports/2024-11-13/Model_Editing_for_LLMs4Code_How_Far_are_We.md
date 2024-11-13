# 针对 LLMs4Code 的模型编辑：我们走了多远？
发布时间：2024年11月10日

`代码编写`
> Model Editing for LLMs4Code: How Far are We?
>
> 用于代码的大型语言模型（LLMs4Code）已被发现在软件工程领域表现出色，特别是在编码任务中的显著表现。然而，即使是最先进的 LLMs4Code 也不可避免地包含不正确或过时的代码知识。由于训练 LLMs4Code 的成本很高，重新训练模型以修复这些有问题的代码知识是不切实际的。模型编辑是一个新的技术领域，用于有效和高效地纠正 LLMs 中的错误知识，最近已经提出了各种模型编辑技术和基准。尽管如此，一个全面的研究，彻底比较和分析最先进的模型编辑技术在适应 LLMs4Code 内的知识在各种与代码相关的任务中的性能是明显缺失的。为了弥补这一差距，我们对应用最先进的模型编辑方法来修复 LLMs4Code 的不准确性进行了首次系统研究。为此，我们引入了一个名为 CLMEEval 的基准，它由两个数据集组成，即具有 21K + 代码生成样本的 CoNaLa-Edit（CNLE）和具有 16K + 代码摘要样本的 CodeSearchNet-Edit（CSNE）。在 CLMEEval 的帮助下，我们在三个 LLMs4Code 上评估了六种先进的模型编辑技术：CodeLlama（7B）、CodeQwen1.5（7B）和 Stable-Code（3B）。我们的发现包括基于外部记忆的 GRACE 方法实现了最佳的知识编辑有效性和特异性（编辑不影响未目标的知识），而泛化（编辑是否可以推广到其他语义相同的输入）是现有技术的普遍挑战。此外，基于深入的案例分析，我们引入了 GRACE 的增强版本称为 A-GRACE，它结合了对比学习以更好地捕获输入的语义。
>
> https://arxiv.org/abs/2411.06638

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2411.06638](https://arxiv.org/abs/2411.06638)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)