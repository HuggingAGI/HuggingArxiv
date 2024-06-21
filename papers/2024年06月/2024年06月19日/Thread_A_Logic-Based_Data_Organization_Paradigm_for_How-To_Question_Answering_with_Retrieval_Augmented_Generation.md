# 探讨：逻辑驱动的数据架构，专为“如何做”问答系统设计，通过检索增强生成技术优化答案生成。

发布时间：2024年06月19日

`RAG

理由：论文摘要中提到的“Thread”是一种创新的数据组织方式，它通过文档间的互联性构建逻辑单元，以提升处理非事实性“如何做”查询的效率。这种数据组织方式和增强问题回答系统的能力，与RAG（Retrieval-Augmented Generation）模型的概念相吻合，后者通常用于结合检索和生成技术来改善语言模型的性能，尤其是在需要详细解释和步骤的问题回答场景中。因此，这篇论文更适合归类到RAG分类中。` `问答系统` `工业自动化`

> Thread: A Logic-Based Data Organization Paradigm for How-To Question Answering with Retrieval Augmented Generation

# 摘要

> 当前的问题回答系统虽在事实性问题上表现出色，但在应对需要详细步骤和解释的非事实性“如何做”查询时显得力不从心。本文推出的Thread，一种创新的数据组织方式，通过文档间的互联性构建逻辑单元，已在多个领域和工业场景中证明其优越性，大幅提升了处理此类问题的效率。

> Current question answering systems leveraging retrieval augmented generation perform well in answering factoid questions but face challenges with non-factoid questions, particularly how-to queries requiring detailed step-by-step instructions and explanations. In this paper, we introduce Thread, a novel data organization paradigm that transforms documents into logic units based on their inter-connectivity. Extensive experiments across open-domain and industrial scenarios demonstrate that Thread outperforms existing data organization paradigms in RAG-based QA systems, significantly improving the handling of how-to questions.

![探讨：逻辑驱动的数据架构，专为“如何做”问答系统设计，通过检索增强生成技术优化答案生成。](../../../paper_images/2406.13372/x1.png)

![探讨：逻辑驱动的数据架构，专为“如何做”问答系统设计，通过检索增强生成技术优化答案生成。](../../../paper_images/2406.13372/x2.png)

![探讨：逻辑驱动的数据架构，专为“如何做”问答系统设计，通过检索增强生成技术优化答案生成。](../../../paper_images/2406.13372/x3.png)

![探讨：逻辑驱动的数据架构，专为“如何做”问答系统设计，通过检索增强生成技术优化答案生成。](../../../paper_images/2406.13372/x4.png)

[Arxiv](https://arxiv.org/abs/2406.13372)