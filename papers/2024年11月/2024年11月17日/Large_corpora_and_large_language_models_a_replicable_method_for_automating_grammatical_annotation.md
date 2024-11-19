# 大型语料库与大型语言模型：一种实现自动语法标注的可复制之法

发布时间：2024年11月17日

`LLM应用` `语言学` `AI 协作`

> Large corpora and large language models: a replicable method for automating grammatical annotation

# 摘要

> 许多语言学研究都依赖从文本语料库中提取特征的标注数据集，然而这些语料库的快速大量增长，给语言学家手动标注大量数据样本造成了实际困难。在本文中，我们呈现了一种可复制、受监督的方法，借助大型语言模型，通过提示工程、训练和评估来辅助语言学家进行语法标注。我们引入了一种方法流程，应用于基于大型语言模型 Claude 3.5 Sonnet 以及 Davies' NOW 和 EnTenTen21（SketchEngine）语料库数据的英语评价动词结构“consider X (as) (to be) Y”的形式变化这一案例研究。总的来说，我们在保留的测试样本上仅用少量训练数据就实现了超过 90％的模型准确率，证实了该方法未来对该结构大量标记进行标注的有效性。我们探讨了我们的结果对于更广泛的语法结构及语法变异和变化案例研究的通用性，突出了 AI 协作者作为未来语言学研究工具的价值。

> Much linguistic research relies on annotated datasets of features extracted from text corpora, but the rapid quantitative growth of these corpora has created practical difficulties for linguists to manually annotate large data samples. In this paper, we present a replicable, supervised method that leverages large language models for assisting the linguist in grammatical annotation through prompt engineering, training, and evaluation. We introduce a methodological pipeline applied to the case study of formal variation in the English evaluative verb construction 'consider X (as) (to be) Y', based on the large language model Claude 3.5 Sonnet and corpus data from Davies' NOW and EnTenTen21 (SketchEngine). Overall, we reach a model accuracy of over 90% on our held-out test samples with only a small amount of training data, validating the method for the annotation of very large quantities of tokens of the construction in the future. We discuss the generalisability of our results for a wider range of case studies of grammatical constructions and grammatical variation and change, underlining the value of AI copilots as tools for future linguistic research.

[Arxiv](https://arxiv.org/abs/2411.11260)