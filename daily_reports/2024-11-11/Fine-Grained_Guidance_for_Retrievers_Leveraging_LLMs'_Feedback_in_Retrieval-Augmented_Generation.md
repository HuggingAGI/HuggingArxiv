# 细粒度的检索器指导：在检索增强生成中利用大型语言模型的反馈
发布时间：2024年11月06日

`RAG`
> Fine-Grained Guidance for Retrievers: Leveraging LLMs' Feedback in Retrieval-Augmented Generation
>
> 检索增强生成（RAG）已被证明是缓解大型语言模型（LLM）中固有的幻觉问题的有效方法。以前的方法通常基于语义相似性训练检索器，缺乏对 RAG 的优化。最近的工作提出了使检索器与 LLM 的偏好信号对齐。然而，这些偏好信号对于通常语言能力较弱的密集检索器来说往往难以有效理解和学习。从像引导发现学习这样的教学理论中获得灵感，我们提出了一个新的框架，FiGRet（检索器的细粒度指导），它利用 LLM 的语言能力从更细粒度、以信息为中心的角度构建示例来指导检索器的学习。具体来说，我们的方法利用 LLM 从检索器表现不佳的样本中构建易于理解的示例，重点关注与 RAG 场景高度相关的三个学习目标：相关性、全面性和纯度。这些示例作为支架，最终使检索器与 LLM 的偏好对齐。此外，我们采用双重课程学习策略，并利用 LLM 和检索器之间的相互反馈来进一步提高 RAG 系统的性能。一系列实验表明，我们提出的框架提高了配备不同检索器的 RAG 系统的性能，并且适用于各种 LLM。
>
> https://arxiv.org/abs/2411.03957

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2411.03957](https://arxiv.org/abs/2411.03957)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)