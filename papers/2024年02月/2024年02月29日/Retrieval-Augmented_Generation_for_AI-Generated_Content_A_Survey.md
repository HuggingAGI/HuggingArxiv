# 本篇综述聚焦于“检索增强生成”这一技术在AI生成内容领域的应用与发展，深度剖析了该技术如何通过整合检索与生成过程，提升AI内容创作的质量与智能性。

发布时间：2024年02月29日

`RAG`

> Retrieval-Augmented Generation for AI-Generated Content: A Survey

> 在模型算法优化、可扩展基础模型结构和丰富高质量数据集的支持下，AIGC领域蓬勃发展。然而，尽管成绩斐然，但AIGC仍需应对诸如保持实时和长尾知识更新、防范数据泄露及高昂训练推理成本等挑战。近期，一种名为检索增强生成（RAG）的新范式应运而生，它借助信息检索机制从海量数据源中抓取相关对象以改进AIGC效果，从而提升了准确度与稳定性。本文系统梳理了将RAG技术融入AIGC应用场景的各项研究成果。首先，我们将RAG的基础模型按照检索器如何赋能生成器的方式进行了分类，并精炼提取了各类检索器与生成器强化策略的核心理念。这一全景视角囊括了所有RAG情景，揭示推动未来发展的关键技术进展。另外，我们还汇总了优化RAG效能的附加方法，助力高效构建和部署RAG系统。再者，我们从多元模态和任务的角度探讨了RAG在实际应用中的广泛案例，为科研工作者和从业者提供宝贵的借鉴资源。不仅如此，我们还推出了RAG的基准评测标准，剖析了当前RAG系统的局限所在，并对未来研究趋势给出了前瞻性的指引。

> The development of Artificial Intelligence Generated Content (AIGC) has been facilitated by advancements in model algorithms, scalable foundation model architectures, and the availability of ample high-quality datasets. While AIGC has achieved remarkable performance, it still faces challenges, such as the difficulty of maintaining up-to-date and long-tail knowledge, the risk of data leakage, and the high costs associated with training and inference. Retrieval-Augmented Generation (RAG) has recently emerged as a paradigm to address such challenges. In particular, RAG introduces the information retrieval process, which enhances AIGC results by retrieving relevant objects from available data stores, leading to greater accuracy and robustness. In this paper, we comprehensively review existing efforts that integrate RAG technique into AIGC scenarios. We first classify RAG foundations according to how the retriever augments the generator. We distill the fundamental abstractions of the augmentation methodologies for various retrievers and generators. This unified perspective encompasses all RAG scenarios, illuminating advancements and pivotal technologies that help with potential future progress. We also summarize additional enhancements methods for RAG, facilitating effective engineering and implementation of RAG systems. Then from another view, we survey on practical applications of RAG across different modalities and tasks, offering valuable references for researchers and practitioners. Furthermore, we introduce the benchmarks for RAG, discuss the limitations of current RAG systems, and suggest potential directions for future research. Project: https://github.com/hymie122/RAG-Survey

[Arxiv](https://arxiv.org/abs/2402.19473)