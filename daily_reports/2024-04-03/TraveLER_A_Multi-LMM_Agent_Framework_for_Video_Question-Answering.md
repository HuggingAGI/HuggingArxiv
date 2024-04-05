# TraveLER：面向视频问答任务的多语言模型代理框架
`RAG` `视频处理` `问答系统`
> 近期，大型多模态模型（LMMs）在视频问答领域取得了突破，它们采用逐帧方法，借助大规模图像预训练，实现了零样本学习。尽管这些基于图像的方法表现出色，但它们常忽略了关键时间戳的选取，并在发现时间戳错误时无法调整。它们也难以提取问题相关的细节，通常只提供帧的泛泛描述。为解决这些问题，我们构建了一个多LMM代理框架，它能够沿着视频进度迭代搜集关键帧信息，通过互动提问积累答案，直至信息充足。我们提出的TraveLER模型，能够规划“穿越”视频的路径，针对每一帧提出“定位”问题，保存关键信息，并评估是否足以作答。若信息不足，模型还能根据已有知识“重新规划”。经过大量实验验证，TraveLER在多个视频问答基准测试中，如NExT-QA、STAR和感知测试，均提升了性能，且无需针对特定数据集进行微调。
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.01476/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.01476/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.01476/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.01476/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.01476/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.01476/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.01476/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.01476/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.01476/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.01476/x10.png)
