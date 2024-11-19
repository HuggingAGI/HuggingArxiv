# GLDesigner：借助多模态大型语言模型充当设计师，以优化美学文本字形布局

发布时间：2024年11月18日

`LLM应用`

> GLDesigner: Leveraging Multi-Modal LLMs as Designer for Enhanced Aesthetic Text Glyph Layouts

# 摘要

> 文本标志设计极大地仰仗专业设计师的创造力与专业水准，其中元素布局安排是最为关键的步骤之一。然而，这个需要兼顾精准纹理细节和用户约束的特定任务鲜有关注，人们更多聚焦于诸如文档/海报布局生成这类更宽泛的任务。在本文中，我们提出了一个基于 VLM 的框架，它融合多模态输入与用户约束来生成具有内容感知能力的文本标志布局，为实际应用提供更灵活且稳定的布局设计。我们引入了两种模型技术，以减少同时处理多个字形图像的计算量，且不会导致性能降低。为支持模型的指令调整，我们构建了两个大规模的文本标志数据集，规模是现有公共数据集的 5 倍。除了几何注释（如文本掩码和字符识别），我们还补充了自然语言格式的全面布局描述，以便在处理复杂布局和自定义用户约束时进行更高效的训练，从而具备推理能力。实验研究表明，在评估几何美学和人类偏好的各种基准测试中，与先前方法相比，我们提出的模型和数据集是有效的。代码和数据集将会公开。

> Text logo design heavily relies on the creativity and expertise of professional designers, in which arranging element layouts is one of the most important procedures. However, few attention has been paid to this specific task which needs to take precise textural details and user constraints into consideration, but only on the broader tasks such as document/poster layout generation. In this paper, we propose a VLM-based framework that generates content-aware text logo layouts by integrating multi-modal inputs with user constraints, supporting a more flexible and stable layout design in real-world applications. We introduce two model techniques to reduce the computation for processing multiple glyph images simultaneously, while does not face performance degradation. To support instruction-tuning of out model, we construct two extensive text logo datasets, which are 5x more larger than the existing public dataset. Except for the geometric annotations (e.g. text masks and character recognition), we also compliment with comprehensive layout descriptions in natural language format, for more effective training to have reasoning ability when dealing with complex layouts and custom user constraints. Experimental studies demonstrate the effectiveness of our proposed model and datasets, when comparing with previous methods in various benchmarks to evaluate geometric aesthetics and human preferences. The code and datasets will be publicly available.

[Arxiv](https://arxiv.org/abs/2411.11435)