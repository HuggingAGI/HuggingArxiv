# 运用大型语言模型剖析立陶宛网络评论的情感色彩

发布时间：2024年07月29日

`LLM应用` `情感分析`

> Sentiment Analysis of Lithuanian Online Reviews Using Large Language Models

# 摘要

> 情感分析作为NLP的热门研究领域，因自动化解决方案的兴起而备受瞩目。然而，语言的复杂性和情感的主观性使得这一任务颇具挑战，尤其是对于立陶宛语这类资源匮乏的语言。我们的研究发现，传统机器学习方法在立陶宛语情感分析中效果有限。为此，我们首次采用转换器模型，利用预训练的多语种LLMs，特别是微调BERT和T5模型，对收集自多个领域的立陶宛语五星级在线评论进行情感分析。结果显示，这些模型在情感表达较为明确时表现卓越，一星和五星评论的识别准确率分别达到80.74%和89.61%，远超当前顶尖的GPT-4。我们已将这些微调模型公开分享，供研究使用。

> Sentiment analysis is a widely researched area within Natural Language Processing (NLP), attracting significant interest due to the advent of automated solutions. Despite this, the task remains challenging because of the inherent complexity of languages and the subjective nature of sentiments. It is even more challenging for less-studied and less-resourced languages such as Lithuanian. Our review of existing Lithuanian NLP research reveals that traditional machine learning methods and classification algorithms have limited effectiveness for the task. In this work, we address sentiment analysis of Lithuanian five-star-based online reviews from multiple domains that we collect and clean. We apply transformer models to this task for the first time, exploring the capabilities of pre-trained multilingual Large Language Models (LLMs), specifically focusing on fine-tuning BERT and T5 models. Given the inherent difficulty of the task, the fine-tuned models perform quite well, especially when the sentiments themselves are less ambiguous: 80.74% and 89.61% testing recognition accuracy of the most popular one- and five-star reviews respectively. They significantly outperform current commercial state-of-the-art general-purpose LLM GPT-4. We openly share our fine-tuned LLMs online.

[Arxiv](https://arxiv.org/abs/2407.19914)