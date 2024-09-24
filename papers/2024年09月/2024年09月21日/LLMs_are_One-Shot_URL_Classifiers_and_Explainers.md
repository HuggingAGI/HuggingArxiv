# LLM 即单次 URL 分类与解释神器

发布时间：2024年09月21日

`LLM应用` `网络安全`

> LLMs are One-Shot URL Classifiers and Explainers

# 摘要

> 恶意 URL 分类在网络安全中至关重要。尽管已有众多基于机器学习和深度学习的 URL 分类模型，但它们大多因缺乏代表性训练数据而面临泛化和领域适应问题。此外，这些模型无法以自然语言解释其分类结果。为此，我们探索并展示了大型语言模型 (LLM) 的应用。我们提出了一种基于 LLM 的单次学习框架，利用思维链 (CoT) 推理来判断 URL 的性质。通过三个数据集和五种顶尖 LLM 的评估，我们发现单次 LLM 提示的性能接近监督模型，其中 GPT 4-Turbo 表现最佳，Claude 3 Opus 紧随其后。定量分析显示，LLM 的解释与监督分类器的后验解释高度一致，且具有高可读性、连贯性和信息量。

> Malicious URL classification represents a crucial aspect of cyber security. Although existing work comprises numerous machine learning and deep learning-based URL classification models, most suffer from generalisation and domain-adaptation issues arising from the lack of representative training datasets. Furthermore, these models fail to provide explanations for a given URL classification in natural human language. In this work, we investigate and demonstrate the use of Large Language Models (LLMs) to address this issue. Specifically, we propose an LLM-based one-shot learning framework that uses Chain-of-Thought (CoT) reasoning to predict whether a given URL is benign or phishing. We evaluate our framework using three URL datasets and five state-of-the-art LLMs and show that one-shot LLM prompting indeed provides performances close to supervised models, with GPT 4-Turbo being the best model, followed by Claude 3 Opus. We conduct a quantitative analysis of the LLM explanations and show that most of the explanations provided by LLMs align with the post-hoc explanations of the supervised classifiers, and the explanations have high readability, coherency, and informativeness.

[Arxiv](https://arxiv.org/abs/2409.14306)