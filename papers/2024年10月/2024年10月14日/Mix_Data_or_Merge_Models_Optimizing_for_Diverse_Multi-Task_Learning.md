# 是混合数据还是合并模型？探讨如何优化多样化的多任务学习。

发布时间：2024年10月14日

`LLM应用` `人工智能` `多语言处理`

> Mix Data or Merge Models? Optimizing for Diverse Multi-Task Learning

# 摘要

> 全球广泛应用的大型语言模型 (LLM) 面临安全挑战。偏好训练和安全措施常过度适应西方数据集，难以扩展至多语言环境。我们探索多任务环境中的模型合并，结合多语言的安全与通用任务。每种语言带来独特的学习挑战。基于目标的合并比数据混合更有效，性能和安全性分别提升8%和10%。基于语言的合并也显著有效，单语言微调模型合并后，性能提升4%，危害减少7%。我们的研究为构建强大且安全的多语言模型提供了实用框架。

> Large Language Models (LLMs) have been adopted and deployed worldwide for a broad variety of applications. However, ensuring their safe use remains a significant challenge. Preference training and safety measures often overfit to harms prevalent in Western-centric datasets, and safety protocols frequently fail to extend to multilingual settings. In this work, we explore model merging in a diverse multi-task setting, combining safety and general-purpose tasks within a multilingual context. Each language introduces unique and varied learning challenges across tasks. We find that objective-based merging is more effective than mixing data, with improvements of up to 8% and 10% in general performance and safety respectively. We also find that language-based merging is highly effective -- by merging monolingually fine-tuned models, we achieve a 4% increase in general performance and 7% reduction in harm across all languages on top of the data mixtures method using the same available data. Overall, our comprehensive study of merging approaches provides a useful framework for building strong and safe multilingual models.

[Arxiv](https://arxiv.org/abs/2410.10801)