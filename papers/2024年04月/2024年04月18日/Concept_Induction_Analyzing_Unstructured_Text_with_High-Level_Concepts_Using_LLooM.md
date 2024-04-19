# 概念归纳：运用高级概念对非结构化文本进行分析的 LLooM技术

发布时间：2024年04月18日

`LLM应用` `数据分析` `文本分析`

> Concept Induction: Analyzing Unstructured Text with High-Level Concepts Using LLooM

# 摘要

> 数据分析师一直努力将杂乱无章的文本信息提炼为有深度的概念。常见的主题建模和聚类技术虽然侧重于关键词，却往往需要大量的解释工作。现在，我们引入了一种名为概念归纳的计算过程，它能够从非结构化文本中提炼出定义明确的高级概念。以一个包含有害网络评论的数据集为例，先进的BERTopic模型可能会提取出“女性、权力、女性”等词汇，而概念归纳则能进一步抽象出“对传统性别角色的批评”和“对女性问题的关注不足”等高级概念。我们设计了一种名为LLooM的概念归纳算法，该算法利用大型语言模型，通过迭代合成抽样文本，提出更具普遍性的、易于人类理解的概念。LLooM还被集成到一个混合主动性文本分析工具中，帮助分析师从繁琐的主题解释工作中解放出来，转而进行基于理论的深入分析。经过技术评估和多个分析场景的测试，我们发现LLooM在概念质量和数据覆盖率上都超越了传统的主题模型。在专家案例研究中，LLooM甚至能够揭示出熟悉数据集中的新见解，例如在一个政治社交媒体数据集中，它指出了之前未被注意到的对反对党立场的攻击行为。

> Data analysts have long sought to turn unstructured text data into meaningful concepts. Though common, topic modeling and clustering focus on lower-level keywords and require significant interpretative work. We introduce concept induction, a computational process that instead produces high-level concepts, defined by explicit inclusion criteria, from unstructured text. For a dataset of toxic online comments, where a state-of-the-art BERTopic model outputs "women, power, female," concept induction produces high-level concepts such as "Criticism of traditional gender roles" and "Dismissal of women's concerns." We present LLooM, a concept induction algorithm that leverages large language models to iteratively synthesize sampled text and propose human-interpretable concepts of increasing generality. We then instantiate LLooM in a mixed-initiative text analysis tool, enabling analysts to shift their attention from interpreting topics to engaging in theory-driven analysis. Through technical evaluations and four analysis scenarios ranging from literature review to content moderation, we find that LLooM's concepts improve upon the prior art of topic models in terms of quality and data coverage. In expert case studies, LLooM helped researchers to uncover new insights even from familiar datasets, for example by suggesting a previously unnoticed concept of attacks on out-party stances in a political social media dataset.

![概念归纳：运用高级概念对非结构化文本进行分析的 LLooM技术](../../../paper_images/2404.12259/x1.png)

![概念归纳：运用高级概念对非结构化文本进行分析的 LLooM技术](../../../paper_images/2404.12259/x2.png)

![概念归纳：运用高级概念对非结构化文本进行分析的 LLooM技术](../../../paper_images/2404.12259/x3.png)

![概念归纳：运用高级概念对非结构化文本进行分析的 LLooM技术](../../../paper_images/2404.12259/lloom_workbench.png)

![概念归纳：运用高级概念对非结构化文本进行分析的 LLooM技术](../../../paper_images/2404.12259/x4.png)

![概念归纳：运用高级概念对非结构化文本进行分析的 LLooM技术](../../../paper_images/2404.12259/x5.png)

![概念归纳：运用高级概念对非结构化文本进行分析的 LLooM技术](../../../paper_images/2404.12259/x6.png)

![概念归纳：运用高级概念对非结构化文本进行分析的 LLooM技术](../../../paper_images/2404.12259/x7.png)

![概念归纳：运用高级概念对非结构化文本进行分析的 LLooM技术](../../../paper_images/2404.12259/x8.png)

![概念归纳：运用高级概念对非结构化文本进行分析的 LLooM技术](../../../paper_images/2404.12259/x9.png)

![概念归纳：运用高级概念对非结构化文本进行分析的 LLooM技术](../../../paper_images/2404.12259/x10.png)

![概念归纳：运用高级概念对非结构化文本进行分析的 LLooM技术](../../../paper_images/2404.12259/x11.png)

![概念归纳：运用高级概念对非结构化文本进行分析的 LLooM技术](../../../paper_images/2404.12259/x12.png)

![概念归纳：运用高级概念对非结构化文本进行分析的 LLooM技术](../../../paper_images/2404.12259/x13.png)

![概念归纳：运用高级概念对非结构化文本进行分析的 LLooM技术](../../../paper_images/2404.12259/x14.png)

![概念归纳：运用高级概念对非结构化文本进行分析的 LLooM技术](../../../paper_images/2404.12259/x15.png)

![概念归纳：运用高级概念对非结构化文本进行分析的 LLooM技术](../../../paper_images/2404.12259/x16.png)

![概念归纳：运用高级概念对非结构化文本进行分析的 LLooM技术](../../../paper_images/2404.12259/x17.png)

![概念归纳：运用高级概念对非结构化文本进行分析的 LLooM技术](../../../paper_images/2404.12259/x18.png)

[Arxiv](https://arxiv.org/abs/2404.12259)