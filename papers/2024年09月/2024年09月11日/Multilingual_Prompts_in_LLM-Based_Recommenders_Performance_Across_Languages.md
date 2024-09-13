# LLM 推荐系统中的多语言提示：跨语言表现探究

发布时间：2024年09月11日

`LLM应用` `推荐系统` `多语言处理`

> Multilingual Prompts in LLM-Based Recommenders: Performance Across Languages

# 摘要

> 大型语言模型 (LLM) 在自然语言处理任务中日益普及。推荐系统传统上依赖协同过滤、矩阵分解等方法，以及深度学习和强化学习等先进技术。尽管语言模型已应用于推荐领域，但最新趋势是利用 LLM 的生成能力来提供更个性化的建议。当前研究多聚焦于英语，因其资源丰富，而本研究则探讨了非英语提示对推荐性能的影响。我们使用 OpenP5 平台，将英语提示模板扩展至西班牙语和土耳其语，并在 ML1M、LastFM 和 Amazon-Beauty 三个真实数据集上进行评估。结果显示，非英语提示通常会降低推荐性能，尤其是在资源较少的土耳其语中。此外，我们还重新训练了基于 LLM 的推荐模型，使用多语言提示，发现性能在各语言间更为平衡，但英语性能略有下降。这项研究强调了在基于 LLM 的推荐系统中支持多样化语言的重要性，并建议未来研究应创建更多评估数据集，使用更新的模型和更多语言。

> Large language models (LLMs) are increasingly used in natural language processing tasks. Recommender systems traditionally use methods such as collaborative filtering and matrix factorization, as well as advanced techniques like deep learning and reinforcement learning. Although language models have been applied in recommendation, the recent trend have focused on leveraging the generative capabilities of LLMs for more personalized suggestions. While current research focuses on English due to its resource richness, this work explores the impact of non-English prompts on recommendation performance. Using OpenP5, a platform for developing and evaluating LLM-based recommendations, we expanded its English prompt templates to include Spanish and Turkish. Evaluation on three real-world datasets, namely ML1M, LastFM, and Amazon-Beauty, showed that usage of non-English prompts generally reduce performance, especially in less-resourced languages like Turkish. We also retrained an LLM-based recommender model with multilingual prompts to analyze performance variations. Retraining with multilingual prompts resulted in more balanced performance across languages, but slightly reduced English performance. This work highlights the need for diverse language support in LLM-based recommenders and suggests future research on creating evaluation datasets, using newer models and additional languages.

[Arxiv](https://arxiv.org/abs/2409.07604)