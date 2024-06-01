# VideoTree：一种基于树结构的自适应视频表示方法，专为大型语言模型处理长视频推理而设计。
发布时间：2024年05月29日

`多模态大模型`
> VideoTree: Adaptive Tree-based Video Representation for LLM Reasoning on Long Videos
>
> 视频-语言理解任务传统上聚焦于短视频片段，而长视频理解则是一大挑战。近期，借助大型语言模型（LLMs）的推理能力，长视频问答领域取得了进展，方法是将视频密集采样为帧标题，再由LLMs处理文本查询。但这种方法常因帧的冗余和无关信息导致效率低下，且未能考虑到视频问答中不同层次的细节需求。为此，我们推出了VideoTree，一种结合LLMs的查询自适应和分层长视频理解框架。VideoTree能动态提取视频中与查询相关的信息，并构建一个树状结构以供LLM推理。首先，它通过视觉特征聚类和查询相关性评分，智能选择帧进行标题化。接着，将这些聚类组织成一个分层的树结构，确保相关段落的高分辨率。最后，通过遍历关键帧并利用LLM回答者，VideoTree生成答案。实验证明，VideoTree在准确性和效率上均优于现有方法，在三大基准测试中分别提升了7.0%、2.2%和2.7%的准确性，同时推理时间减少了40%。
>
> https://arxiv.org/abs/2405.19209

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19209/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19209/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19209/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19209/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19209/x5.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.19209](https://arxiv.org/abs/2405.19209)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886