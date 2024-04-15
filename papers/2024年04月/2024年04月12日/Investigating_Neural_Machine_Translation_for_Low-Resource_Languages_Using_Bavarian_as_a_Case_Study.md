# 探索低资源语言的神经机器翻译：以巴伐利亚语为案例研究

发布时间：2024年04月12日

`LLM应用` `机器翻译` `低资源语言`

> Investigating Neural Machine Translation for Low-Resource Languages: Using Bavarian as a Case Study

# 摘要

> 近年来，机器翻译技术飞速发展，让多种语言的翻译质量逼近人类翻译水平。然而，这些研究主要关注资源丰富、网络覆盖广泛的语言。得益于大型语言模型的发展，一些资源匮乏的语言开始通过其他语言的支持取得进步。但研究发现，并非所有资源较少的语言都能从多语种系统中获益，特别是那些缺乏足够训练和评估数据的语言。本文重新审视了神经机器翻译的最新技术，并致力于开发德语与巴伐利亚语之间的自动翻译系统。我们深入探讨了数据稀缺、参数敏感等低资源语言面临的挑战，并着眼于提出针对性的解决方案和创新方法，比如利用语言间的相似性。通过运用回译和迁移学习技术，我们的实验成功生成了更多训练数据，并显著提升了翻译质量。我们识别并处理了数据中的噪声问题，并采取了广泛的文本预处理措施。我们采用BLEU、chrF和TER等综合指标进行评估，经过Bonferroni校正的统计结果表明，基线系统表现出人意料地高效，回译技术显著提升了翻译效果。此外，我们还对翻译中的错误和系统局限性进行了深入的定性分析。

> Machine Translation has made impressive progress in recent years offering close to human-level performance on many languages, but studies have primarily focused on high-resource languages with broad online presence and resources. With the help of growing Large Language Models, more and more low-resource languages achieve better results through the presence of other languages. However, studies have shown that not all low-resource languages can benefit from multilingual systems, especially those with insufficient training and evaluation data. In this paper, we revisit state-of-the-art Neural Machine Translation techniques to develop automatic translation systems between German and Bavarian. We investigate conditions of low-resource languages such as data scarcity and parameter sensitivity and focus on refined solutions that combat low-resource difficulties and creative solutions such as harnessing language similarity. Our experiment entails applying Back-translation and Transfer Learning to automatically generate more training data and achieve higher translation performance. We demonstrate noisiness in the data and present our approach to carry out text preprocessing extensively. Evaluation was conducted using combined metrics: BLEU, chrF and TER. Statistical significance results with Bonferroni correction show surprisingly high baseline systems, and that Back-translation leads to significant improvement. Furthermore, we present a qualitative analysis of translation errors and system limitations.

[Arxiv](https://arxiv.org/abs/2404.08259)