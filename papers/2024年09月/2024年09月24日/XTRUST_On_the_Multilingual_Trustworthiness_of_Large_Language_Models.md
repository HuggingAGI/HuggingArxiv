# XTRUST：探讨大型语言模型在多语言环境中的可信度

发布时间：2024年09月24日

`LLM应用`

> XTRUST: On the Multilingual Trustworthiness of Large Language Models

# 摘要

> 大型语言模型 (LLM) 在 NLP 任务中的出色表现引起了广泛关注。然而，随着 LLM 在医疗和金融等敏感领域的应用增多，其信任问题变得尤为重要。现有研究多集中在单一语言（如英语），而全球部署的需求促使我们推出 XTRUST，首个多语言信任度基准。XTRUST 涵盖非法活动、幻觉、OOD 鲁棒性等 10 种语言的多个主题。我们评估了五种常用 LLM 的多语言信任度，发现它们在低资源语言（如阿拉伯语和俄语）上表现欠佳，显示了当前模型在多语言信任度上的改进空间。代码已公开，详见 https://github.com/LluckyYH/XTRUST。

> Large language models (LLMs) have demonstrated remarkable capabilities across a range of natural language processing (NLP) tasks, capturing the attention of both practitioners and the broader public. A key question that now preoccupies the AI community concerns the capabilities and limitations of these models, with trustworthiness emerging as a central issue, particularly as LLMs are increasingly applied in sensitive fields like healthcare and finance, where errors can have serious consequences. However, most previous studies on the trustworthiness of LLMs have been limited to a single language, typically the predominant one in the dataset, such as English. In response to the growing global deployment of LLMs, we introduce XTRUST, the first comprehensive multilingual trustworthiness benchmark. XTRUST encompasses a diverse range of topics, including illegal activities, hallucination, out-of-distribution (OOD) robustness, physical and mental health, toxicity, fairness, misinformation, privacy, and machine ethics, across 10 different languages. Using XTRUST, we conduct an empirical evaluation of the multilingual trustworthiness of five widely used LLMs, offering an in-depth analysis of their performance across languages and tasks. Our results indicate that many LLMs struggle with certain low-resource languages, such as Arabic and Russian, highlighting the considerable room for improvement in the multilingual trustworthiness of current language models. The code is available at https://github.com/LluckyYH/XTRUST.

[Arxiv](https://arxiv.org/abs/2409.15762)