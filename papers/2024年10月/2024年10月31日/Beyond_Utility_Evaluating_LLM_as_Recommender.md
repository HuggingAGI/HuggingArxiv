# 超越效用：对 LLM 作为推荐器予以评估

发布时间：2024年10月31日

`LLM应用` `推荐系统` `信息服务`

> Beyond Utility: Evaluating LLM as Recommender

# 摘要

> 随着大型语言模型（LLMs）的迅猛发展，近来的研究把 LLMs 当作推荐器，为不同用户提供个性化的信息服务。尽管一直在努力提升基于 LLM 的推荐模型的准确性，可对实用功能之外的维度关注却相对较少。而且，基于 LLM 的推荐模型存在独特的评估方面，这些在很大程度上被忽视了。为了填补这一空缺，我们探索了四个新的评估维度，并提出了一个多维评估框架。新的评估维度涵盖：1. 历史长度敏感性；2. 候选位置偏差；3. 涉及生成的性能；4. 幻觉。这四个维度都可能对性能产生影响，但在传统系统中基本无需考虑。运用这个多维评估框架以及传统方面，我们评估了七个基于 LLM 的推荐器的性能，采用了三种提示策略，在四个数据集上的排名和重新排名任务中，将它们与六个传统模型进行了对比。我们发现，在排名设定中，LLMs 善于处理具有先验知识和较短输入历史的任务，在重新排名设定中表现更优，在多个维度上胜过传统模型。然而，LLMs 存在大量的候选位置偏差问题，并且有些模型比其他模型更频繁地产生不存在的项目幻觉。我们期望我们的评估框架和观察结果能助力未来把 LLMs 用作推荐器的研究。代码和数据可在 https://github.com/JiangDeccc/EvaLLMasRecommender 获取。

> With the rapid development of Large Language Models (LLMs), recent studies employed LLMs as recommenders to provide personalized information services for distinct users. Despite efforts to improve the accuracy of LLM-based recommendation models, relatively little attention is paid to beyond-utility dimensions. Moreover, there are unique evaluation aspects of LLM-based recommendation models, which have been largely ignored. To bridge this gap, we explore four new evaluation dimensions and propose a multidimensional evaluation framework. The new evaluation dimensions include: 1) history length sensitivity, 2) candidate position bias, 3) generation-involved performance, and 4) hallucinations. All four dimensions have the potential to impact performance, but are largely unnecessary for consideration in traditional systems. Using this multidimensional evaluation framework, along with traditional aspects, we evaluate the performance of seven LLM-based recommenders, with three prompting strategies, comparing them with six traditional models on both ranking and re-ranking tasks on four datasets. We find that LLMs excel at handling tasks with prior knowledge and shorter input histories in the ranking setting, and perform better in the re-ranking setting, beating traditional models across multiple dimensions. However, LLMs exhibit substantial candidate position bias issues, and some models hallucinate non-existent items much more often than others. We intend our evaluation framework and observations to benefit future research on the use of LLMs as recommenders. The code and data are available at https://github.com/JiangDeccc/EvaLLMasRecommender.

[Arxiv](https://arxiv.org/abs/2411.00331)