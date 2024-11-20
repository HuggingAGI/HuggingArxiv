# EUREKHA：增强用于地下论坛中关键黑客识别的用户表示
发布时间：2024年11月08日


> EUREKHA: Enhancing User Representation for Key Hackers Identification in Underground Forums
>
> 地下论坛是网络犯罪活动的中心，为匿名和逃避常规在线监督提供了空间。在这些隐藏的社区中，恶意行为者合作交流非法知识、工具和策略，推动了从黑客技术到被盗数据、恶意软件和零日漏洞利用的销售等一系列网络威胁。确定这些操作背后的关键煽动者（即关键黑客）至关重要，但仍然是一个复杂的挑战。本文提出了一种称为 EUREKHA（增强地下论坛中关键黑客识别的用户表示）的新方法，旨在通过将每个用户建模为文本序列来识别这些关键黑客。此序列通过大型语言模型（LLM）进行特定领域的适应，LLM 充当特征提取器。然后将这些提取的特征输入到图神经网络（GNN）中以对用户结构关系进行建模，显著提高识别准确性。此外，我们采用 BERTopic（来自 Transformer 的双向编码器表示主题建模）从用户生成的内容中提取个性化主题，为每个用户实现多个文本表示，并优化最具代表性序列的选择。我们的研究表明，微调的 LLM 在识别关键黑客方面优于最先进的方法。此外，当与 GNN 结合时，我们的模型实现了显著的改进，与现有方法相比，准确率和 F1 分数分别提高了约 6％和 10％。EUREKHA 在 Hack-Forums 数据集上进行了测试，我们提供了代码的开源访问。
>
> https://arxiv.org/abs/2411.05479

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2411.05479](https://arxiv.org/abs/2411.05479)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)