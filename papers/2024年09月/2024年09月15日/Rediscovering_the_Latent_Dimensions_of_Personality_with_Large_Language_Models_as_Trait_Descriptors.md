# 借助大型语言模型，重新探索人格的潜在特质维度

发布时间：2024年09月15日

`LLM应用` `心理学` `人工智能`

> Rediscovering the Latent Dimensions of Personality with Large Language Models as Trait Descriptors

# 摘要

> 利用大型语言模型（LLM）评估人格特质，已成为一个既有趣又具挑战性的研究领域。传统方法依赖于大五人格模型的显式问卷，而我们提出，LLM在生成下一个词时，已隐含地编码了人格特征。为此，我们创新性地运用奇异值分解（SVD）处理特质形容词的对数概率，揭示了LLM中的潜在人格维度。实验结果显示，LLM无需直接问卷，便能“重现”外向性、宜人性、尽责性、神经质和开放性等核心特质，前五大因素解释了潜在空间中高达74.3%的方差。此外，我们利用这些主成分，在大五人格维度上进行评估，使预测准确性比微调模型提升5%，比直接LLM评分技术提升21%。

> Assessing personality traits using large language models (LLMs) has emerged as an interesting and challenging area of research. While previous methods employ explicit questionnaires, often derived from the Big Five model of personality, we hypothesize that LLMs implicitly encode notions of personality when modeling next-token responses. To demonstrate this, we introduce a novel approach that uncovers latent personality dimensions in LLMs by applying singular value de-composition (SVD) to the log-probabilities of trait-descriptive adjectives. Our experiments show that LLMs "rediscover" core personality traits such as extraversion, agreeableness, conscientiousness, neuroticism, and openness without relying on direct questionnaire inputs, with the top-5 factors corresponding to Big Five traits explaining 74.3% of the variance in the latent space. Moreover, we can use the derived principal components to assess personality along the Big Five dimensions, and achieve improvements in average personality prediction accuracy of up to 5% over fine-tuned models, and up to 21% over direct LLM-based scoring techniques.

[Arxiv](https://arxiv.org/abs/2409.09905)