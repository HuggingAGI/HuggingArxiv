# 大型语言模型：叙事驱动的推荐引擎

发布时间：2024年10月17日

`LLM应用` `电影推荐` `推荐系统`

> Large Language Models as Narrative-Driven Recommenders

# 摘要

> 叙事驱动的推荐系统旨在根据用户自由文本请求（如“我想看一部像《禁闭岛》那样情节曲折的心理惊悚片”）提供个性化建议。尽管大型语言模型（LLMs）在处理一般自然语言查询方面表现出色，但它们在推荐请求方面的应用仍未充分探索。为此，我们在电影推荐场景中对比了38个不同大小的开源和闭源LLMs（如LLama 3.2和GPT-4o）的性能。我们使用了reddit电影建议社区中由众包工作者标注的金标准数据集，并采用了零-shot、身份和少-shot等多种提示策略。结果显示，LLMs生成的电影推荐与上下文高度相关，显著优于其他最先进的方法，如doc2vec。虽然闭源和大型参数化模型表现最佳，但中等大小的开源模型也表现不俗，仅略逊于计算成本更高的模型。此外，大多数模型在提示策略上无显著差异，表明零-shot提示在叙事驱动推荐中同样有效。这项研究为推荐系统领域的研究人员和从业者提供了重要参考，帮助他们更好地将LLMs应用于实际推荐工具中。

> Narrative-driven recommenders aim to provide personalized suggestions for user requests expressed in free-form text such as "I want to watch a thriller with a mind-bending story, like Shutter Island." Although large language models (LLMs) have been shown to excel in processing general natural language queries, their effectiveness for handling such recommendation requests remains relatively unexplored. To close this gap, we compare the performance of 38 open- and closed-source LLMs of various sizes, such as LLama 3.2 and GPT-4o, in a movie recommendation setting. For this, we utilize a gold-standard, crowdworker-annotated dataset of posts from reddit's movie suggestion community and employ various prompting strategies, including zero-shot, identity, and few-shot prompting. Our findings demonstrate the ability of LLMs to generate contextually relevant movie recommendations, significantly outperforming other state-of-the-art approaches, such as doc2vec. While we find that closed-source and large-parameterized models generally perform best, medium-sized open-source models remain competitive, being only slightly outperformed by their more computationally expensive counterparts. Furthermore, we observe no significant differences across prompting strategies for most models, underscoring the effectiveness of simple approaches such as zero-shot prompting for narrative-driven recommendations. Overall, this work offers valuable insights for recommender system researchers as well as practitioners aiming to integrate LLMs into real-world recommendation tools.

[Arxiv](https://arxiv.org/abs/2410.13604)