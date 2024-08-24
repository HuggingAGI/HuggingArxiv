# DAAD：针对虚假新闻检测的动态分析与自适应判别技术

发布时间：2024年08月20日

`LLM应用` `社交媒体` `新闻业`

> DAAD: Dynamic Analysis and Adaptive Discriminator for Fake News Detection

# 摘要

> 在当今网络环境中，假新闻如野火般在社交网络中蔓延，严重威胁社会秩序。现有的多模态假新闻检测方法，无论是基于知识还是语义，都过于依赖人类专家，缺乏灵活性。为此，我们创新性地提出了动态分析与自适应判别器（DAAD）方法，旨在提升假新闻检测的效率与准确性。对于基于知识的方法，我们巧妙地运用蒙特卡洛树搜索算法，充分发挥大型语言模型的自省能力，优化提示，为模型注入更丰富的领域知识，同时增强其对新闻内容的灵活评论。在语义层面，我们精准定义了四种欺骗模式：情感夸张、逻辑矛盾、图像篡改和语义不一致，深入剖析假新闻的制造机制。我们精心设计了四个判别器，并采用软路由机制，在深度与广度上拓展其能力，力求构建最优的检测模型。实验结果显示，我们的方法在三个真实数据集上表现卓越。相关代码即将在GitHub上发布，敬请期待。

> In current web environment, fake news spreads rapidly across online social networks, posing serious threats to society. Existing multimodal fake news detection (MFND) methods can be classified into knowledge-based and semantic-based approaches. However, these methods are overly dependent on human expertise and feedback, lacking flexibility. To address this challenge, we propose a Dynamic Analysis and Adaptive Discriminator (DAAD) approach for fake news detection. For knowledge-based methods, we introduce the Monte Carlo Tree Search (MCTS) algorithm to leverage the self-reflective capabilities of large language models (LLMs) for prompt optimization, providing richer, domain-specific details and guidance to the LLMs, while enabling more flexible integration of LLM comment on news content. For semantic-based methods, we define four typical deceit patterns: emotional exaggeration, logical inconsistency, image manipulation, and semantic inconsistency, to reveal the mechanisms behind fake news creation. To detect these patterns, we carefully design four discriminators and expand them in depth and breadth, using the soft-routing mechanism to explore optimal detection models. Experimental results on three real-world datasets demonstrate the superiority of our approach. The code will be available at: https://github.com/SuXinqi/DAAD.

[Arxiv](https://arxiv.org/abs/2408.10883)