# 采用多单元解码器结合互学习技术，提升表格结构和字符识别的准确性。

发布时间：2024年04月20日

`分类：LLM应用

这篇论文讨论了如何将表格内容提取并转换成大型语言模型可处理的格式，以及提出了一种多单元格内容解码器和双向互学习机制来优化端到端识别方法。这些内容与大型语言模型（LLM）的应用相关，因此将其归类为LLM应用。` `信息提取`

> Multi-Cell Decoder and Mutual Learning for Table Structure and Character Recognition

# 摘要

> 将科学论文、财务报告等文档中的表格内容提取并转换成大型语言模型可处理的格式，对于知识信息处理至关重要。采用端到端识别方法，不仅识别表格结构，还识别单元格内容，其性能已达到与外部字符识别系统相媲美的水平，并展现出提升空间。这些模型通过引入局部注意力机制，能够识别拥有数百单元格的长表格。不过，模型在识别表格结构时是单向的，从标题至页脚，且每个单元格内容的识别是独立进行，无法从邻近单元格中获取信息。本文提出了一种多单元格内容解码器和双向互学习机制，以优化端到端识别方法。在两大数据集上的测试显示，该方法有效，且对于长表格，即使单元格数量众多，其性能也能与业界顶尖模型相提并论。

> Extracting table contents from documents such as scientific papers and financial reports and converting them into a format that can be processed by large language models is an important task in knowledge information processing. End-to-end approaches, which recognize not only table structure but also cell contents, achieved performance comparable to state-of-the-art models using external character recognition systems, and have potential for further improvements. In addition, these models can now recognize long tables with hundreds of cells by introducing local attention. However, the models recognize table structure in one direction from the header to the footer, and cell content recognition is performed independently for each cell, so there is no opportunity to retrieve useful information from the neighbor cells. In this paper, we propose a multi-cell content decoder and bidirectional mutual learning mechanism to improve the end-to-end approach. The effectiveness is demonstrated on two large datasets, and the experimental results show comparable performance to state-of-the-art models, even for long tables with large numbers of cells.

![采用多单元解码器结合互学习技术，提升表格结构和字符识别的准确性。](../../../paper_images/2404.13268/x1.png)

![采用多单元解码器结合互学习技术，提升表格结构和字符识别的准确性。](../../../paper_images/2404.13268/x2.png)

![采用多单元解码器结合互学习技术，提升表格结构和字符识别的准确性。](../../../paper_images/2404.13268/x3.png)

[Arxiv](https://arxiv.org/abs/2404.13268)