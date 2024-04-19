# iRAG：一种为视频内容设计的渐进式检索增强生成系统
发布时间：2024年04月18日
`RAG`
> 检索增强生成（RAG）系统融合了语言生成与信息检索的长处，广泛应用于聊天机器人等实际应用。RAG 在整合理解多模态数据，如文本、图像和视频方面颇具潜力，但面临两大挑战：一是将大量多模态数据一次性转换为文本描述，处理耗时；二是文本描述往往无法涵盖所有多模态数据中的信息。鉴于用户查询无法预先知晓，构建一个能够将多模态数据转换为文本并进行交互式查询的系统颇具难度。为应对这些挑战，我们提出了 iRAG，这是一种创新的增量式工作流程，它扩展了 RAG 系统，使其能够交互式地查询大规模多模态数据集。与传统 RAG 相比，iRAG 能够迅速构建大型多模态数据库的索引，并在增量式工作流程中，利用索引从多模态数据的选定部分提取更多细节，以响应用户的交互式查询。这种方法避免了长时间的多模态到文本的转换，通过按需提取多模态数据中的细节，解决了信息丢失问题，并确保了对用户查询的响应质量。据我们所知，iRAG 是首个采用增量式工作流程增强 RAG 系统的案例，旨在高效地支持大规模现实世界多模态数据的交互式查询。在现实世界长视频上的实验结果显示，视频转文本的速度提升了 23 至 25 倍，同时保证了交互式用户查询的响应质量，与传统 RAG 系统相比毫不逊色。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12309/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12309/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12309/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12309/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12309/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12309/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12309/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12309/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12309/x9.png)

[https://wx.zsxq.com/dweb2/index/topic_detail/2855288158222451](https://wx.zsxq.com/dweb2/index/topic_detail/2855288158222451)

[https://arxiv.org/abs/2404.12309](https://arxiv.org/abs/2404.12309)