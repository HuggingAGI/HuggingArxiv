# 利用大型语言模型提升去噪推荐中的硬样本识别

发布时间：2024年09月16日

`LLM应用` `推荐系统` `电子商务`

> Large Language Model Enhanced Hard Sample Identification for Denoising Recommendation

# 摘要

> 隐式反馈在推荐系统中常被使用，但因误点击和位置偏差等因素，难免会遇到噪声。以往的研究尝试通过识别高损失值等分歧模式来缓解噪声，但现有方法在区分困难样本和噪声样本时效果有限。为此，我们提出了LLMHD框架，利用LLM评分器评估项目与用户偏好的语义一致性，并通过基于方差的样本修剪策略提高效率。此外，迭代偏好更新模块持续优化用户偏好，以应对虚假交互带来的偏差。实验证明，我们的方法在多个数据集和推荐系统中表现出色。

> Implicit feedback, often used to build recommender systems, unavoidably confronts noise due to factors such as misclicks and position bias. Previous studies have attempted to alleviate this by identifying noisy samples based on their diverged patterns, such as higher loss values, and mitigating the noise through sample dropping or reweighting. Despite the progress, we observe existing approaches struggle to distinguish hard samples and noise samples, as they often exhibit similar patterns, thereby limiting their effectiveness in denoising recommendations. To address this challenge, we propose a Large Language Model Enhanced Hard Sample Denoising (LLMHD) framework. Specifically, we construct an LLM-based scorer to evaluate the semantic consistency of items with the user preference, which is quantified based on summarized historical user interactions. The resulting scores are used to assess the hardness of samples for the pointwise or pairwise training objectives. To ensure efficiency, we introduce a variance-based sample pruning strategy to filter potential hard samples before scoring. Besides, we propose an iterative preference update module designed to continuously refine summarized user preference, which may be biased due to false-positive user-item interactions. Extensive experiments on three real-world datasets and four backbone recommenders demonstrate the effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2409.10343)