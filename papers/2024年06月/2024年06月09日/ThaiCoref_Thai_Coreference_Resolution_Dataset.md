# ThaiCoref：泰语指代消解数据集，专注于提升泰语文本中的指代理解能力。

发布时间：2024年06月09日

`LLM应用

理由：这篇论文主要介绍了针对泰语的指代消解问题，并推出了一个名为 ThaiCoref 的数据集，以及基于此数据集训练的模型。论文中提到的模型结合了多语言编码器与跨语言迁移技术，这些都是大型语言模型（LLM）在特定语言处理任务中的应用。因此，这篇论文属于 LLM 应用类别。` `数据集构建`

> ThaiCoref: Thai Coreference Resolution Dataset

# 摘要

> 在 NLP 领域，指代消解虽已成熟，但针对泰语的研究却因缺乏大型标注语料库而受限。为此，我们推出了 ThaiCoref 数据集，专为泰语指代消解设计。该数据集涵盖 777,271 词元、44,082 提及和 10,429 实体，横跨大学论文、报纸、演讲及维基百科四大文本类型。我们基于 OntoNotes 基准调整了标注方案，以适应泰语特性。通过 ThaiCoref，我们训练的模型结合了多语言编码器与跨语言迁移技术，测试集上 F1 分数高达 67.88%。错误分析显示，泰语的独特语言特征带来了挑战。为促进 NLP 社区的发展，我们已在 http://www.github.com/nlp-chula/thai-coref 公开了数据集和模型。

> While coreference resolution is a well-established research area in Natural Language Processing (NLP), research focusing on Thai language remains limited due to the lack of large annotated corpora. In this work, we introduce ThaiCoref, a dataset for Thai coreference resolution. Our dataset comprises 777,271 tokens, 44,082 mentions and 10,429 entities across four text genres: university essays, newspapers, speeches, and Wikipedia. Our annotation scheme is built upon the OntoNotes benchmark with adjustments to address Thai-specific phenomena. Utilizing ThaiCoref, we train models employing a multilingual encoder and cross-lingual transfer techniques, achieving a best F1 score of 67.88\% on the test set. Error analysis reveals challenges posed by Thai's unique linguistic features. To benefit the NLP community, we make the dataset and the model publicly available at http://www.github.com/nlp-chula/thai-coref .

[Arxiv](https://arxiv.org/abs/2406.06000)