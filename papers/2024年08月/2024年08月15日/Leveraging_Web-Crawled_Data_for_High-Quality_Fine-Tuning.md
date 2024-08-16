# 借助网络爬取数据，实现高质量微调

发布时间：2024年08月15日

`LLM应用` `人工智能`

> Leveraging Web-Crawled Data for High-Quality Fine-Tuning

# 摘要

> 大多数大型语言模型依赖昂贵的人工标注数据或 GPT-4 生成的数据进行微调，但这些数据在特定领域的表现无法保证。我们认为，尽管网络爬取的数据存在格式错误，仍可作为特定领域高质量微调的宝贵资源，无需依赖 GPT-4 等先进模型。为此，我们通过将网络数据与少量高质量数据配对，自动创建了训练数据集。实验显示，使用模型转换的网络数据训练，在解决中文数学问题时，平均得分比仅用高质量数据训练高出 9.4%。此外，我们的 7B 模型不仅超越了多个大型开源模型，还优于 GPT-3.5 等知名闭源模型，充分证明了我们方法的有效性。

> Most large language models are fine-tuned using either expensive human-annotated data or GPT-4 generated data which cannot guarantee performance in certain domains. We argue that although the web-crawled data often has formatting errors causing semantic inaccuracies, it can still serve as a valuable source for high-quality supervised fine-tuning in specific domains without relying on advanced models like GPT-4. To this end, we create a paired training dataset automatically by aligning web-crawled data with a smaller set of high-quality data. By training a language model on this dataset, we can convert web data with irregular formats into high-quality ones. Our experiments show that training with the model-transformed data yields better results, surpassing training with only high-quality data by an average score of 9.4% in Chinese math problems. Additionally, our 7B model outperforms several open-source models larger than 32B and surpasses well-known closed-source models such as GPT-3.5, highlighting the efficacy of our approach.

[Arxiv](https://arxiv.org/abs/2408.08003)