# μgat 技术通过融入多页上下文，显著提升了单页文档的解析质量。

发布时间：2024年08月28日

`LLM应用` `数字人文` `文档解析`

> μgat: Improving Single-Page Document Parsing by Providing Multi-Page Context

# 摘要

> Regesta，作为其他文件摘要的目录，有时是了解这些完整文件内容的唯一途径，因此备受社会和人文领域学者的关注。本研究聚焦于庞大的教皇登记册集合——Regesta Pontificum Romanum。这些视觉丰富的多页文档，其布局与文本内容同等重要，通过结构传递信息。在数字人文领域，文档解析技术崭露头角，旨在将扫描文档转化为机器可读的结构化形式，助力学者高效利用这些资源。然而，现有模型多聚焦于科学和商业文档，且大多仅处理单页文档。为此，我们提出 μgat，作为 Nougat 架构的扩展，能处理跨页元素，通过整合前后页内容来解析当前页。实验证明，这一方法在处理复杂的 Regesta Pontificum Romanorum 时同样有效。

> Regesta are catalogs of summaries of other documents and, in some cases, are the only source of information about the content of such full-length documents. For this reason, they are of great interest to scholars in many social and humanities fields. In this work, we focus on Regesta Pontificum Romanum, a large collection of papal registers. Regesta are visually rich documents, where the layout is as important as the text content to convey the contained information through the structure, and are inherently multi-page documents. Among Digital Humanities techniques that can help scholars efficiently exploit regesta and other documental sources in the form of scanned documents, Document Parsing has emerged as a task to process document images and convert them into machine-readable structured representations, usually markup language. However, current models focus on scientific and business documents, and most of them consider only single-paged documents. To overcome this limitation, in this work, we propose μgat, an extension of the recently proposed Document parsing Nougat architecture, which can handle elements spanning over the single page limits. Specifically, we adapt Nougat to process a larger, multi-page context, consisting of the previous and the following page, while parsing the current page. Experimental results, both qualitative and quantitative, demonstrate the effectiveness of our proposed approach also in the case of the challenging Regesta Pontificum Romanorum.

[Arxiv](https://arxiv.org/abs/2408.15646)