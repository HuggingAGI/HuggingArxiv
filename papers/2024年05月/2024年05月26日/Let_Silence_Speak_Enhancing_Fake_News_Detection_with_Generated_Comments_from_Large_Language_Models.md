# 沉默之声：借助大型语言模型生成的评论，提升假新闻检测能力

发布时间：2024年05月26日

`LLM应用

这篇论文探讨了如何利用大型语言模型（LLMs）来模拟用户并生成评论，以增强假新闻检测的准确性。通过构建GenFEND框架，该研究展示了LLMs在生成多样化评论方面的应用，这些评论可以用来提高假新闻检测的性能。这种方法直接应用于实际问题解决，属于LLM应用的范畴。` `社交媒体` `新闻检测`

> Let Silence Speak: Enhancing Fake News Detection with Generated Comments from Large Language Models

# 摘要

> 假新闻检测对于保护社交媒体用户和维护新闻生态的健康至关重要。现有研究显示，基于评论的检测方法颇具前景，因为评论能揭示用户的真实想法和情感，增强模型对假新闻的辨识力。但现实中，由于曝光偏差和用户评论意愿的差异，获取多样化评论颇具挑战，尤其是在假新闻早期检测阶段。若忽视了“沉默”用户的意见，新闻真实性的判断可能因此失真。本文探索了一种新途径：利用大型语言模型（LLMs）模拟用户并生成评论，构建了GenFEND框架，该框架通过模拟多样化的用户群体生成评论，并将其汇总分析。实验结果表明，GenFEND不仅有效，而且生成的评论覆盖面更广，甚至优于实际评论，为假新闻检测提供了新的视角。

> Fake news detection plays a crucial role in protecting social media users and maintaining a healthy news ecosystem. Among existing works, comment-based fake news detection methods are empirically shown as promising because comments could reflect users' opinions, stances, and emotions and deepen models' understanding of fake news. Unfortunately, due to exposure bias and users' different willingness to comment, it is not easy to obtain diverse comments in reality, especially for early detection scenarios. Without obtaining the comments from the ``silent'' users, the perceived opinions may be incomplete, subsequently affecting news veracity judgment. In this paper, we explore the possibility of finding an alternative source of comments to guarantee the availability of diverse comments, especially those from silent users. Specifically, we propose to adopt large language models (LLMs) as a user simulator and comment generator, and design GenFEND, a generated feedback-enhanced detection framework, which generates comments by prompting LLMs with diverse user profiles and aggregating generated comments from multiple subpopulation groups. Experiments demonstrate the effectiveness of GenFEND and further analysis shows that the generated comments cover more diverse users and could even be more effective than actual comments.

![沉默之声：借助大型语言模型生成的评论，提升假新闻检测能力](../../../paper_images/2405.16631/x1.png)

![沉默之声：借助大型语言模型生成的评论，提升假新闻检测能力](../../../paper_images/2405.16631/x2.png)

![沉默之声：借助大型语言模型生成的评论，提升假新闻检测能力](../../../paper_images/2405.16631/early_detection.png)

![沉默之声：借助大型语言模型生成的评论，提升假新闻检测能力](../../../paper_images/2405.16631/diversity_all.png)

![沉默之声：借助大型语言模型生成的评论，提升假新闻检测能力](../../../paper_images/2405.16631/user-study.png)

[Arxiv](https://arxiv.org/abs/2405.16631)