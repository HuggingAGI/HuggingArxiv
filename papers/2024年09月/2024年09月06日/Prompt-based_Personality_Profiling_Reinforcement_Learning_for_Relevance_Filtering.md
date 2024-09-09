# 提示驱动的人格剖析：强化学习助力相关性筛选

发布时间：2024年09月06日

`LLM应用` `社交媒体` `用户画像`

> Prompt-based Personality Profiling: Reinforcement Learning for Relevance Filtering

# 摘要

> 作者画像任务通过分析个人分享的内容来推断其特征。尽管大型语言模型在自然语言理解任务中表现出色，但监督机器学习仍是执行此任务的主流方法。原因之一是分类实例包含大量帖子，可能超过Transformer的输入长度。即使模型能处理大上下文，所有帖子的处理成本高且速度慢。为此，我们提出一种新方法，先区分相关与不相关内容，再仅用相关数据进行用户画像。通过强化学习优化相关性过滤器，利用大型语言模型的零-shot能力，我们避免了标注数据的需要。在Twitter语料库上，我们的方法在标签分布偏斜的公开数据上表现与使用所有帖子相当，但上下文更短。在人工平衡的数据上，过滤相关帖子显著提升了预测准确性。

> Author profiling is the task of inferring characteristics about individuals by analyzing content they share. Supervised machine learning still dominates automatic systems that perform this task, despite the popularity of prompting large language models to address natural language understanding tasks. One reason is that the classification instances consist of large amounts of posts, potentially a whole user profile, which may exceed the input length of Transformers. Even if a model can use a large context window, the entirety of posts makes the application of API-accessed black box systems costly and slow, next to issues which come with such "needle-in-the-haystack" tasks. To mitigate this limitation, we propose a new method for author profiling which aims at distinguishing relevant from irrelevant content first, followed by the actual user profiling only with relevant data. To circumvent the need for relevance-annotated data, we optimize this relevance filter via reinforcement learning with a reward function that utilizes the zero-shot capabilities of large language models. We evaluate our method for Big Five personality trait prediction on two Twitter corpora. On publicly available real-world data with a skewed label distribution, our method shows similar efficacy to using all posts in a user profile, but with a substantially shorter context. An evaluation on a version of these data balanced with artificial posts shows that the filtering to relevant posts leads to a significantly improved accuracy of the predictions.

[Arxiv](https://arxiv.org/abs/2409.04122)