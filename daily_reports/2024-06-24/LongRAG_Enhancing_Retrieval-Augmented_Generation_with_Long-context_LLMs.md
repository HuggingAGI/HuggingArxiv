# LongRAG：借助长上下文大型语言模型，提升检索增强生成能力
发布时间：2024年06月21日

`RAG`
> LongRAG: Enhancing Retrieval-Augmented Generation with Long-context LLMs
>
> 传统的RAG框架中，检索单元通常较短，如DPR处理100字的维基百科段落，迫使检索器在大规模语料库中寻找关键信息，而阅读器则仅需从这些短单元中提取答案。这种检索器“重”与阅读器“轻”的不平衡设计可能导致性能不佳。为此，我们提出了LongRAG框架，它包含一个能够处理4K令牌单元的“长检索器”和一个“长阅读器”，比之前长30倍，大幅减少了总单元数，从而显著提升了检索效率，答案召回率显著提高。我们将这些长单元输入长上下文LLM进行零样本答案提取，无需额外训练，LongRAG在NQ和HotpotQA上均取得了与最先进模型相当的优异成绩。这一研究为RAG与长上下文LLM的未来结合提供了新的视角。
>
> https://arxiv.org/abs/2406.15319

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.15319/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.15319/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.15319/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.15319/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.15319/x5.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.15319](https://arxiv.org/abs/2406.15319)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验：公众号号菜单回复1
- 最新论文订阅新人：公众号号菜单回复2