# Multi-News+：利用大型语言模型实现高效数据集净化与注释

发布时间：2024年04月15日

`LLM应用` `数据集清洗` `自动文档分类`

> Multi-News+: Cost-efficient Dataset Cleansing via LLM-based Data Annotation

# 摘要

> 确保数据集的质量对于提升下游模型的性能和可靠性非常关键。但是，数据集在构建时常常会不小心掺入噪声。尽管已经有众多尝试通过人工注释者来解决这个问题，但这种方法成本高昂且耗时。因此，近期研究开始尝试利用大型语言模型（LLMs）来进行数据标注。我们在此提出了一项案例研究，通过LLM来执行数据标注，以提升现有数据集的质量，并采用一种净化策略。我们特别采用了链式思维（CoT）和多数表决等技术，模仿人类进行文档分类，剔除Multi-News数据集中的无关文档，该数据集常用于多文档摘要任务。通过这种创新的净化方法，我们推出了升级版的Multi-News+。利用LLMs进行数据清洗，我们证明了一种既经济又高效的提升数据集质量的方法，避免了对昂贵的人工标注的依赖。

> The quality of the dataset is crucial for ensuring optimal performance and reliability of downstream task models. However, datasets often contain noisy data inadvertently included during the construction process. Numerous attempts have been made to correct this issue through human annotators. However, hiring and managing human annotators is expensive and time-consuming. As an alternative, recent studies are exploring the use of large language models (LLMs) for data annotation.
  In this study, we present a case study that extends the application of LLM-based data annotation to enhance the quality of existing datasets through a cleansing strategy. Specifically, we leverage approaches such as chain-of-thought (CoT) and majority voting to imitate human annotation and classify unrelated documents from the Multi-News dataset, which is widely used for the multi-document summarization task. Through our proposed cleansing method, we introduce an enhanced Multi-News+. By employing LLMs for data cleansing, we demonstrate an efficient and effective approach to improving dataset quality without relying on expensive human annotation efforts.

![Multi-News+：利用大型语言模型实现高效数据集净化与注释](../../../paper_images/2404.09682/fig_framework.png)

![Multi-News+：利用大型语言模型实现高效数据集净化与注释](../../../paper_images/2404.09682/fig_histogram.png)

![Multi-News+：利用大型语言模型实现高效数据集净化与注释](../../../paper_images/2404.09682/fig_screenshot.png)

[Arxiv](https://arxiv.org/abs/2404.09682)