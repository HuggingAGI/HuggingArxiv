# OntoNotes 5.0下的研究：探索注释错误对命名实体识别的影响

发布时间：2024年06月27日

`LLM应用

理由：这篇论文主要关注的是命名实体识别（NER）任务中的数据集质量问题，并提出了一种改进数据集标注错误的方法。虽然NER是NLP领域的一个具体应用，但论文的核心贡献在于数据集的改进，这对于训练和评估大型语言模型（LLM）在NER任务上的表现具有重要意义。因此，这篇论文更偏向于LLM的应用层面，即如何通过改进数据集来提升LLM在特定任务上的性能。` `数据集标注`

> Annotation Errors and NER: A Study with OntoNotes 5.0

# 摘要

> 命名实体识别（NER）在NLP领域备受关注，但相较于新模型的开发，NER数据集的研究却鲜有人问津。本文中，我们运用三种简便技术，对英语NER最大的语料库OntoNotes 5.0进行了标注错误的检测。这些技术纠正了训练、开发和测试数据中约10%的句子，并对数据集中约8%的实体提及的跨度和/或类型进行了修正，同时进行了一些增删分割合并操作。考虑到OntoNotes的庞大规模，这些修正的影响不容小觑。我们利用三个NER库对原始数据集和重新标注数据集训练的模型进行了训练、评估和比较，发现总体F-score平均提升了1.23%，某些实体类型的提升甚至超过了10%。尽管我们的标注错误检测方法并非无懈可击，且涉及一定程度的手动标注，但它们具有较强的语言通用性，可应用于其他NER数据集及序列标注任务。

> Named Entity Recognition (NER) is a well-studied problem in NLP. However, there is much less focus on studying NER datasets, compared to developing new NER models. In this paper, we employed three simple techniques to detect annotation errors in the OntoNotes 5.0 corpus for English NER, which is the largest available NER corpus for English. Our techniques corrected ~10% of the sentences in train/dev/test data. In terms of entity mentions, we corrected the span and/or type of ~8% of mentions in the dataset, while adding/deleting/splitting/merging a few more. These are large numbers of changes, considering the size of OntoNotes. We used three NER libraries to train, evaluate and compare the models trained with the original and the re-annotated datasets, which showed an average improvement of 1.23% in overall F-scores, with large (>10%) improvements for some of the entity types. While our annotation error detection methods are not exhaustive and there is some manual annotation effort involved, they are largely language agnostic and can be employed with other NER datasets, and other sequence labelling tasks.

[Arxiv](https://arxiv.org/abs/2406.19172)