# ECLIPSE：跨语言工业日志解析的语义熵-最长公共子序列方法

发布时间：2024年05月22日

`LLM应用

理由：这篇论文主要介绍了ECLIPSE系统，这是一种利用大型语言模型（LLM）的强大语义理解能力来增强跨语言工业日志解析的系统。论文中提到的技术应用，如利用语义熵-最长公共子序列技术和Faiss索引，以及结合LLM的能力来提取日志关键词语义，都是具体应用LLM技术来解决实际工业问题。因此，这篇论文属于LLM应用类别。` `工业日志处理` `跨语言技术`

> ECLIPSE: Semantic Entropy-LCS for Cross-Lingual Industrial Log Parsing

# 摘要

> 日志解析在从学术领域转向工业应用时遭遇重大挑战，尽管现有解析器在标准化数据集上表现优异，但在处理真实工业日志的庞大规模和多样性时却力不从心。主要挑战包括：1）海量日志模板：随着日志量的激增，多数解析器的效率和性能大打折扣；2）语义复杂多变：传统模板匹配算法难以应对工业日志的复杂性，尤其是无法跨语言解析相似语义的日志。为此，我们开发了ECLIPSE，一种增强型跨语言工业日志解析系统，利用语义熵-最长公共子序列技术，有效应对跨语言日志解析。ECLIPSE不仅融合了两种高效的数据驱动模板匹配算法和Faiss索引，还借助大型语言模型的强大语义理解能力，精准提取日志关键词语义，大幅缩小检索范围。此外，我们推出了中英文跨平台工业日志解析基准ECLIPSE-Bench，用以检验主流解析器在实际工业环境中的表现。实验结果显示，ECLIPSE在公共及专有数据集上均展现出卓越性能和稳健性，尤其在与多样数据集上的顶尖基线对比时，不仅性能领先，处理效率也显著占优。

> Log parsing, a vital task for interpreting the vast and complex data produced within software architectures faces significant challenges in the transition from academic benchmarks to the industrial domain. Existing log parsers, while highly effective on standardized public datasets, struggle to maintain performance and efficiency when confronted with the sheer scale and diversity of real-world industrial logs. These challenges are two-fold: 1) massive log templates: The performance and efficiency of most existing parsers will be significantly reduced when logs of growing quantities and different lengths; 2) Complex and changeable semantics: Traditional template-matching algorithms cannot accurately match the log templates of complicated industrial logs because they cannot utilize cross-language logs with similar semantics. To address these issues, we propose ECLIPSE, Enhanced Cross-Lingual Industrial log Parsing with Semantic Entropy-LCS, since cross-language logs can robustly parse industrial logs. On the one hand, it integrates two efficient data-driven template-matching algorithms and Faiss indexing. On the other hand, driven by the powerful semantic understanding ability of the Large Language Model (LLM), the semantics of log keywords were accurately extracted, and the retrieval space was effectively reduced. It is worth noting that we launched a Chinese and English cross-platform industrial log parsing benchmark ECLIPSE-Bench to evaluate the performance of mainstream parsers in industrial scenarios. Our experimental results, conducted across public benchmarks and the proprietary ECLIPSE-Bench dataset, underscore the superior performance and robustness of our proposed ECLIPSE. Notably, ECLIPSE delivers state-of-the-art performance when compared to strong baselines on diverse datasets and preserves a significant edge in processing efficiency.

[Arxiv](https://arxiv.org/abs/2405.13548)