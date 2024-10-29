# CTINEXUS：利用优化的大型语言模型的上下文学习在数据稀缺的情况下构建网络安全知识图谱

发布时间：2024年10月28日

`LLM应用` `网络安全` `知识图谱`

> CTINEXUS: Leveraging Optimized LLM In-Context Learning for Constructing Cybersecurity Knowledge Graphs Under Data Scarcity

# 摘要

> 网络威胁情报（CTI）报告中的文本描述，如安全文章和新闻，是有关网络威胁的丰富知识来源，对于组织了解迅速变化的威胁形势至关重要。然而，当前的 CTI 提取方法缺乏灵活性和通用性，常常导致知识提取不准确和不完整。语法解析依赖于固定的规则和词典，而模型微调需要大量的标注数据集，这使得两种模式都难以适应新的威胁和本体。为了弥补这一差距，我们提出了 CTINexus，这是一个新颖的框架，利用大型语言模型（LLM）的优化上下文学习（ICL）来进行数据高效的 CTI 知识提取和高质量的网络安全知识图谱（CSKG）构建。与现有方法不同，CTINexus 既不需要大量数据也不需要参数调整，并且可以通过最少的标注示例适应各种本体。这是通过（1）精心设计的具有最佳示范检索的自动提示构建策略，用于提取各种网络安全实体和关系；（2）分层实体对齐技术，对提取的知识进行规范化并消除冗余；（3）ICL 增强的长距离关系预测技术，以进一步用缺失的链接完成 CKSG 来实现的。我们使用从 10 个平台收集的 150 份真实世界的 CTI 报告进行的广泛评估表明，CTINexus 在构建准确和完整的 CSKG 方面明显优于现有方法，突出了其通过高效和适应性强的解决方案改变 CTI 分析以应对动态威胁形势的潜力。

> Textual descriptions in cyber threat intelligence (CTI) reports, such as security articles and news, are rich sources of knowledge about cyber threats, crucial for organizations to stay informed about the rapidly evolving threat landscape. However, current CTI extraction methods lack flexibility and generalizability, often resulting in inaccurate and incomplete knowledge extraction. Syntax parsing relies on fixed rules and dictionaries, while model fine-tuning requires large annotated datasets, making both paradigms challenging to adapt to new threats and ontologies. To bridge the gap, we propose CTINexus, a novel framework leveraging optimized in-context learning (ICL) of large language models (LLMs) for data-efficient CTI knowledge extraction and high-quality cybersecurity knowledge graph (CSKG) construction. Unlike existing methods, CTINexus requires neither extensive data nor parameter tuning and can adapt to various ontologies with minimal annotated examples. This is achieved through (1) a carefully designed automatic prompt construction strategy with optimal demonstration retrieval for extracting a wide range of cybersecurity entities and relations; (2) a hierarchical entity alignment technique that canonicalizes the extracted knowledge and removes redundancy; (3) an ICL-enhanced long-distance relation prediction technique to further complete the CKSG with missing links. Our extensive evaluations using 150 real-world CTI reports collected from 10 platforms demonstrate that CTINexus significantly outperforms existing methods in constructing accurate and complete CSKGs, highlighting its potential to transform CTI analysis with an efficient and adaptable solution for the dynamic threat landscape.

[Arxiv](https://arxiv.org/abs/2410.21060)