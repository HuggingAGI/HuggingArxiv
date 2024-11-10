# 细粒度的检索器指导：在检索增强生成中利用大型语言模型的反馈

发布时间：2024年11月06日

`RAG` `信息检索`

> Fine-Grained Guidance for Retrievers: Leveraging LLMs' Feedback in Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）已被证明是缓解大型语言模型（LLM）中固有的幻觉问题的有效方法。以前的方法通常基于语义相似性训练检索器，缺乏对 RAG 的优化。最近的工作提出了使检索器与 LLM 的偏好信号对齐。然而，这些偏好信号对于通常语言能力较弱的密集检索器来说往往难以有效理解和学习。从像引导发现学习这样的教学理论中获得灵感，我们提出了一个新的框架，FiGRet（检索器的细粒度指导），它利用 LLM 的语言能力从更细粒度、以信息为中心的角度构建示例来指导检索器的学习。具体来说，我们的方法利用 LLM 从检索器表现不佳的样本中构建易于理解的示例，重点关注与 RAG 场景高度相关的三个学习目标：相关性、全面性和纯度。这些示例作为支架，最终使检索器与 LLM 的偏好对齐。此外，我们采用双重课程学习策略，并利用 LLM 和检索器之间的相互反馈来进一步提高 RAG 系统的性能。一系列实验表明，我们提出的框架提高了配备不同检索器的 RAG 系统的性能，并且适用于各种 LLM。

> Retrieval-Augmented Generation (RAG) has proven to be an effective method for mitigating hallucination issues inherent in large language models (LLMs). Previous approaches typically train retrievers based on semantic similarity, lacking optimization for RAG. More recent works have proposed aligning retrievers with the preference signals of LLMs. However, these preference signals are often difficult for dense retrievers, which typically have weaker language capabilities, to understand and learn effectively. Drawing inspiration from pedagogical theories like Guided Discovery Learning, we propose a novel framework, FiGRet (Fine-grained Guidance for Retrievers), which leverages the language capabilities of LLMs to construct examples from a more granular, information-centric perspective to guide the learning of retrievers. Specifically, our method utilizes LLMs to construct easy-to-understand examples from samples where the retriever performs poorly, focusing on three learning objectives highly relevant to the RAG scenario: relevance, comprehensiveness, and purity. These examples serve as scaffolding to ultimately align the retriever with the LLM's preferences. Furthermore, we employ a dual curriculum learning strategy and leverage the reciprocal feedback between LLM and retriever to further enhance the performance of the RAG system. A series of experiments demonstrate that our proposed framework enhances the performance of RAG systems equipped with different retrievers and is applicable to various LLMs.

[Arxiv](https://arxiv.org/abs/2411.03957)