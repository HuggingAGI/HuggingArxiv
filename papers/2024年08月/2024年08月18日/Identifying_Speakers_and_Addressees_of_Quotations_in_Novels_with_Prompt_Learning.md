# 借助提示学习，我们能在小说中精准定位引述的说话人与听话者。

发布时间：2024年08月18日

`LLM应用` `人工智能`

> Identifying Speakers and Addressees of Quotations in Novels with Prompt Learning

# 摘要

> 在小说等文学作品中，引用语不仅是塑造角色、映射关系的关键，也是推动故事发展的引擎。目前，引用语研究多聚焦于识别发言者，而忽视了受话者在关系构建中的作用。为此，我们创建了首个包含发言者、受话者等元素的中文引用语语料库，并采用基于提示学习的微调模型，有效识别发言者和受话者。实验证明，我们的方法在中英文数据集上均表现优异，超越了依赖零-shot和少-shot大型语言模型的传统方法。

> Quotations in literary works, especially novels, are important to create characters, reflect character relationships, and drive plot development. Current research on quotation extraction in novels primarily focuses on quotation attribution, i.e., identifying the speaker of the quotation. However, the addressee of the quotation is also important to construct the relationship between the speaker and the addressee. To tackle the problem of dataset scarcity, we annotate the first Chinese quotation corpus with elements including speaker, addressee, speaking mode and linguistic cue. We propose prompt learning-based methods for speaker and addressee identification based on fine-tuned pre-trained models. Experiments on both Chinese and English datasets show the effectiveness of the proposed methods, which outperform methods based on zero-shot and few-shot large language models.

[Arxiv](https://arxiv.org/abs/2408.09452)