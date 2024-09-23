# 利用预训练的多语言 BERT 嵌入技术，提升恶意提示注入攻击的检测效率

发布时间：2024年09月20日

`LLM应用` `网络安全` `机器学习`

> Applying Pre-trained Multilingual BERT in Embeddings for Improved Malicious Prompt Injection Attacks Detection

# 摘要

> 大型语言模型 (LLM) 虽然能力卓越，广泛应用于各个领域，但也带来了显著的安全隐患。特别是，当前方法在应对恶意提示注入攻击的复杂性和演变性方面可能力不从心。因此，本研究聚焦于这一最危险的漏洞，探讨如何利用多语言 BERT 等 BERT 变体来有效区分恶意与合法提示。通过分词和嵌入技术，我们提升了高斯朴素贝叶斯、随机森林、支持向量机和逻辑回归等多种机器学习方法的性能。实验结果显示，多语言 BERT 嵌入方法显著优于现有技术，逻辑回归模型准确率高达 96.55%。此外，我们还分析了模型的错误预测，以揭示其局限性，为未来研究提供方向。

> Large language models (LLMs) are renowned for their exceptional capabilities, and applying to a wide range of applications. However, this widespread use brings significant vulnerabilities. Also, it is well observed that there are huge gap which lies in the need for effective detection and mitigation strategies against malicious prompt injection attacks in large language models, as current approaches may not adequately address the complexity and evolving nature of these vulnerabilities in real-world applications. Therefore, this work focuses the impact of malicious prompt injection attacks which is one of most dangerous vulnerability on real LLMs applications. It examines to apply various BERT (Bidirectional Encoder Representations from Transformers) like multilingual BERT, DistilBert for classifying malicious prompts from legitimate prompts. Also, we observed how tokenizing the prompt texts and generating embeddings using multilingual BERT contributes to improve the performance of various machine learning methods: Gaussian Naive Bayes, Random Forest, Support Vector Machine, and Logistic Regression. The performance of each model is rigorously analyzed with various parameters to improve the binary classification to discover malicious prompts. Multilingual BERT approach to embed the prompts significantly improved and outperformed the existing works and achieves an outstanding accuracy of 96.55% by Logistic regression. Additionally, we investigated the incorrect predictions of the model to gain insights into its limitations. The findings can guide researchers in tuning various BERT for finding the most suitable model for diverse LLMs vulnerabilities.

[Arxiv](https://arxiv.org/abs/2409.13331)