# 利用高级歌曲描述符实现基于自然语言的音乐推荐

发布时间：2024年11月08日

`LLM应用` `推荐系统`

> Harnessing High-Level Song Descriptors towards Natural Language-Based Music Recommendation

# 摘要

> 依赖语言模型（LMs）的推荐系统在帮助用户浏览大型目录方面越来越受欢迎。LMs 经常从训练数据或用户偏好中利用项目的高级描述符，即类别或消费情境。这在电影或产品等领域已被证明是有效的。然而，在音乐领域，了解 LMs 如何有效地利用歌曲描述符进行基于自然语言的音乐推荐相对有限。在本文中，我们根据用户的自然语言描述和具有诸如流派、情绪和收听情境等描述符的项目来评估 LMs 在推荐歌曲方面的有效性。我们将推荐任务制定为密集检索问题，并在 LMs 对与任务和领域相关的数据越来越熟悉时对其进行评估。我们的发现表明，随着 LMs 针对一般语言相似性、信息检索以及将较长描述映射到音乐中较短的高级描述符进行微调，性能得到了改善。

> Recommender systems relying on Language Models (LMs) have gained popularity in assisting users to navigate large catalogs. LMs often exploit item high-level descriptors, i.e. categories or consumption contexts, from training data or user preferences. This has been proven effective in domains like movies or products. However, in the music domain, understanding how effectively LMs utilize song descriptors for natural language-based music recommendation is relatively limited. In this paper, we assess LMs effectiveness in recommending songs based on user natural language descriptions and items with descriptors like genres, moods, and listening contexts. We formulate the recommendation task as a dense retrieval problem and assess LMs as they become increasingly familiar with data pertinent to the task and domain. Our findings reveal improved performance as LMs are fine-tuned for general language similarity, information retrieval, and mapping longer descriptions to shorter, high-level descriptors in music.

[Arxiv](https://arxiv.org/abs/2411.05649)