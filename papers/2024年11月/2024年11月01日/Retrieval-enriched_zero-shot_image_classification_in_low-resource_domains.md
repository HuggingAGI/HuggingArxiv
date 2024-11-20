# 低资源领域中的检索增强式零样本图像分类

发布时间：2024年11月01日

`LLM应用` `图像分类` `低资源领域`

> Retrieval-enriched zero-shot image classification in low-resource domains

# 摘要

> 低资源领域，其特征为数据和注释匮乏，给语言和视觉理解任务带来巨大挑战，其中视觉理解任务在文献中的研究尤为不足。视觉语言模型（VLM）的最新进展在高资源领域成果喜人，但在预训练集中代表性欠缺的低资源概念（比如每个类别仅有少量图像）方面表现欠佳。我们从全新视角应对零样本低资源图像分类这一艰巨任务。借助基于检索的策略，我们以无需训练的方式达成目标。具体而言，我们的方法名为 CoRE（检索丰富组合），它通过从大型网络爬虫数据库中检索相关文本信息，来丰富查询图像和类别原型的表征。这种基于检索的丰富化操作，通过融入与特定类别相关的更广泛的上下文信息，显著提升了分类性能。我们在新设立的涵盖医学成像、稀有植物和电路等各类低资源领域的基准上验证了我们的方法。我们的实验表明，CORE 优于依赖合成数据生成和模型微调的现有前沿方法。

> Low-resource domains, characterized by scarce data and annotations, present significant challenges for language and visual understanding tasks, with the latter much under-explored in the literature. Recent advancements in Vision-Language Models (VLM) have shown promising results in high-resource domains but fall short in low-resource concepts that are under-represented (e.g. only a handful of images per category) in the pre-training set. We tackle the challenging task of zero-shot low-resource image classification from a novel perspective. By leveraging a retrieval-based strategy, we achieve this in a training-free fashion. Specifically, our method, named CoRE (Combination of Retrieval Enrichment), enriches the representation of both query images and class prototypes by retrieving relevant textual information from large web-crawled databases. This retrieval-based enrichment significantly boosts classification performance by incorporating the broader contextual information relevant to the specific class. We validate our method on a newly established benchmark covering diverse low-resource domains, including medical imaging, rare plants, and circuits. Our experiments demonstrate that CORE outperforms existing state-of-the-art methods that rely on synthetic data generation and model fine-tuning.

[Arxiv](https://arxiv.org/abs/2411.00988)