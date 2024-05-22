# 时间因素不容忽视：强化预训练新闻推荐模型，引入用户停留时间的稳健注入

发布时间：2024年05月21日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在新闻推荐系统中的应用，特别是在理解和捕捉用户偏好方面的挑战。论文提出了两种创新的策略来利用用户停留时间信息，以优化推荐系统的表现。这些策略直接应用于实际的新闻推荐场景中，通过实验验证了其有效性。因此，这篇论文属于LLM应用类别，因为它关注的是LLMs在特定应用领域（即新闻推荐系统）的实际应用和改进。` `新闻推荐` `用户偏好分析`

> Time Matters: Enhancing Pre-trained News Recommendation Models with Robust User Dwell Time Injection

# 摘要

> 大型语言模型（LLMs）的兴起，使得新闻推荐系统能够深入理解文本，达到行业顶尖水平。然而，由于点击行为的不确定性，准确捕捉用户偏好依旧是一大挑战。尽管Transformer中的多头注意力技术尝试通过分析点击交互来缓解这一问题，但在整合明确用户反馈方面仍有欠缺。用户停留时间作为一种强有力的指标，能够增强点击行为中蕴含的微弱信号。但在实际应用中，由于数据收集可能存在的延迟，其有效性受到质疑。为此，本文提出了两种创新的停留时间注入策略：停留时间权重（DweW）和停留时间感知（DweA）。DweW通过深入分析停留时间，优化用户点击的有效性，并与初始行为数据结合，构建更为稳健的用户偏好模型。DweA则让模型能够感知停留时间信息，自主调整用户模型中的注意力权重，从而更精准地识别用户偏好。我们在MSN网站的真实新闻数据集上进行的实验表明，这两种策略显著提升了推荐质量，更倾向于推荐高质量新闻。更重要的是，即使在极端情况下（如完全缺失停留时间数据），我们的方法依然能够保持推荐高质量内容的能力，显示出对用户停留时间信息的强大适应性。

> Large Language Models (LLMs) have revolutionized text comprehension, leading to State-of-the-Art (SOTA) news recommendation models that utilize LLMs for in-depth news understanding. Despite this, accurately modeling user preferences remains challenging due to the inherent uncertainty of click behaviors. Techniques like multi-head attention in Transformers seek to alleviate this by capturing interactions among clicks, yet they fall short in integrating explicit feedback signals. User Dwell Time emerges as a powerful indicator, offering the potential to enhance the weak signals emanating from clicks. Nonetheless, its real-world applicability is questionable, especially when dwell time data collection is subject to delays. To bridge this gap, this paper proposes two novel and robust dwell time injection strategies, namely Dwell time Weight (DweW) and Dwell time Aware (DweA). Dwe} concentrates on refining Effective User Clicks through detailed analysis of dwell time, integrating with initial behavioral inputs to construct a more robust user preference. DweA empowers the model with awareness of dwell time information, thereby facilitating autonomous adjustment of attention values in user modeling. This enhancement sharpens the model's ability to accurately identify user preferences. In our experiment using the real-world news dataset from MSN website, we validated that our two strategies significantly improve recommendation performance, favoring high-quality news. Crucially, our approaches exhibit robustness to user dwell time information, maintaining their ability to recommend high-quality content even in extreme cases where dwell time data is entirely missing.

[Arxiv](https://arxiv.org/abs/2405.12486)