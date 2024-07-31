# QAEA-DR：一款专为密集检索设计的统一文本增强框架
发布时间：2024年07月29日

`RAG`
> QAEA-DR: A Unified Text Augmentation Framework for Dense Retrieval
>
> 在密集检索中，长文本嵌入密集向量可能引发信息丢失，影响查询-文本匹配的准确性。同时，噪声过多或关键信息稀疏的低质量文本难以与相关查询有效对齐。近期研究多聚焦于改进句子嵌入模型或检索流程。本研究提出一种创新的文本增强框架，通过将原始文档转换为信息密集的文本格式，补充原始文本，有效应对上述挑战，无需调整嵌入或检索方法。我们利用大型语言模型（LLM）的零-shot提示，生成问答对和元素驱动的事件两种文本表示，并命名为QAEA-DR，旨在统一问答生成与事件提取，优化密集检索的文本增强。此外，我们引入基于评分的评估与再生机制，进一步提升生成文本质量。理论分析与实证实验均证实QAEA-DR模型对密集检索的积极贡献。
>
> https://arxiv.org/abs/2407.20207

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.20207/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.20207/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.20207/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.20207/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.20207/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.20207/x6.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.20207](https://arxiv.org/abs/2407.20207)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1