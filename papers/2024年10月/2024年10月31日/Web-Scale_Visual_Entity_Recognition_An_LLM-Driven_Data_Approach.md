# Web 规模的视觉实体识别：一种由 LLM 驱动的数据方法

发布时间：2024年10月31日

`LLM应用` `视觉识别` `数据标注`

> Web-Scale Visual Entity Recognition: An LLM-Driven Data Approach

# 摘要

> Web-scale 视觉实体识别，也就是在类似维基百科这样的庞大知识库中把图像和其对应的实体相联系的任务，因缺少干净的大规模训练数据而面临严峻挑战。在本文里，我们提出了一种全新的方法来整理这样的数据集，借助多模态大型语言模型（LLM）进行标签验证、元数据生成以及理由阐释。我们发现让多模态 LLM 直接标注数据效果不佳，而是引导它通过获取额外的上下文相关信息（比如维基百科）来推断潜在的候选实体标签，从而得到更精准的标注。我们还进一步利用多模态 LLM 生成问答对以及能解释图像和所分配实体之间联系的基于基础的细粒度文本描述（称作“理由”），以此丰富数据集。实验表明，基于这个自动整理的数据训练的模型在 Web-scale 视觉实体识别任务中达到了领先水平（例如，在 OVEN 实体任务中提升了 +6.9%），凸显了该领域中高质量训练数据的重要性。

> Web-scale visual entity recognition, the task of associating images with their corresponding entities within vast knowledge bases like Wikipedia, presents significant challenges due to the lack of clean, large-scale training data. In this paper, we propose a novel methodology to curate such a dataset, leveraging a multimodal large language model (LLM) for label verification, metadata generation, and rationale explanation. Instead of relying on the multimodal LLM to directly annotate data, which we found to be suboptimal, we prompt it to reason about potential candidate entity labels by accessing additional contextually relevant information (such as Wikipedia), resulting in more accurate annotations. We further use the multimodal LLM to enrich the dataset by generating question-answer pairs and a grounded finegrained textual description (referred to as "rationale") that explains the connection between images and their assigned entities. Experiments demonstrate that models trained on this automatically curated data achieve state-of-the-art performance on web-scale visual entity recognition tasks (e.g. +6.9% improvement in OVEN entity task), underscoring the importance of high-quality training data in this domain.

[Arxiv](https://arxiv.org/abs/2410.23676)