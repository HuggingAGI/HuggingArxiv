# ARL2 方法旨在通过自我指导适应性相关性标注技术，实现对黑盒式大型语言模型检索器的精准对齐，以提升其性能。

发布时间：2024年02月21日

`RAG`

> ARL2: Aligning Retrievers for Black-box Large Language Models via Self-guided Adaptive Relevance Labeling

# 摘要

> 检索增强生成技术通过汲取外部知识源内容，成功赋能大型语言模型(LLMs)，使其在特定领域更具适应性，并有效抑制了知识密集任务中的臆想现象。不过，当前的检索器因独立训练及LLMs的黑盒属性，常常与其不够协调一致。为此，我们创新性地推出了ARL2，这是一种以LLMs充当标签提供者的检索学习方案。ARL2巧妙运用LLMs对相关证据进行标注和打分，借由强大LLMs的监督作用训练检索器。更进一步，ARL2采用灵活的自适应自我训练策略，筛选出高质量且多样性的关联数据集，极大程度减少了标注成本。大量实验证明了ARL2的卓越效果，在NQ基准测试中比现有最先进方法提高了5.4%的准确性，在MMLU测试上提高了4.6%。而且，ARL2展现出稳健的迁移学习能力和极强的零样本泛化能力。我们的代码将会发布于GitHub地址：<https://github.com/zhanglingxi-cs/ARL2>。

> Retrieval-augmented generation enhances large language models (LLMs) by incorporating relevant information from external knowledge sources. This enables LLMs to adapt to specific domains and mitigate hallucinations in knowledge-intensive tasks. However, existing retrievers are often misaligned with LLMs due to their separate training processes and the black-box nature of LLMs. To address this challenge, we propose ARL2, a retriever learning technique that harnesses LLMs as labelers. ARL2 leverages LLMs to annotate and score relevant evidence, enabling learning the retriever from robust LLM supervision. Furthermore, ARL2 uses an adaptive self-training strategy for curating high-quality and diverse relevance data, which can effectively reduce the annotation cost. Extensive experiments demonstrate the effectiveness of ARL2, achieving accuracy improvements of 5.4% on NQ and 4.6% on MMLU compared to the state-of-the-art methods. Additionally, ARL2 exhibits robust transfer learning capabilities and strong zero-shot generalization abilities. Our code will be published at \url{https://github.com/zhanglingxi-cs/ARL2}.

[Arxiv](https://arxiv.org/abs/2402.13542)