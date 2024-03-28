# X-Shot 系统集大成，一举囊括了分类任务中频繁出现、少量样本及零样本的学习场景，实现了一体化解决方案。

发布时间：2024年03月06日

`LLM应用`

> X-Shot: A Unified System to Handle Frequent, Few-shot and Zero-shot Learning Simultaneously in Classification

# 摘要

> 近年来，few-shot 和 zero-shot 学习因能在少量标注样本情况下预测标签而备受瞩目。以往研究通常孤立地看待不同频次标签的问题，如频繁标签（freq-shot）、少量标签和零样本标签，只针对某一特定场景优化系统。然而，在现实世界中，各类标签出现的频次差异极大，有的标签数量众多，有的则稀疏或未曾出现。对于实际应用来说，系统具备对任意频次标签的适应能力至关重要。因此，我们提出了一项全新的挑战——X-shot，模拟真实环境中无预设上限条件下freq-shot、few-shot及zero-shot标签共同出现的情况，其中X代表的次数可以从0延伸至正无穷大。X-shot问题的核心在于实现开放领域的泛化能力和构建能灵活应对多种标签情况的系统。为此，我们创新性地提出了BinBin方法，该方法通过遵循指令的方式利用大规模NLP任务集合所提供的间接监督，并结合大型语言模型给予的弱监督强化训练。在跨多个领域的三个基准数据集上，BinBin成功超越了之前的最新技术水平。据我们所知，这是首次尝试解决具有可变X值的X-shot学习问题的研究。

> In recent years, few-shot and zero-shot learning, which learn to predict labels with limited annotated instances, have garnered significant attention. Traditional approaches often treat frequent-shot (freq-shot; labels with abundant instances), few-shot, and zero-shot learning as distinct challenges, optimizing systems for just one of these scenarios. Yet, in real-world settings, label occurrences vary greatly. Some of them might appear thousands of times, while others might only appear sporadically or not at all. For practical deployment, it is crucial that a system can adapt to any label occurrence. We introduce a novel classification challenge: X-shot, reflecting a real-world context where freq-shot, few-shot, and zero-shot labels co-occur without predefined limits. Here, X can span from 0 to positive infinity. The crux of X-shot centers on open-domain generalization and devising a system versatile enough to manage various label scenarios. To solve X-shot, we propose BinBin (Binary INference Based on INstruction following) that leverages the Indirect Supervision from a large collection of NLP tasks via instruction following, bolstered by Weak Supervision provided by large language models. BinBin surpasses previous state-of-the-art techniques on three benchmark datasets across multiple domains. To our knowledge, this is the first work addressing X-shot learning, where X remains variable.

[Arxiv](https://arxiv.org/abs/2403.03863)