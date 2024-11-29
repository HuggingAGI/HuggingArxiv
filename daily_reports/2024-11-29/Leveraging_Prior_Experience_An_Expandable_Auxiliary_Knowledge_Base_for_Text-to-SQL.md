# 借助先前经验：面向文本到 SQL 的可扩展辅助知识库
发布时间：2024年11月20日

`代码编写`
> Leveraging Prior Experience: An Expandable Auxiliary Knowledge Base for Text-to-SQL
>
> 大型语言模型（LLMs）在众多任务中展现出了出色的问题解决能力，然而在诸如文本到 SQL 等各类下游应用中，其表现仍逊于人类。在 BIRD 基准排行榜上，人类表现的准确率高达 92.96%，而表现最佳的方法仅达 72.39%。值得注意的是，这些前沿（SoTA）方法主要依赖于上下文学习来模拟人类般的推理。但它们忽略了一项关键的人类技能：持续学习。受我们成长过程中整理错题本这一教育实践的启发，我们提出了 LPE-SQL（利用先前经验：用于文本到 SQL 的可扩展辅助知识库），这是一个旨在增强 LLMs 的新型框架，能够实现持续学习，且无需参数微调。LPE-SQL 由四个模块构成，分别是\(i\)）检索相关条目，\(ii\)）高效生成 SQL，\(iii\)）通过交叉一致性机制生成最终结果，以及\(iv\)）记录成功和失败的任务及其推理过程或反思生成的提示。重要的是，LPE-SQL 的核心模块是第四个，其他模块则采用基础方法，这使得 LPE-SQL 能够轻松与 SoTA 技术相融合，进一步提升性能。我们的实验结果表明，这种持续学习的方式带来了显著的性能提升，较小的 Llama-3.1-70B 模型的性能超越了使用 SoTA 方法的较大的 Llama-3.1-405B 模型。
>
> https://arxiv.org/abs/2411.13244

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2411.13244](https://arxiv.org/abs/2411.13244)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)