# RAGCache：为检索增强型生成提供高效的知识缓存解决方案
发布时间：2024年04月18日
`RAG`
> 检索增强生成（RAG）融合了大型语言模型（LLM）与外部知识库的长处，在多种自然语言处理任务中实现了显著的性能提升。但这种方法也带来了长序列生成的问题，增加了计算和内存的开销。为此，我们设计了托特（Thoth），一款专为RAG优化的创新多级动态缓存系统。通过对现有RAG系统的深入分析，我们发现了性能瓶颈——知识注入导致的序列过长，以及潜在的优化点——缓存知识的中间状态。托特通过知识树结构来组织并缓存检索到的知识中间状态，同时在GPU和主机内存中进行有效管理。此外，托特还引入了一种智能替换策略，能够适应LLM的推理特性和RAG的检索模式，并通过动态地并行处理检索与推理步骤，有效降低了整体的延迟。我们在顶尖的LLM推理系统vLLM和向量数据库Faiss上对托特进行了实现和测试，实验结果显示，托特在减少首个令牌生成时间（TTFT）和提升处理吞吐量方面，相比vLLM结合Faiss的方案，分别提升了至多4倍和2.1倍。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12457/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12457/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12457/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12457/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12457/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12457/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12457/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12457/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12457/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12457/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12457/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12457/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12457/x13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12457/x14.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12457/x15.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12457/x16.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12457/x17.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12457/x18.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12457/x19.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12457/x20.png)

[https://wx.zsxq.com/dweb2/index/topic_detail/2855282424444841](https://wx.zsxq.com/dweb2/index/topic_detail/2855282424444841)

[https://arxiv.org/abs/2404.12457](https://arxiv.org/abs/2404.12457)