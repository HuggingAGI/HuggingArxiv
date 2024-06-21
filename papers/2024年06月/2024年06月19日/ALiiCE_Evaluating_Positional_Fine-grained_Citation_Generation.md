# ALiiCE：细粒度位置引用生成的评估研究

发布时间：2024年06月19日

`LLM应用

这篇论文介绍了ALiiCE，一个针对细粒度引用生成的自动评估框架，它专注于大型语言模型（LLMs）在生成带有引用的文本时的性能评估。这个框架特别关注于句子中任意位置的细粒度引用的重要性，并通过依赖分析将句子声明分解为原子声明，评估原子级别的引用质量。ALiiCE引入了新的评估指标来衡量细粒度引用的召回率、精确率及引用位置的变异系数。这项工作是在LLMs的应用层面进行的，特别是在提升文本的可信度和可验证性方面，因此属于LLM应用分类。` `评估框架`

> ALiiCE: Evaluating Positional Fine-grained Citation Generation

# 摘要

> 大型语言模型（LLMs）通过生成带有引用的文本，提升了文本的可信度和可验证性。但目前的方法多关注句子级别的陈述，忽略了句子中任意位置可能出现的位置细粒度引用的重要性。为此，我们推出了ALiiCE，首个针对细粒度引用生成的自动评估框架。该框架通过依赖分析将句子声明分解为原子声明，并评估原子级别的引用质量。ALiiCE创新性地引入了三个评估指标，包括位置细粒度引用的召回率、精确率及引用位置的变异系数。我们在两个长篇QA数据集上测试了多个LLMs的细粒度引用生成能力，实验结果验证了ALiiCE的有效性，并指出当前LLMs在生成位置细粒度引用方面仍有挑战。

> Large Language Models (LLMs) can enhance the credibility and verifiability by generating text with citations. However, existing tasks and evaluation methods are predominantly limited to sentence-level statement, neglecting the significance of positional fine-grained citations that can appear anywhere within sentences. To facilitate further exploration of the fine-grained citation generation, we propose ALiiCE, the first automatic evaluation framework for this task. Our framework first parses the sentence claim into atomic claims via dependency analysis and then calculates citation quality at the atomic claim level. ALiiCE introduces three novel metrics for positional fined-grained citation quality assessment, including positional fine-grained citation recall and precision, and coefficient of variation of citation positions. We evaluate the positional fine-grained citation generation performance of several LLMs on two long-form QA datasets. Our experiments and analyses demonstrate the effectiveness and reasonableness of ALiiCE. The results also indicate that existing LLMs still struggle to provide positional fine-grained citations.

![ALiiCE：细粒度位置引用生成的评估研究](../../../paper_images/2406.13375/x1.png)

![ALiiCE：细粒度位置引用生成的评估研究](../../../paper_images/2406.13375/x2.png)

![ALiiCE：细粒度位置引用生成的评估研究](../../../paper_images/2406.13375/x3.png)

![ALiiCE：细粒度位置引用生成的评估研究](../../../paper_images/2406.13375/x4.png)

![ALiiCE：细粒度位置引用生成的评估研究](../../../paper_images/2406.13375/x5.png)

![ALiiCE：细粒度位置引用生成的评估研究](../../../paper_images/2406.13375/x6.png)

![ALiiCE：细粒度位置引用生成的评估研究](../../../paper_images/2406.13375/x7.png)

![ALiiCE：细粒度位置引用生成的评估研究](../../../paper_images/2406.13375/x8.png)

![ALiiCE：细粒度位置引用生成的评估研究](../../../paper_images/2406.13375/x9.png)

![ALiiCE：细粒度位置引用生成的评估研究](../../../paper_images/2406.13375/x10.png)

![ALiiCE：细粒度位置引用生成的评估研究](../../../paper_images/2406.13375/x11.png)

![ALiiCE：细粒度位置引用生成的评估研究](../../../paper_images/2406.13375/x12.png)

![ALiiCE：细粒度位置引用生成的评估研究](../../../paper_images/2406.13375/x13.png)

[Arxiv](https://arxiv.org/abs/2406.13375)