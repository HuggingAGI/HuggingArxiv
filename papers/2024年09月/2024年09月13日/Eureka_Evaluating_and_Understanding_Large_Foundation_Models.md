# Eureka：探索与理解巨型基础模型

发布时间：2024年09月13日

`LLM理论` `人工智能`

> Eureka: Evaluating and Understanding Large Foundation Models

# 摘要

> 在人工智能领域，严格且可重复的评估是推动科学进步的关键。然而，由于基准饱和、测量方法不透明、生成任务测量困难以及全面比较所需能力众多等原因，评估实践充满挑战。为此，我们提出了三大贡献：首先，Eureka开源框架，超越单一分数，标准化大型基础模型的评估；其次，Eureka-Bench，一个测试前沿模型仍感困难及被忽视基本能力的可扩展基准集合；最后，通过Eureka分析12个前沿模型，深入剖析失败原因及模型差异，助力针对性改进。与近期强调单一最佳模型的趋势不同，我们发现不同模型各有所长，某些模型在特定能力上表现尤为突出。尽管模型有所进步，但在图像理解、多模态输入利用、信息检索实际性及过度拒绝等方面仍需努力。

> Rigorous and reproducible evaluation is critical for assessing the state of the art and for guiding scientific advances in Artificial Intelligence. Evaluation is challenging in practice due to several reasons, including benchmark saturation, lack of transparency in methods used for measurement, development challenges in extracting measurements for generative tasks, and, more generally, the extensive number of capabilities required for a well-rounded comparison across models. We make three contributions to alleviate the above challenges. First, we present Eureka, an open-source framework for standardizing evaluations of large foundation models beyond single-score reporting and rankings. Second, we introduce Eureka-Bench as an extensible collection of benchmarks testing capabilities that (i) are still challenging for state-of-the-art models and (ii) represent fundamental but overlooked language and multimodal capabilities. The inherent space for improvement in non-saturated benchmarks enables us to discover meaningful differences between models at a capability level. Third, using Eureka, we conduct an analysis of 12 state-of-the-art models, providing in-depth insights into failure understanding and model comparison, which can be leveraged to plan targeted improvements. In contrast to recent trends in reports and leaderboards showing absolute rankings and claims for one model or another to be the best, our analysis shows that there is no such best model. Different models have different strengths, but there are models that appear more often than others as best performers for some capabilities. Despite the recent improvements, current models still struggle with several fundamental capabilities including detailed image understanding, benefiting from multimodal input when available rather than fully relying on language, factuality and grounding for information retrieval, and over refusals.

[Arxiv](https://arxiv.org/abs/2409.10566)