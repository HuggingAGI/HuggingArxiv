# M3DocRAG：多模态检索是您理解多页多文档所需要的。
发布时间：2024年11月07日

`RAG`
> M3DocRAG: Multi-modal Retrieval is What You Need for Multi-page Multi-document Understanding
>
> 文档视觉问答（DocVQA）管道用于回答来自文档的问题，具有广泛的应用。现有的方法侧重于使用多模态语言模型（MLM）处理单页文档，或者依赖于使用诸如光学字符识别（OCR）等文本提取工具的基于文本的检索增强生成（RAG）。然而，在现实场景中应用这些方法存在困难：（a）问题通常需要跨不同页面或文档的信息，而 MLM 无法处理许多长文档；（b）文档经常在诸如图形等视觉元素中具有重要信息，但文本提取工具会忽略它们。我们引入了 M3DocRAG，这是一种新颖的多模态 RAG 框架，能够灵活适应各种文档上下文（封闭域和开放域）、问题跳转（单跳和多跳）和证据模式（文本、图表、图形等）。M3DocRAG 使用多模态检索器和 MLM 查找相关文档并回答问题，因此它可以有效地处理单个或多个文档，同时保留视觉信息。由于以前的 DocVQA 数据集在特定文档的上下文中提出问题，我们还提出了 M3DocVQA，这是一个新的基准，用于评估超过 3000 多个 PDF 文档和 40000 多页的开放域 DocVQA。在三个基准（M3DocVQA/MMLongBench-Doc/MP-DocVQA）中，实证结果表明，带有 ColPali 和 Qwen2-VL 7B 的 M3DocRAG 比许多强大的基线表现更优，包括在 MP-DocVQA 中的最先进性能。我们提供了对不同索引、MLM 和检索模型的综合分析。最后，我们定性地表明，M3DocRAG 能够成功处理各种场景，例如当相关信息存在于多个页面中以及当答案证据仅存在于图像中时。
>
> https://arxiv.org/abs/2411.04952

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2411.04952](https://arxiv.org/abs/2411.04952)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)