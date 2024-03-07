# [本研究旨在从全文档中精准抽提聚合物纳米复合材料样本信息，以深入探究其特性与应用。](https://arxiv.org/abs/2403.00260)

发布时间：2024年02月29日

`LLM应用`

> Extracting Polymer Nanocomposite Samples from Full-Length Documents

> 本研究关注如何运用LLMs从完整材料科学论文中精准抽提PNC样品信息，鉴于PNC样品属性在文中分布散乱、详尽标注难度大，导致传统文档级关系抽取方法因难以构建全面的实体标注而无法实施。针对此难题，我们创新性地提出了一项新基准及评估技术，并以零样本学习的方式探究了多种提示策略，同时融入自洽性以优化效果。尽管如此，即使是最先进的LLMs，在实现从单篇论文中全面提取样品信息上仍显力有未逮。最后，我们将实践中遇到的错误进行了分类总结，归纳出三大核心挑战，并对未来研究可能采用的应对策略展开了讨论。

> This paper investigates the use of large language models (LLMs) for extracting sample lists of polymer nanocomposites (PNCs) from full-length materials science research papers. The challenge lies in the complex nature of PNC samples, which have numerous attributes scattered throughout the text. The complexity of annotating detailed information on PNCs limits the availability of data, making conventional document-level relation extraction techniques impractical due to the challenge in creating comprehensive named entity span annotations. To address this, we introduce a new benchmark and an evaluation technique for this task and explore different prompting strategies in a zero-shot manner. We also incorporate self-consistency to improve the performance. Our findings show that even advanced LLMs struggle to extract all of the samples from an article. Finally, we analyze the errors encountered in this process, categorizing them into three main challenges, and discuss potential strategies for future research to overcome them.