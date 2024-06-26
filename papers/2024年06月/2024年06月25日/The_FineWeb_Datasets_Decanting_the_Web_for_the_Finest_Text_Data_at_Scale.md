# FineWeb 数据集：精选网络，规模化提炼最优质文本数据

发布时间：2024年06月25日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLM）的预训练数据集的质量和规模对其性能的影响，并介绍了FineWeb数据集的设计和分析过程。这些内容更偏向于LLM的理论研究，特别是关于预训练数据集的构建和优化，而不是具体的应用、Agent行为或RAG（Retrieval-Augmented Generation）技术。因此，将其归类为LLM理论是合适的。`

> The FineWeb Datasets: Decanting the Web for the Finest Text Data at Scale

# 摘要

> 大型语言模型（LLM）的性能深受其预训练数据集的质量和规模影响。然而，诸如Llama 3和Mixtral等顶尖开源LLM的预训练数据集并未公开，其构建细节鲜为人知。本研究中，我们推出了FineWeb，一个基于96个Common Crawl快照、包含15万亿token的数据集，其训练出的LLM性能超越其他开源数据集。为探究如何高效策划高质量预训练数据集，我们详尽记录并分析了FineWeb的设计决策，涵盖去重与过滤策略的深入探讨。此外，我们还推出了FineWeb-Edu，一个精选自FineWeb、包含1.3万亿token的教育文本集。在FineWeb-Edu上预训练的LLM在MMLU和ARC等知识与推理密集型测试中表现卓越。我们不仅公开了数据集，还发布了数据处理代码库及消融实验中训练的所有模型。

> The performance of a large language model (LLM) depends heavily on the quality and size of its pretraining dataset. However, the pretraining datasets for state-of-the-art open LLMs like Llama 3 and Mixtral are not publicly available and very little is known about how they were created. In this work, we introduce FineWeb, a 15-trillion token dataset derived from 96 Common Crawl snapshots that produces better-performing LLMs than other open pretraining datasets. To advance the understanding of how best to curate high-quality pretraining datasets, we carefully document and ablate all of the design choices used in FineWeb, including in-depth investigations of deduplication and filtering strategies. In addition, we introduce FineWeb-Edu, a 1.3-trillion token collection of educational text filtered from FineWeb. LLMs pretrained on FineWeb-Edu exhibit dramatically better performance on knowledge- and reasoning-intensive benchmarks like MMLU and ARC. Along with our datasets, we publicly release our data curation codebase and all of the models trained during our ablation experiments.

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/x1.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/x2.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/x3.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/x4.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/x5.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/x6.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/x7.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/x8.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/x9.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/x10.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/x11.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/x12.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/x13.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/x14.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/x15.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/x16.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/gender_piechart.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/edu-gender_piechart.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/age_piechart.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/edu-age_piechart.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/religion_piechart.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/edu-religion_piechart.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/non-binary_tfidf.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/woman_tfidf.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/man_tfidf.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/atheist_tfidf.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/buddhist_tfidf.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/christian_tfidf.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/muslim_tfidf.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/jewish_tfidf.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/hindu_tfidf.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/old_tfidf.png)

![FineWeb 数据集：精选网络，规模化提炼最优质文本数据](../../../paper_images/2406.17557/young_tfidf.png)

[Arxiv](https://arxiv.org/abs/2406.17557)